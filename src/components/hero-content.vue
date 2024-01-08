<script setup lang="ts">
</script>

<template>
  <div class="hero-bg">
    <div class="hero-heading">
      <div class="display">
        <p class="head">高雄</p>
        <p class="head">豪華住宿之選</p>
      </div>
      <p class="desc">
        我們致力於為您提供無與倫比的奢華體驗與優質服務
      </p>
    </div>

    <button class="hero-btn">立即訂房</button>
  </div>
</template>

<style scoped>

.hero-bg{
  display: flex;
  padding: 60px 20px 60px 20px;
  flex-direction: column;
  justify-content: center;

  border-radius: 40px;
  border-top: 1px solid #F5F7F9;
  border-right: 1px solid #F5F7F9;
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.00) 0%, rgba(255, 255, 255, 0.30) 100%);
  backdrop-filter: blur(10px);

  font-family: Noto, TC,serif;
  font-style: normal;
  font-weight: 700;
  align-self: stretch;
  .hero-heading{
    margin-bottom: 40px;

    .display{
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      gap: 8px;
      .head{
        color: #FFF;
        font-size: 48px;
        line-height: 120%; /* 57.6px */
        letter-spacing: 2px;
      }
      margin-bottom: 24px;
    }
    .desc{
      color: #ECECEC;
      font-size: 16px;
      line-height: 150%; /* 24px */
      letter-spacing: 0;
    }
  }

  .hero-btn{
    width: 100%;
    height: auto;
    display: flex;
    padding: 20px;
    flex-direction: column;
    align-items: center;
    gap: 10px;
    border-radius: 8px;
    background:  #FFF;
    color: #000;
    font-size: 16px;
    line-height: 150%; /* 24px */
    letter-spacing: 0;
  }
}
</style>