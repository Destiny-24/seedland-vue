<template>
  <div class="contact-container">
    <div class="footer">
      <div class="footer-list">
        <div class="footer-item">
          <div class="piece-info">
            <h2>关于实地</h2>
            <div class="infotag">
              <a href>集团介绍</a>
              <a href>实地愿景</a>
              <a href>实地荣誉</a>
              <a href>企业文化</a>
            </div>
          </div>
        </div>
        <div class="footer-item">
          <div class="piece-info">
            <h2>地产服务</h2>
            <div class="infotag">
              <a href>楼盘信息</a>
            </div>
          </div>
        </div>
        <div class="footer-item">
          <div class="piece-info">
            <h2>智慧人居</h2>
            <div class="infotag">
              <a href>全场智慧社区</a>
              <a href>只能产品</a>
              <a href>智慧人居生态系统</a>
            </div>
          </div>
        </div>
        <div class="footer-item">
          <div class="piece-info">
            <h2>新闻中心</h2>
            <div class="infotag">
              <a href>企业新闻</a>
              <a href>楼盘动态</a>
            </div>
          </div>
        </div>
        <div class="footer-item">
          <div class="piece-info">
            <h2>加入实地</h2>
            <div class="infotag">
              <a href>团队理念</a>
              <a href>实地生活</a>
              <a href>人才观</a>
              <a href>团队实力</a>
              <a href>员工活动</a>
            </div>
          </div>
        </div>
        <div class="footer-item">
          <div class="piece-info">
            <h2>联系我们</h2>
            <div class="infotag">
              <a href>廉洁举报</a>
              <a href>客服热线：400-0080-8080</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <img class="logo" src="../assets//image/logo.png" alt="">
    <div class="sub-info">
      <div class="en-copyright">©2018 版权所有：广州实地房地产开发有限公司.</div>
      <div
        class="cn-copyright"
      >ALL RIGHTS RESERVED: GUANGZHOU SEEDLAND REAL ESTATE DEVELOPMENT CO., LTD.</div>
      <div class="record">
        <a href="#">粤ICP备13058296号</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="less" scoped>
.contact-container {
  height: 100%;
  box-shadow: inset 0 500px 196px rgba(0, 0, 0, 0.621);
  position: relative;
  .footer {
    padding: 8%;
    .footer-list {
      .footer-item {
        float: left;
        width: 16.6%;
        h2 {
          letter-spacing: 1px;
          color: #ffffff;
          font-size: 20px;
          padding-bottom: 30px;
          border-bottom: 1px solid rgba(255, 255, 255, 0.1);
          margin-bottom: 30px;
          width: 100%;
        }
        .infotag{
          display: flex;
          flex-direction: column;
          a{
            font-weight: 300;
            color:rgba(255, 255, 255, 0.5);
            text-decoration: none;
            margin-bottom: 5px;
          }
        }
      }
    }
  }
  .logo{
    position: absolute;
    top:60%;
    right:41%;
    width: 350px;
  }
  .sub-info {
    position: absolute;
    bottom: 30px;
    left: 36%;
    text-align: center;
    color: #fff;
    font-size: 12px;
    .en-copyright {
      margin-bottom: 10px;
    }
    .record {
      margin-top: 10px;
      a {
        color: #fff;
        text-decoration: none;
      }
    }
  }
}
</style>