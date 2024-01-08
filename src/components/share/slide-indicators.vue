<script setup lang="ts">
import {onMounted} from "vue";

const props = defineProps({
  activeIndex: {
    type: Number,
  },
  length: {
    type: Number,
  }
});

onMounted(() => {
  console.log(props.activeIndex);
  console.log(props.length);
});
</script>

<template>

  <div class="slides">
    <div v-for="index in length" :key="index" :class="index === activeIndex ? 'selected' : 'non-selected'"></div>
  </div>
</template>

<style scoped>
  .slides{
    display: inline-flex;
    height: 4px;
    align-items: flex-start;
    gap: 8px;
    flex-shrink: 0;

    .selected{
      background: #BE9C7C;
      width: 60px;
      height: 4px;
    }

    .non-selected{
      width: 32px;
      height: 4px;
      border-radius: 100px;
      background:  #F1EAE4;
    }
  }

</style>