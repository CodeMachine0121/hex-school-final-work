<script setup lang="ts">

import {ref} from "vue";

const isDisplay = ref(false);
const onclick = () => {
  isDisplay.value = !isDisplay.value;
}
</script>

<template>
  <div>
    <img @click="onclick" src="../images/menu.svg" alt="menu">
  </div>
</template>

<style scoped>
</style>