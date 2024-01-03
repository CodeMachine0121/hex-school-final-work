<script setup lang="ts">

import HeroTitle from "./share/hero-title.vue";
import DecoLine from "./share/deco-line.vue";
</script>

<template>
  <div class="content">
    <hero-title class="hero-title" :title="'享樂酒店'" :sub-title="'Enjoyment Luxury Hotel'"/>
    <deco-line class="deco-line"/>
  </div>
</template>

<style scoped>
.content {
  .deco-line{
    margin-top: 20px;
  }

  width: 335px;
  height: 169px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 20px;
  align-self: stretch;
}
</style>