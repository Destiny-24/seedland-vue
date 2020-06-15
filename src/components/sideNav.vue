<template>
  <div class="side-nav" >
    <div class="nav-container">
      <img src="@/assets/image/close.png" >
      <div class="nav-list">
        <a class="nav-item" href="#login" >
          01
          <div class="item-text">
            <div class="cn-text">主页</div>
            <div class="en-text">HOME</div>
          </div>
        </a>
        <a class="nav-item" href="#service" >
          02
          <div class="item-text">
            <div class="cn-text">地产服务</div>
            <div class="en-text">Real estate services</div>
          </div>
        </a>
        <a class="nav-item" href="#Examples" >
          03
          <div class="item-text">
            <div class="cn-text">精品房产</div>
            <div class="en-text">Boutique property</div>
          </div>
        </a>
        <a class="nav-item" href="#wisdom" >
          04
          <div class="item-text">
            <div class="cn-text">智慧人居</div>
            <div class="en-text">Smart Habitat</div>
          </div>
        </a>
        <a class="nav-item" href="#course" >
          05
          <div class="item-text">
            <div class="cn-text">新闻中心</div>
            <div class="en-text">NEWS</div>
          </div>
        </a>
        <a class="nav-item" href="#contact" >
          06
          <div class="item-text">
            <div class="cn-text">联系我们</div>
            <div class="en-text">CONTACT</div>
          </div>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="less" scoped>
.side-nav{
  width: 400px;
  height: 100%;
  position: absolute;
  right: 0;
  top: 0;
  background: rgba(0,0,0,.55);
  z-index: 99;
  animation: slideright 1s both;
  @keyframes slideright {
    0% {
      transform: translate3d(100%, 0, 0);
      visibility: visible;
    }
    100% {
      transform: translate3d(0, 0, 0);
    }
  }
  .nav-container{
    width: 300px;
    position: absolute;
    right: 0;
    top: 0;
    img{
        width: 34px;
        margin: 40px 48px 0 0;
        cursor: pointer;
        float: right;
    }
    .nav-list{
      position: absolute;
      top: 100px;
      .nav-item{
        text-decoration: none;
        color: #fff;
        font-size: 16px;
        margin: 25px 0;
        display: flex;
        align-items: center;
        .item-text{
          font-size: 14px;
          font-weight: 100;
          line-height: 1.5;
          border-left: 1px solid hsla(0,0%,100%,.41);
          flex-direction: column;
          margin-left: 10px;
          padding: 5px 0 5px 15px;
          display: flex;
          .en-text{
            font-size: 8px;
          }
        }
      }
    }
  }
}
</style>
