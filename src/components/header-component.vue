<script setup lang="ts">

import MenuList from "./menuList.vue";
</script>

<template>
<div class="header">
  <div class="title">
    <p>Header</p>
    <h1>Sub text</h1>
  </div>
  <div class="menu">
    <menu-list></menu-list>
  </div>
</div>
</template>

<style scoped>
.header{
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;

  .title{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 10px;
  }



}

</style>