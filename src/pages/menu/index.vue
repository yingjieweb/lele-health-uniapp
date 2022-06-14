<template>
  <div class="menu">
    <div class="content">
      这里准备整个菜单
    </div>
    <div class="message">
      做大做强，再创辉煌
    </div>
  </div>
</template>

<script lang="js">
  export default {
    name: "menu"
  }
</script>

<style lang="scss" scoped>
.menu {
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
