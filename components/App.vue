<template>
    <div class="app">
       <h1>{{msg}}</h1>
       <School: getSchoolName="getSchoolName"/>
       <!-- <Student v-on:atguigu="getStudentName"/> -->
       <!-- <Student @atguigu.once="getStudentName"/> -->
       <Student ref='student'/>
    </div>
</template>

<script>
import Student from './student.vue'
import School from './school.vue'
export default{
    name:'App',
    components:{
        School,
        Student,
    },
    data(){
        return{
            msg:'你好呀！'
        }
    },
    methods:{
        getSchoolName(name){
            console.log('App收到了学校名：',name)
        },
        getStudentName(name,...params){
            console.log('App收到了学生名：',name,params)
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