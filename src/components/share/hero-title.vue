<script setup lang="ts">

const props = defineProps({
  title: String,
  subTitle: String
});
</script>

<template>
<div class="title">
  <p class="main-title">{{props.title}}</p>
  <p class="sub-title">{{props.subTitle}}</p>
</div>
</template>

<style scoped>
.title{
  color: #BE9C7C;
  text-align: center;
  font-family: Noto,TC,serif;
  font-style: normal;
  font-weight: 700;

  .main-title{
    font-size: 28px;
    line-height: 120%; /* 33.6px */
    letter-spacing: 1px;
    margin-bottom: 8px;
  }
  .sub-title {
    font-size: 16px;
    line-height: 150%; /* 24px */
    letter-spacing: 0;
  }
}
</style>