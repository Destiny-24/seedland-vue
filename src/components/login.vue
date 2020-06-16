<template>
  <div class="login-section">
    <div class="header">
      <div class="logo">
        <img class="header-logo" src="../assets/image/logo.png" alt />
      </div>
      <div class="nav">
        <div class="nav_ul">
          <ul class="menu-container">
            <li class="menu-item">
              <a href="#login">关于实地</a>
            </li>
            <li class="menu-item">
              <a href="#service">地产服务</a>
            </li>
            <li class="menu-item">
              <a href="#Examples">精品房产</a>
            </li>
            <li class="menu-item">
              <a href="#wisdom">智慧人居</a>
            </li>
            <li class="menu-item">
              <a href="#course">新闻中心</a>
            </li>
          </ul>
        </div>
        <div class="global">
          <a href="/en">EN/</a>
          <a href="/">CN</a>
        </div>
      </div>
    </div>
    <div class="main-init">
      <div class="main-title">THE FUTURE</div>
      <div class="main-title">IS HERE</div>
      <div class="main-subtitle">
        未来
        <span>•</span> 就在眼前
      </div>
    </div>
    <img class="main-bg" src="../assets/image/bg1.png" alt />
  </div>
</template>
<script>
export default {};
</script>
<style lang="less">
.login-section {
  overflow: hidden;
  .header {
    width: 100%;
    height: 106px;
    border-bottom: 2px solid rgba(255, 255, 255, 0.8);
    display: flex;
    position: relative;
    .logo {
      margin-top: 45px;
      padding-left: 4%;
      .header-logo {
        object-fit: contain;
      }
    }
    .nav {
      width: 100%;
      display: flex;
      position: relative;
      .nav_ul {
        width: 100%;
        height: 100%;
        .menu-container {
          display: flex;
          list-style: none;
          padding-top: 42px;
          justify-content: flex-end;
          .menu-item {
            width: 77px;
            margin-left: 68px;
            a {
              text-decoration: none;
              font-size: 18px;
              color: #ffffff;
            }
          }
        }
      }
      .global {
        padding: 45px 135px 0 40px;
        a {
          text-decoration: none;
          color: #050c1f;
          font-size: 18px;
        }
      }
    }
  }
  .main-init {
    font-size: 50px;
    color: #ffffff;
    position: absolute;
    left: 51%;
    top: 222px;
    .main-subtitle {
      font-size: 35px;
      span {
        font-size: 20px;
      }
    }
  }
  .main-bg {
    width: 100%;
    position: absolute;
    top: 106px;
    left: 0;
  }
}
</style>