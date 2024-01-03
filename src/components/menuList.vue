<script setup lang="ts">
</script>

<template>
  <label for="burger">☰</label>
  <input type="checkbox" id="burger"/>
  <ul>
    <li>客房旅宿</li>
    <li>
      James
    </li>
  </ul>
</template>

<style scoped>
ul{
  display: none;
}

input{
  display: none;
}

label{
  display: block;
}
#burger:checked + ul{
  display: block;
}
</style>