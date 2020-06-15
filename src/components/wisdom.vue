<template>
  <div class="wisdom-section">
    <img src="../assets/image/bg4.jpg" alt />
    <div class="info-container">
      <div class="title">
        <h2>领·智慧人居</h2>
        <h3>SMART LIVING</h3>
      </div>
      <div class="content">
        <p>以深邃洞察挺立时代潮头</p>
        <p>以登山越岭之势领人居新风潮</p>
      </div>
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
.wisdom-section {
  height: 100%;
  display: flex;
  position: relative;
  overflow: hidden;
  .info-container {
    position: absolute;
    top: 30%;
    left: 13%;

    .title {
      color: #ffffff;
      font-size: 40px;
      h2 {
        font-weight: 300;
      }
      h3 {
        font-size: 33px;
      }
    }
    .content {
      margin-top: 30px;
      color: #ffffff;
      font-weight: 300;
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
    left: 13%;
    bottom: 30%;
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