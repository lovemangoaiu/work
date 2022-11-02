<template>
    <div class="student">
        <h2>学生姓名：{{name}}</h2>
        <h2>学生性别：{{sex}}</h2>
        <h2>当前求和为：{{number}}</h2>
        <button @click="add">点我number++</button>
        <button @click="sendStudentlName">把学生名给App</button>
        <button @click="unbind">解绑atguigu事件</button>
        <button @click="death">销毁当前Student组件的实例(vc)</button>
        

    </div>
</template>

<script>
export default{
    name:'Student',
    data(){
        return{
            name:'张三',
            sex:'男',
            number:0
        }
    },
    methods: {
        add(){
            console.log('add回调被调用了')
            this.number++
        },
        sendStudentlName(){
            this.$emit('atguigu',this.name,666,888)
            this.$emit('demo')
        },
        unbind(){
            //this.$off('aatguigu')//解绑一个
            //this.$off(['aatguigu','demo'])//解绑多个
            this.$off()//解绑所有的自定义事件
        },
        death(){
            this.$destroy()//销毁当前Student组件的实例
        }
    },
}
</script>
<style lang="less" scoped>
.student{
    background-color: pink;
    padding: 5px;
    margin-top: 30px;
}
</style>