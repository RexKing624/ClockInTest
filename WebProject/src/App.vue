<template>
<div class="Up">
    <clockPage msg="222"/>
</div>

<div class="Down">
    <clockPage msg="123"></clockPage>
</div>
</template>

<script setup>
import clockPage from './components/clockPage.vue'
</script>
<style scoped>
    .Up{
        color: red;
    }

</style>