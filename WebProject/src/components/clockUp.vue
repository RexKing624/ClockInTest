<template>
  <div>
      <el-row class="rowBox">
          <el-button class="btu" @click="submit()">{{ btuName }}</el-button>
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
        // console.log('-------===-------')
    },
    methods:{
        submit(){
            console.log(this.btuName,'-----')
            var myDate = new Date();
            var timeStamp = myDate.getTime()
            var newDate = new Date(timeStamp);
            console.log(timeStamp)
            console.log(myDate,'----')

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