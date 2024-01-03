<script setup lang="ts">

import BrandComponent from "./brandComponent.vue";
import NavMenu from "./nav-menu.vue";
</script>

<template>
<div class="header">
  <brand-component/>
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