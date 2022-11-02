<template>
    <div class="app">
       <h1>{{msg}}，学生姓名是：{{name}}</h1>
       <School: getSchoolName="getSchoolName"/>

       <!-- <Student v-on:atguigu="getStudentName"/> -->

       <!-- <Student @atguigu="getStudentName" @demo="m1"/> -->

       <Student ref='student' @click.native="show"/>
    </div>
</template>

<script>
import Student from '../components/student.vue'
import School from '../components/school.vue'
export default{
    name:'App',
    components:{
        School,
        Student,
    },
    data(){
        return{
            msg:'你好呀！',
            studentName:''
        }
    },
    methods:{
        getSchoolName(name){
            console.log('App收到了学校名：',name)
        },
        getStudentName(name,...params){
            console.log('App收到了学生名：',name,params)
            this.studentName=name
        },
        m1(){
            console.log('demo事件被触发了！')
        },
        show(){
            alert(123)
        }
    },
    mounted() {
        // setTimeout(()=>{
        //     this.$refs.student.$on('atguigu',this.getStudentName)
        // },1000)
            this.$refs.student.$once('atguigu',this.getStudentName)
    },

}
</script>
<style scoped>
.app{
    background-color: gray;
    padding:5px;
}
</style>