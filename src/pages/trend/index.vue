<template>
  <div class="trend">
    <div class="content">
      这里整个图表分析你最近吃的 Junk food
    </div>
    <div class="message">
      做大做强，再创辉煌
    </div>
  </div>
</template>

<script lang="js">
  export default {
    name: "trend"
  }
</script>

<style lang="scss" scoped>
.trend {
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-self: center;
  justify-content: space-around;
  .content {
    text-align: center;
  }
  .message {
    text-align: center;
  }
}
</style>
