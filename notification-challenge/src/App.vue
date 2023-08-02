<script setup>
import Button from "./components/button.vue"
</script>

<template>
 <div class="floor">
  <Button></Button>
  <Notification></Notification>
 </div>
 
<style scoped>
  .floor{  
    position: absolute;
    width: 700px;
    height: 175px;

    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: #fff;
    
  }
</style>
