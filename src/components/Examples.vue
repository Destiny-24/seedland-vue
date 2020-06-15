<template>
  <div class="Examples-section">
    <div class="Examples-list">
      <a href="/" class="estate-item">
        <img src="../assets/image/estate1.jpg" alt />
        <div class="setateCont">
          <h2>- 01</h2>
          <h3>紫薇公馆·广州</h3>
        </div>
      </a>
      <a href="/" class="estate-item">
        <img src="../assets/image/estate2.jpg" alt />
        <div class="setateCont">
          <h2>- 02</h2>
          <h3>紫薇公馆·安阳</h3>
        </div>
      </a>
      <a href="/" class="estate-item">
        <img src="../assets/image/estate3.jpg" alt />
        <div class="setateCont">
          <h2>- 03</h2>
          <h3>蔷薇国际·重庆</h3>
          <p>ROSE INTERNATIONAL</p>
        </div>
      </a>
      <a href="/" class="estate-item">
        <img src="../assets/image/estate4.jpg" alt />
        <div class="setateCont">
          <h2>- 04</h2>
          <h3>常春藤·广州</h3>
          <p>BOSTON LVY</p>
        </div>
      </a>
    </div>
    <a href class="moreButton">
      <div class="left" style="pointer-events: none;">
        <div class="en">EXPLORE MORE</div>
        <div class="cn">了解更多</div>
      </div>
      <div class="right">
        <div class="about-rightarrow"></div>
        <div class="about-arrowtipup"></div>
      </div>
      <span id="aboutplus1">+</span>
      <span id="aboutplus2">+</span>
      <span id="aboutplus3">+</span>
      <span id="aboutplus4">+</span>
    </a>
  </div>
</template>>
<script>
export default {};
</script>
<style lang="less">
.Examples-section {
  display: flex;
  overflow: hidden;
  height: 100%;
  position: relative;
  .Examples-list {
    display: flex;
    height: 100%;
    background: rgba(0, 0, 0, 0.98);
    .estate-item {
      position: relative;
      height: 100%;
      overflow: hidden;
      img {
        width: 100%;
        height: 100%;
        z-index: 1;
        opacity: 0.8;
      }
      img:hover {
        opacity: 1;
        transform: scale(1.1);
        transition: all 0.3s ease-out;
      }
      .setateCont {
        position: absolute;
        top: 15%;
        left: 15%;
        color: #ffffff;
        letter-spacing: 1px;
        h3 {
          font-weight: 300;
          font-size: 40px;
        }
        p {
          font-size: 30px;
        }
      }
    }
  }
  .moreButton {
    width: 252px;
    height: 65px;
    border: 1px solid #ffffff;
    padding: 8px 25px;
    color: #ffffff;
    text-decoration: none;
    position: absolute;
    left: 43.5%;
    bottom: 9%;
    display: flex;
    .right {
      .about-rightarrow {
        border-bottom: 2px solid #fafafa;
        margin-top: 29px;
        position: absolute;
        width: 52px;
        right: 20px;
        top: 0;
      }
      .about-arrowtipup {
        border-bottom: 2px solid #fafafa;
        margin-top: 1px;
        position: absolute;
        width: 12px;
        -webkit-transform: rotate(32deg);
        transform: rotate(32deg);
        -webkit-transform-origin: bottom right;
        transform-origin: bottom right;
        right: 20px;
        top: 28px;
      }
    }
    #aboutplus1 {
      position: absolute;
      top: -13px;
      left: -5px;
      font-size: 18px;
    }
    #aboutplus2 {
      position: absolute;
      top: -13px;
      right: -5px;
      font-size: 18px;
    }
    #aboutplus3 {
      position: absolute;
      bottom: -16px;
      left: -5px;
      font-size: 18px;
    }
    #aboutplus4 {
      position: absolute;
      bottom: -16px;
      right: -5px;
      font-size: 18px;
    }
  }
  .moreButton:hover {
    background: hsla(0, 0%, 100%, 0.4);
    transition: all 0.6s cubic-bezier(0.215, 0.61, 0.355, 1) 0s;
  }
}
</style>