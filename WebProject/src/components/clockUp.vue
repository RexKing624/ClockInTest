<template>
  <div>
<!--      <h1>{{ msg }}</h1>-->
      <el-row class="rowBox">
          <el-button class="btu" @click="submit()">{{ btuName }}</el-button>
<!--          <el-button class="btu" @click="submit()">test</el-button>-->
      </el-row>
  </div>
</template>
<script>
export default {
    props: {
        btuName: String,
    },
    data(){
        return{
        }
    },
    mounted() {
        console.log('-------===-------')
    },
    methods:{
        submit(){
            console.log(this.btuName,'-----')
            // var timestamp = Date.parse(new Date());
            // console.log(timestamp,'=====')
            var myDate = new Date();
            // var Yer=myDate.getMonth();
            var timeStamp = myDate.getTime()
            var newDate = new Date(timeStamp);
            console.log(timeStamp)

        },


    },

}
</script>

<style scoped>
 .rowBox{
     .btu{
         background-color: red;
         color: red;
         margin-left: 1000px;
     }
 }
</style>