<template>
  <div class="course-sectopm">
    <div class="container">
      <div class="intellect">
        <img class="intellectImg" src="../assets/image/courseimg.jpg" alt />
        <a href class="intellectTit">
          <h2>2020-06-10</h2>
          <p>看好“万亿金矿”社区商业 实地集团加快布局</p>
          <a href class="moreButton">
            <div class="en">EXPLORE</div>
            <span id="aboutplus1">+</span>
            <span id="aboutplus2">+</span>
            <span id="aboutplus3">+</span>
            <span id="aboutplus4">+</span>
          </a>
        </a>
      </div>
      <div class="course-list">
        <a href class="course-item-active">
          <h2>2020-06-05</h2>
          <p>两会代表建言智慧社区建设 实地集团加快智慧人居布局</p>
          <a href class="moreButton">
            <div class="en">EXPLORE</div>
            <span id="aboutplus1">+</span>
            <span id="aboutplus2">+</span>
            <span id="aboutplus3">+</span>
            <span id="aboutplus4">+</span>
          </a>
        </a>
        <a href class="course-item">
          <h2>2020-05-28</h2>
          <p>满意度每年增长10% 实地集团精细化物业服务获认可</p>
          <a href class="moreButton">
            <div class="en">EXPLORE</div>
            <span id="aboutplus1">+</span>
            <span id="aboutplus2">+</span>
            <span id="aboutplus3">+</span>
            <span id="aboutplus4">+</span>
          </a>
        </a>
        <a href class="course-item">
          <h2>2020-05-22</h2>
          <p>实地集团：乘数字经济浪潮 赋能湾区智慧城市建设</p>
          <a href class="moreButton">
            <div class="en">EXPLORE</div>
            <span id="aboutplus1">+</span>
            <span id="aboutplus2">+</span>
            <span id="aboutplus3">+</span>
            <span id="aboutplus4">+</span>
          </a>
        </a>
        <a href class="course-item">
          <h2>2020-05-15</h2>
          <p>“新基建”关键环节：实地集团智慧社区的有益实践</p>
          <a href class="moreButton">
            <div class="en">EXPLORE</div>
            <span id="aboutplus1">+</span>
            <span id="aboutplus2">+</span>
            <span id="aboutplus3">+</span>
            <span id="aboutplus4">+</span>
          </a>
        </a>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="less">
.course-sectopm {
  width: 100%;
  height: 100%;
  background: url("../assets/image/bg5.jpg");
  overflow: hidden;
  .container {
    padding-top: 10%;
    margin: 0 13%;
    .intellect {
      display: flex;
      .intellectImg {
        border-radius: 80px 0 0 0;
      }
      .intellectTit {
        margin-left: 30px;
        border: 1px solid #ffffff;
        border-radius: 0 0 80px 0;
        padding: 40px 70px 40px 50px;
        text-decoration: none;
        color: #ffffff;
        position: relative;
        h2 {
          font-size: 16px;
        }
        p {
          font-size: 19px;
          line-height: 28px;
          margin-top: 10%;
          margin-bottom: 15px;
          letter-spacing: 3px;
          font-weight: 300;
        }
        .moreButton {
          border: 1px solid #ffffff;
          padding: 4px 8px 1px 8px;
          color: #ffffff;
          text-decoration: none;
          position: absolute;
          left: 15%;
          bottom: 34%;
          display: flex;
          letter-spacing: 2px;
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
    }
    .course-list {
      display: flex;
      margin-top: 4%;
      .course-item-active {
        font-size: 12px;
        color: #ffffff;
        font-weight: 300;
        text-decoration: none;
        padding-right: 20px;
        p {
          margin-top: 20px;
          font-size: 18px;
          max-width: 85%;
        }
        .moreButton {
          width: 112px;
          border: 1px solid #ffffff;
          padding: 4px 8px 1px 8px;
          color: #ffffff;
          text-decoration: none;
          top: 80px;
          display: flex;
          letter-spacing: 2px;
          position: relative;
          justify-content: center;
          #aboutplus1 {
            position: absolute;
            top: -13px;
            left: -5px;
            font-size: 18px;
          }
          #aboutplus2 {
            position: absolute;
            top: -13px;
            right: -7px;
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
            right: -7px;
            font-size: 18px;
          }
        }
        .moreButton:hover {
          background: hsla(0, 0%, 100%, 0.4);
          transition: all 0.6s cubic-bezier(0.215, 0.61, 0.355, 1) 0s;
        }
      }
      .course-item {
        font-size: 12px;
        color: #ffffff;
        font-weight: 300;
        text-decoration: none;
        padding-left: 20px;
        p {
          margin-top: 20px;
          font-size: 18px;
          max-width: 85%;
        }
        .moreButton {
          width: 112px;
          border: 1px solid #ffffff;
          padding: 4px 8px 1px 8px;
          color: #ffffff;
          text-decoration: none;
          top: 80px;
          display: flex;
          letter-spacing: 2px;
          position: relative;
          justify-content: center;
          #aboutplus1 {
            position: absolute;
            top: -13px;
            left: -5px;
            font-size: 18px;
          }
          #aboutplus2 {
            position: absolute;
            top: -13px;
            right: -7px;
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
            right: -7px;
            font-size: 18px;
          }
        }
        .moreButton:hover {
          background: hsla(0, 0%, 100%, 0.4);
          transition: all 0.6s cubic-bezier(0.215, 0.61, 0.355, 1) 0s;
        }
      }
    }
  }
}
</style>