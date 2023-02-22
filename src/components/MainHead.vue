<template>
  <div id="head">
    <el-row type="flex" :style="bgColor">

      <!-- logo部分 -->
      <el-col class="home" :span="4">
        <a href="#">
          <!-- <el-image
            style="width:60px; height:60px; "
            :src="require('@/assets/img/head/logo.svg')"
            fit="fit">
          </el-image> -->
          <svg id="logo_svg" data-name="logo_svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60">
            <defs>
            <!-- <style>.cls-1{fill:#e1645f;}.cls-2{fill:#fff;}</style> -->
            </defs>
            <rect class="cls-1" :style="svg1Style" width="60" height="60"/>
          <path class="cls-2" :style="svg2Style" d="M54,19.37A.61.61,0,0,0,54.2,19a.55.55,0,0,0-.07-.29c-.08-.14-.21-.23-1-.51l-.42-.15c-.19-.06-.37-.11-.56-.15a4.13,4.13,0,0,0-.7,0,9.56,9.56,0,0,0-1,.08,1.63,1.63,0,0,0-.35.07,1.7,1.7,0,0,0-.63.44l-.77.8c-.89,1.17-6,7-6.08,7.09h0l-.06.07a.39.39,0,0,1-.28.07l-.14-.07-.28-.22s-.06,0-.07-.08a.28.28,0,0,1,0-.22.56.56,0,0,1,.07-.14,2.43,2.43,0,0,1,.14-.22C49.39,16.94,52.69,13.12,52.87,13a.5.5,0,0,0,.14-.15.43.43,0,0,0,0-.44,1.24,1.24,0,0,0-.21-.14l-.14-.08a7.06,7.06,0,0,0-1.61-.58,3.29,3.29,0,0,0-2.17,0,3.28,3.28,0,0,0-1.33,1.17c0,.05-.37.45-1,1.24-1.21,1.43-4.66,5.4-7.62,8.84h0a.42.42,0,0,1-.21.15.34.34,0,0,1-.21,0c-.09,0-.09-.07-.35-.29a.53.53,0,0,1-.21-.29v-.08c0-.1.09-.16.28-.36l.14-.15,11-12.71a.44.44,0,0,0,0-.3.31.31,0,0,0-.14-.14,4.62,4.62,0,0,0-1.68-.59,3.76,3.76,0,0,0-2,.08,3.25,3.25,0,0,0-1,.58h0l-.07.07s-8,8.94-8.82,10.09a.65.65,0,0,1-.42.29.57.57,0,0,1-.41-.15L34.62,19c-.2-.21-.29-.32-.28-.44a.17.17,0,0,1,.07-.14c1.75-2,2-2.2,2-2.2s.73-.82,2.1-2.41c2.52-2.9,2.17-2.56,2.52-2.92.94-1,1.66-2.16,2.66-3.07.13-.13.48-.44.42-.73s-.79-.52-1.47-.66a5.45,5.45,0,0,0-1.75-.07,2.82,2.82,0,0,0-1.05.29,4,4,0,0,0-.77.59A8.37,8.37,0,0,0,38,8.33c-.48.57-1,1.11-1.47,1.68-1.06,1.28-.77.8-4.33,5-.19.22-1.23,1.47-2.66,3.07-.82.93-1.24,1.4-1.47,1.61-1.12,1-2.6,2.45-4.54,2.41a5.08,5.08,0,0,1-2.24-.65,11.35,11.35,0,0,1-2.8-2.12,23.25,23.25,0,0,0-2-1.9,6.33,6.33,0,0,0-2.51-1.32,5,5,0,0,0-3,.22A5.14,5.14,0,0,0,8.81,18c-.74.95-1.49,2.59-1,3.21.28.34.61,0,1.82.37a5.19,5.19,0,0,1,1.68.88c.21.16.35.31.42.36a6.23,6.23,0,0,1,1.05,1.46,16.2,16.2,0,0,1,1,3.95,23.34,23.34,0,0,0,1,4.53A15.73,15.73,0,0,0,17.13,37h0a14.73,14.73,0,0,0,2.38,2.56,28.64,28.64,0,0,0,3,2.34,32,32,0,0,0,4.33,2.41h0l.33.13c.33.16.37.21.72.38a1.56,1.56,0,0,1,.42.22,1.23,1.23,0,0,1,.28.29c-1.12,1.36-6,7.26-6.22,7.24a.6.6,0,0,1-.21-.08.46.46,0,0,1-.14-.14,2.23,2.23,0,0,0-.28-.3c-.33-.34-8.46-10.1-13.15-15.27-1.2-1.32-2.66-2.88-4.54-5.33A20.37,20.37,0,0,1,1.12,27a13.76,13.76,0,0,1-.91-7.75,13.85,13.85,0,0,1,1.68-4.46,13.11,13.11,0,0,1,4.47-4.6,11.92,11.92,0,0,1,6.58-1.68,13.45,13.45,0,0,1,6.36,2.19c1.42,1,2,1.46,2,1.46,1.34,1.18,1.69,1.93,2.45,2s1.61-.88,1.88-1.24c2-2.52,4.2-4.77,6.23-7.23A16.64,16.64,0,0,1,42,.15,15.89,15.89,0,0,1,52.52,2.63a17.06,17.06,0,0,1,6.71,9.21,18.2,18.2,0,0,1-.07,10.6A17.82,17.82,0,0,1,56.29,28c-6.92,8.08-27,31.49-27.34,31.86a.42.42,0,0,1-.28.15c-.2,0-.34-.24-.42-.37-.23-.35-.58-.61-.84-1-.62-.84-3-3.42-3.28-3.87a.34.34,0,0,1-.07-.22.42.42,0,0,1,.14-.29C41.89,33.49,53.74,19.58,54,19.37Z"/></svg>
          <div class="text" :style="textColor">
            <div class="t1">校园</div>
            <div class="t2">
              <div>志愿</div>
              <div>服务网</div>
            </div>
          </div>
        </a>
      </el-col>

      <!-- 导航栏部分 -->
      <el-col class="navbar" :span="12">
        <a :style="textColor" href="#">首页</a>
        <a :style="textColor" href="#">志愿项目</a>
        <a :style="textColor" href="#">志愿之星</a>
        <a :style="textColor" href="#">文明倡议</a>
        <a :style="textColor" href="#">VR校园</a>
      </el-col>

      <!-- 登录注册 -->
      <el-col class="login" :span="4" :xs="24" :offset="4">
        <div>
          <el-avatar class="loginarea loginimg" src="https://cube.elemecdn.com/0/88/03b0d39583f48206768a7534e55bcpng.png"></el-avatar>
          <div class="card">
            <el-button type="primary" icon="el-icon-user">登录/注册</el-button>
            <el-button type="primary" icon="el-icon-user">个人中心</el-button>
            <el-button type="danger">退出登录</el-button>
          </div>
        </div>
      </el-col>
    </el-row>
    <!-- 进度条 -->
    <el-row><div class="progress" :style="progressWidth"></div></el-row>
  </div>
</template>

<script>
export default {
  name: "MainHead",
  data() {
    return {
      // css
      progressWidth:{width:0},
      bgColor:{
        backgroundColor: '#E1645F',
        transition: '.3s'
      },
      textColor:{
        color: '#fff',
        transition: '.3s'
      },
      svg1Style:{
        fill:'#e1645f',
        transition: '.3s'
      },
      svg2Style:{
        fill:'#fff',
        transition: '.3s'
      },


      isLogin:false
    }
  },
  mounted(){
    window.onscroll = ()=>{
      this.progressWidth = {width: this.progressValue()+'%'}


      if(this.progressValue() == 0){
        this.bgColor.backgroundColor = '#E1645F'
        this.textColor.color = '#fff'
        this.svg1Style.fill = '#e1645f'
        this.svg2Style.fill = '#fff'
      }else{
        this.bgColor.backgroundColor = '#FDF6F5'
        this.textColor.color = '#B94844'
        this.svg1Style.fill = '#FDF6F5'
        this.svg2Style.fill = '#B94844'
      }
    }
  },
  methods:{
    progressValue(){
      return window.scrollY/(document.body.scrollHeight - window.innerHeight) * 100
    }
  }
}
</script>

<style scoped>
#head{
  z-index:5
}


/* 左侧logo */
.home{
  display: flex;
  justify-content: center;
  align-items: center;
}

.home a{
  display: flex;
  width: 100%;
  justify-content: center;
  align-items: center;
}

#logo_svg{
  height: 60px;
}


/* 文字 */
.home .text{
  display: flex;
  align-items: center;
  font-weight: bold;
}

.home .text > div{
  height: 100px;
  display: flex;
  height: 100px;
  flex-direction: column;
  justify-content: center;
}
.home .text .t1{
  margin: 0px 8px;
  font-size: 36px;
}
.home .text .t2{
  font-size: 14px;
}




/* 导航栏 */
.el-col {
  height: 100px;
}
.navbar{
  display: flex;
  justify-content: space-around;
}
.navbar a{
  
  
  font-size: 1.2rem;
  font-weight: bold;

  display: flex;
  flex: 1;
  justify-content: center;
  align-items: center;
}

.navbar a:hover{
  animation: jump .3s;
}

@keyframes jump
{
    0%   {margin-top: 0px;}
    50%  {margin-top: -10px;}
    100% {margin-top: 0px;}
}

/* 登录块 */

.login{
  /* position: relative; */
  display: flex;
  justify-content: center;
  align-items: center;
}
.login>div{
  display: flex;
  justify-content: center;
  align-items: center;
  height:100%;
  width: 100px;
  position: relative;
}

.login .el-avatar{
  height: 40px;
  width: 40px;
  transition: .2s;
}



.login .card{
  z-index: 5;
  /* height: 150px; */
  width: 200px;
  padding: 30px 0 10px 0;
  background-color:white;

  position: absolute;
  left: 50%;
  top: 80px;
  transform: translate(-50%,0);

  display: flex;
  flex-direction: column;
  align-items: center;
  /* justify-content: space-evenly; */

  border: 1px solid #E3E5E7;
  border-radius: 8px;
  box-shadow: 0 0 30px rgb(0 0 0 / 10%);

  /* display: none; */
  opacity: 0;
  transition: .2s;

  pointer-events: none;
}

.login .card button{
  margin: 0px;
  width: 70%;
  margin-bottom: 20px;
}


/* 鼠标移入登录块 */
.login>div:hover .el-avatar{
  height: 50px;
  width: 50px;
}

.login>div:hover .card{
  display: flex;
  opacity: 1;
  pointer-events: all;
}


/* 进度条 */
.el-row:last-child{
  background-color: #f5f5f5;
  box-shadow:inset 0 1px 2px rgb(0 0 0 / 10%)
}
.progress{
  background: #B94844;
  height: 2px;
  transition: .5s;
  /* width: 10%; */
}


</style>