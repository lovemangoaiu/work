<template>
    <div class="school">
        <h2>学校名称：{{name}}</h2>
        <h2>学校地址：{{address}}</h2>
        <button @click="sendSchoolName">把学校名给App</button>
    </div>
</template>

<script>
export default{
    name:'school',
    props:['getSchoolName'],
    data(){
        return{
            name:'青海',
            address:'西宁',
        }
    },
    methods: {
        sendSchoolName(){
            this.getSchoolName(this.name)
        }
    },
}
</script>
<style scoped>
.school{
    background-color: skyblue;
    padding: 5px;
}
</style>