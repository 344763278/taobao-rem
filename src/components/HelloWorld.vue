<template>
  <div class="index-wrap">
    <div class="header">
      <span class="logo"></span>
      <div class="search">iphoneX</div>
    </div>
    <div class="main">
      <div class="c">
        <div class="banner">
          <img src="../assets/img/banner1.png" alt="">
        </div>
        <ul class="nav-box">
          <li class="item">
            <img src="../assets/img/nav1.png" alt="">
            <p>天貓</p>
          </li> 
          <li class="item">
            <img src="../assets/img/nav1.png" alt="">
            <p>天貓</p>
          </li>
          <li class="item">
            <img src="../assets/img/nav1.png" alt="">
            <p>天貓</p>
          </li>
          <li class="item">
            <img src="../assets/img/nav1.png" alt="">
            <p>天貓</p>
          </li>
          <li class="item">
            <img src="../assets/img/nav1.png" alt="">
            <p>天貓</p>
          </li>
          <li class="item">
            <img src="../assets/img/nav1.png" alt="">
            <p>天貓</p>
          </li>
          <li class="item">
            <img src="../assets/img/nav1.png" alt="">
            <p>天貓</p>
          </li>
          <li class="item">
            <img src="../assets/img/nav1.png" alt="">
            <p>天貓</p>
          </li>
          <li class="item">
            <img src="../assets/img/nav1.png" alt="">
            <p>天貓</p>
          </li>
          <li class="item">
            <img src="../assets/img/nav1.png" alt="">
            <p>天貓</p>
          </li>
        </ul>
        <div class="info">
          <img src="../assets/img/info.png" alt="">
        </div>
        <div class="ad-box">
          <div class="ad1">
            <img src="../assets/img/ad1.png" alt="">
          </div>
          <div class="ad2">
            <img src="../assets/img/ad2.png" alt="">
          </div>
          <div class="ad3">
            <img src="../assets/img/ad3.png" alt="">
          </div>
          <div class="ad4">
            <img src="../assets/img/ad3.png" alt="">
          </div>
        </div>
      </div>
    </div>
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
  margin: 0 auto;
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
    .logo {
      width: 0.46rem;
      height: 0.34rem;
      background: url('../assets/img/top-logo.png') no-repeat 0 0;
      background-size: 0.46rem 0.34rem;
      display: block;
      margin-top: 0.13rem;
      margin-left: 0.10rem;
    }
    .search {
      position: absolute;
      width: 5.65rem;
      height: 0.43rem;
      left: 0.63rem;
      top: 0.1rem;
      background: #B52600;
      border-radius: 0.06rem;
      line-height: 0.43rem;
      font-size: 0.2rem;
      text-align: center;
      color: #fff;
    }
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
    position: absolute;
    width: 6.4rem;
    top: 0.63rem;
    bottom: 0.63rem;
    font-size: 0.2rem;
    box-sizing: border-box;
    overflow-x: hidden;
    overflow-y: auto;
    &::-webkit-scrollbar {
      display: none;
    }
    .c {
      .banner {
        width: 6.4rem;
        height: 2rem;
        img {
          display: block;
          width: 100%;
          height: 100%;
        }
      }
      .nav-box {
        overflow: hidden;
        padding-left: 0.22rem;
        padding-bottom: 0.22rem;
        border-bottom: 1px solid #EBEBEB;
        .item {
          width: 1.19rem;
          height: 1.16rem;
          float: left; 
          padding-top: 0.2rem; 
          text-align: center;
          img {
            width: 0.73rem;
            height: 0.73rem;
            display: block;
            margin: 0 auto;
          }
          P {
            height: 0.43rem;
            line-height: 0.43rem;
            font-size: 0.18rem;
            color: #AEAEAE;

          }
        }
      }
      .info {
        width: 100%;
        height: 0.59rem;
        img {
          width: 6.4rem;
          height: 0.59rem;
        }
        border-bottom: 0.1rem solid #EBEBEB;
      }
      .ad-box {
        overflow: hidden;
        border-bottom: 0.02rem solid #EBEBEB;
        .ad1 {
          width: 2.43rem;
          height: 3.22rem;
          float: left;
          border-right: 0.02rem solid #EBEBEB;
          img {
            display: block!important;
            width: 100%;
            height: 100%;
            // width: 2.43rem;
            // height: 3.22rem;
          }
        }
        .ad2 {
          width: 3.95rem;
          height: 1.47rem;
          float: left;
          border-bottom: 0.02rem solid #EBEBEB;
          img {
            display: block;
            width: 100%;
            height: 100%;
          }
        }
        .ad3, .ad4 {
          width: 1.94rem;
          height: 1.73rem;
          float: left;
          img {
            display: block;
            width: 100%;
            height: 100%;
          }
        }
        .ad3 {
          border-right: 0.02rem solid #EBEBEB;
        }
      }
    }
  }
}

</style>
