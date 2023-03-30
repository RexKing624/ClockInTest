<template>
  <div>
<!--      <h1>{{ msg }}</h1>-->
      <row class="rowBox">
          <button class="btu" @click="submit()">{{ btuName }}</button>
      </row>
  </div>
</template>
<script  setup>
defineProps({
    btuName: {
       type: String,
       required: true
     },
})
//     data(){
//
//     },
//     methods(){
//         const submit = () => {
//           console.log(12332123,'-----------------')
//         }
//     },
//     mounted() {
//
//    }

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