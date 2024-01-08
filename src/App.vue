<script setup lang="ts">
import NavBar from "./components/nav-bar.vue";
import HeroContent from "./components/hero-content.vue";
</script>

<template id="app">
  <div class="shadow">
    <nav-bar/>
    <hero-content/>
  </div>
</template>


<style lang="scss">
@import "scss/reset";
#app{
  background: url("../src/images/back-view.png"), lightgray 50% / cover no-repeat;
  padding: 0px;
  width: 100%;
  height: 100vh;
}
.shadow{
  width: 100%;
  height: 100vh;
  flex-shrink: 0;
  background: rgba(0, 0, 0, 0.60);
}
</style>
