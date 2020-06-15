<template>
  <div class="service-section">
    <div class="service-info">
      <div class="title">
        <h2>匠心筑就智慧人居精品</h2>
        <div class="subtitle">CRAFTSMANSHIP CREATES QUALITY LIFE PRODUCTS</div>
      </div>
      <div class="description">
        <p>实地地产集团有限公司，2006年从广州出发，始于地产而不止于地产。14年来，实地一直致力于将人类科技的一切探索创新以人居业态为依托运用于生活中的方方面面，将科技与人文连接，重新构建人类对于自身与居住空间关系的认知。目前，实地集团已经发展成为一家为用户提供贯穿全生命周期智慧人居解决方案的综合性企业。</p>
        <p>实地集团现已覆盖全国六大最具成长力城市群，在29城全面绽放。每落子一地，均从区域先天资源的统筹观出发，开发每个城市的独特魅力，探索每个城市的人文价值，创造与之匹配的智能生活解决方案，为每座城市打造专属的人居经典。</p>
        <p>实地集团坚持用户至上原则，关注每一个个体的真实需求。从项目规划之初，就从用户痛点出发，以科技创新的产品思维先行，借助智能产品、数据分析、生活配套三位一体的服务体系，满足用户对居住环境安全、家庭健康、时间管理、情感交互等多维度的需求,以此为主线来逐步构建智慧人居生态系统，为用户打造美好生活体验的同时，引领行业发展方向，提升城市整体的人居品质。</p>
      </div>
    </div>
    <a href="" class="moreButton">
      <div class="left" style="pointer-events: none;">
          <div class="en">EXPLORE MORE</div>
          <div class="cn">了解更多</div>
      </div>
      <div class="right">
        <div class="about-rightarrow"></div>
        <div class="about-arrowtipup"></div>
      </div>
      <span id="aboutplus1">+</span><span id="aboutplus2">+</span><span id="aboutplus3">+</span><span id="aboutplus4">+</span>
    </a>
  </div>
</template>
<script>
export default {
  
}
</script>
<style lang="less">
.service-section{
  height: 100%;
  display: flex;
  flex-direction: column;
  padding: 0 13%;
  position: relative;
  overflow: hidden;
  background: rgba(0, 0, 0, 0.5);
  .service-info{
    color:#ffffff;
    .title{
      padding-top: 12%;
      h2{
        font-size: 40px;
      }
      .subtitle{
        font-size: 30px;
      }
    }
    .description{
      margin-top: 6%;
      width: 100%;
      font-size: 16px;
      max-height: 340px;
      p{
        margin-bottom: 20px;
      }
    }
  }
  .moreButton {
    width: 252px;
    height: 65px;
    border: 1px solid #ffffff;
    padding:8px 25px ;
    color:#ffffff;
    text-decoration: none;
    position: absolute;
    left: 43%;
    bottom: 20%;
    display: flex;
    .right{
      .about-rightarrow{
        border-bottom: 2px solid #fafafa;
        margin-top: 29px;
        position: absolute;
        width: 52px;
        right: 20px;
        top: 0;
      }
      .about-arrowtipup{
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
    #aboutplus1{
      position: absolute;
      top: -13px;
      left: -5px;
      font-size: 18px;
    }
    #aboutplus2{
      position: absolute;
      top: -13px;
      right: -5px;
      font-size: 18px;
    }
    #aboutplus3{
      position: absolute;
      bottom: -16px;
      left: -5px;
      font-size: 18px;
    }
    #aboutplus4{
      position: absolute;
      bottom: -16px;
      right: -5px;
      font-size: 18px;
    }
  }
  .moreButton:hover{
    background: hsla(0, 0%, 100%, .4);
    transition: all 0.6s cubic-bezier(0.215, 0.61, 0.355, 1) 0s;
  }
}
</style>