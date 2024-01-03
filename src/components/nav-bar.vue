<script setup lang="ts">

import NavMenu from "./share/nav-menu.vue";
import Brand from "./share/brand.vue";
</script>

<template>
<div class="header">
  <brand/>
  <nav-menu/>
</div>
</template>

<style scoped>
.header{
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}

</style>