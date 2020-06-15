<template>
  <div id="app">
    <div class="video">
      <video muted class="bg-video" src="../assets/video.mp4" autoplay loop></video>
    </div>
    <div class="sidenav">
      <img src="../assets/image/hamburger.png" alt="" >
    </div>
    <full-page
      class="fullpage-container"
      ref="fullpage"
      :options="options"
      id="fullpage"
    >
    <div class="section login" ><login /></div>
    <div class="section service" ><service /></div>
    <div class="section Examples" ><Examples /></div>
    <div class="section wisdom" ><wisdom /></div>
    <div class="section course" ><course /></div>
    <div class="section contact" ><contact /></div>
    </full-page>
  </div>
</template>

<script>
import login from "./login";
import service from "./service";
import Examples from "./Examples";
import wisdom from "./wisdom";
import course from "./course";
import contact from "./contact";
export default {
  data(){
    return{
        options: {
        licenseKey: "4F375E3E-7D814D7F-B82954BA-31DC667F",
        menu: "#menu",
        anchors: [
          "login",
          "service",
          "Examples",
          "wisdom",
          "course", 
          "contact"
        ]
      },
    }
  },
  components:{
    login,
    service,
    Examples,
    wisdom,
    course,
    contact,
  }
}
</script>

<style lang="less">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app,body,html{
  width: 100%;
  height: 100%;
  position: relative;
}
.video{
  .bg-video{
    width: 100%;
    height: 100%;
    overflow: hidden;
    position: fixed;
    top: 0;
    left: 0;
    z-index: -100;
    object-fit: cover;
  }
}
.sidenav{
  position: absolute;
  right: 46px;
  top: 47px;
  z-index: 1000;
  img{
    margin-left: 16px;
    width: 28px;
    height: 16px;
  }
}
</style>
