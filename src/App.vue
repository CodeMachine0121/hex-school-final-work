<script setup lang="ts">
import NavBar from "./components/nav-bar.vue";
import HeroContent from "./components/hero-content.vue";
import SlideIndicators from "./components/share/slide-indicators.vue";
</script>

<template id="app">
  <div class="shadow">
    <nav-bar/>
    <hero-content/>
    <slide-indicators :length="5" :active-index="1"/>
  </div>

</template>


<style lang="scss">
@import "scss/reset";
#app{
  background: url("../src/images/back-view.png"), lightgray 50% / cover no-repeat;
  padding: 0;
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
