<!--
 * @Author: Royal
 * @LastEditTime: 2022-07-14 15:12:43
 * @Description: 
-->
<template>
    <div class="outer">
        <button @click="test()">Test</button>
        <div class="testdiv">TEST</div>
    </div>
</template>
<script lang="ts" setup>
import { ref } from "vue";
import { system } from "../systeminit";
function test(){
    // console.log('test') 
    system.Notify.notify('test',"testtest")
}
</script>
<style>

</style>
<style scoped>
.testdiv{
    position: fixed;
    bottom: 0;
    right: 0i
}
</style>