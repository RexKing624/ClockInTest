<template>
<div class="Up">
    <clockPage btuName="test" @click="sumit"/>
</div>

<div class="Down">
    <clockPage btuName="123"></clockPage>
</div>
</template>

<script setup>
import clockPage from './components/clockPage.vue'
</script>
<style scoped>
    .Up{
        color: red;
            /*background-color: red;*/
            color: red;
            /*margin-left: 10px;*/
    }

</style>