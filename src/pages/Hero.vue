<script setup lang="ts">

import SlideIndicators from "../components/share/slide-indicators.vue";
import NavBar from "../components/nav-bar.vue";
import HeroContent from "../components/hero-content.vue";
import DecoLine from "../components/share/deco-line.vue";
import HeroTitle from "../components/share/hero-title.vue";
</script>

<template>
  <div class="hero">
    <div class="shadow">
      <nav-bar/>
      <div class="hero-title">
        <hero-title  :title="'享樂酒店'" :sub-title="'Enjoyment Luxury Hotel'"/>
        <deco-line class="deco-line"/>
      </div>
      <hero-content/>
      <slide-indicators :length="5" :active-index="1"/>
    </div>
  </div>

</template>

<style scoped>
.hero{
  background: url("../images/back-view.png"), lightgray 50% / cover no-repeat;
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

.hero-title {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-bottom: 40px;

  .deco-line {
    margin-top: 20px;
  }
}
</style>