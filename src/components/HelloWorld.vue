<template>
  <div class="index-wrap">
    <div class="header">顶部导航</div>
    <div class="main"></div>
    <div class="footer">底部导航</div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}

</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.index-wrap {
  width: 100%;
  height: 100%;
  overflow: hidden;
  position: relative;
  .header {
    position: absolute;
    left: 0;
    top: 0;
    height: 0.63rem;
    background: #FE5400;
    font-size: 0.2rem;
    width: 6.4rem;
    text-align: center;
    line-height: 0.63rem;
  }
  .footer {
    position: absolute;
    width: 6.4rem;
    left: 0;
    bottom: 0;
    height: 0.63rem;
    background: #FE5400;
    font-size: 0.2rem;
    text-align: center;
    line-height: 0.63rem;
  }
  .main {
    width: 6.4rem;
    height: 20rem;
    font-size: 0.2rem;
    padding: 0.63rem 0; // overflow: auto;
  }
  .main {
    position: absolute;
    left: 0;
    right: 0;
    top: 0.63rem;
    bottom: 0.63rem; // width: 6.4rem;
    // height: 20rem;
    font-size: 0.2rem; // padding: 0.63rem 0;
    overflow: auto;
  }
}

</style>
