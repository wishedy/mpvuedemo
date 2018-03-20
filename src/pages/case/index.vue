<template>
  <div class="container">
    测试模块
  </div>
</template>
<script>
  export default {
    mounted: function () {
      console.log("加载完成")
    }
  }
</script>
<style lang="scss">
  .container {
    height: 300px;
    width: 535px;
    background: #ff0000;
  }
</style>
