<script setup lang="ts">
import NavBar from "./components/nav-bar.vue";
import HeroContent from "./components/hero-content.vue";
</script>

<template id="app">
  <nav-bar/>
  <hero-content/>
</template>


<style lang="scss">
@import "scss/reset";
#app{
  //background: url("./images/back-view.png") no-repeat center center fixed;
  width: 100%;
  height: 100vh;
}
</style>
