<template>
  <div class="contact-container">
    <div class="info">
      <div class="en-copyright">©2018 版权所有：广州实地房地产开发有限公司.</div>
      <div class="cn-copyright">ALL RIGHTS RESERVED: GUANGZHOU SEEDLAND REAL ESTATE DEVELOPMENT CO., LTD.</div>
      <div class="record"><a href="#">粤ICP备13058296号</a></div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="less" scoped>
.contact-container{
  height: 100%;
  box-shadow: inset 0 -300px 196px rgba(0,0,0,.721);
  position: relative;
  .company-info{
    position: absolute;
    bottom: 65px;
    left: 65px;
    color: #fff;
    .select-container{
      width: 350px;
      .select{
        display: block;
        width: 350px;
        height: 50px;
        margin: 15px 0;
        padding: 0 24px;
        font-size: 16px;
        line-height: 1.75;
        color: #fff;
        background-color: hsla(0,0%,100%,0);
        border: 1px solid #ccc;
        appearance: none;
        position: relative;
      }
    }
    .address{
      font-size: 16px;
      margin: 30px 0 20px;
    }
    .phone{
      font-size: 20px;
      margin-top: 50px;
    }
    .logo{
      margin-top: 70px;
      img{
        width: 270px;
      }
    }
  }
  .info{
    position: absolute;
    bottom: 30px;
    left: 37vw;
    text-align: center;
    color: #fff;
    font-size: 12px;
    .en-copyright{
      margin-bottom: 10px;
    }
    .record{
      margin-top: 10px;
      a{
        color: #fff;
        text-decoration: none;
      }
    }
  }
}  
</style>