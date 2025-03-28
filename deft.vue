<template>
  <header id="top-bar">
    <div id="per-imag">
      <img src="./pictures/per.jpg" alt="头像"></img>
      <span id="name">Deft</span>
    </div>
    <div id="top-menu">
      <div class="line1">
        <a class="test1"href=""><span clamss="t-test1">个人介绍</span></a>
      </div>
      <div class="line1">
        <a class="test1" href=""><span class="t-test1">我的相册</span></a>
      </div>
      <div class="line1">
        <a class="test1" id="test3" target="_blank"><span class="t-test1">联系方式</span></a>
      </div>
    </div>
  </header>
  <div id="main">
    <div id="main-left">
      <div class="title">
        <div>
          <a href="../dist/video.html" class="title-img">
            <img src="./pictures/video.jpg" alt="视频" width="150px"></img>
          </a>
        </div>
        <div class="title-right">
          <a href="../video.html"> 
            <h2 style="color: black; margin-left: 15px;"> 
              <span id="jk">堡堡堡堡.mp4</span>
              <div class="date">
                <span style="font-size: 15px;">2025/03/20</span>
              </div>
            </h2>
          </a>
        </div>
      </div>
      <div class="title">
        <div>
          <a href="" class="title-img">
            <img src="./pictures/c++.jpg" alt="c++图片" width="150px"></img>
          </a>
        </div>
      </div>
    </div>
    <!-- 主页面右边 -->
    <div id="main-right">
      <div id="person-introduction">
        <div class="project">
          <div class="pro-text">
            <a href="">
              关于我的c++学习之路
            </a>
          </div>
        </div>
      </div>
      <div id="ddeeft">

      </div>
    </div>
  </div>
</template>

<script setup>
  
</script>

<style >
  body{
    margin: 0;
    /* padding: 0; */
    background-image: url("./pictures/backpaper.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
  #top-bar{
    margin: 0;
    padding: 0;
    position: fixed;
    top: 0;
    margin-left: 10%;
    margin-right: 10%;
    background-color:rgba(232, 90, 147, 0.35);
    left: 0;
    width: 80vw;
    display:flex;
    align-items:center;
    min-width: 320px;
  }
  #main{
    margin: 0;
    display: flex;
    width: 80vh;
    margin-top: 0;   
    margin-right: 10%;
    flex-direction: row;
  }
  #main-left{
    margin: 0 0;
    display: flex;
    margin-top: 0;
    margin-right: 0;
    width: 80vh;
    height: auto;
    margin-left: 0;
    margin-right: 20%;
    flex-direction: column;
  }
  #main-right{
    display: flex;
    flex-direction: row;
    width: 20vh;
    min-height: 500px;
  }
  #name{
    color: aqua;
    left: 10px;
    top: 5px;
  }
  #per-imag img{
    max-width: 100px;
    max-height: 100px;
  }
  #top-menu{
    margin-left: 70%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    gap: 10px;
    width: 80%;
  }
  .line1{
    margin-top: 50px;
  }
  .test1{
    cursor: pointer;
    font-size: 18px;
    color: black;
    text-decoration: underline;
    text-decoration-color: rgb(124, 151, 151);
  }
  .test1:hover{
    color:greenyellow;
  }
  .t-test1{
    color: aqua;
  }
  .title{
    margin-top: 2px;
    margin-left: 20px;
    display: flex;
    flex-direction: row;
    min-height: 160px;
  }
  .title-img{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 160px;
  }
  #jk:hover{
    text-decoration: underline;
  }
  .title-right{
    min-width: 80vh;
  }
  .date{
    display: flex;
    margin-top: 55px;
    margin-left: 50%;
  }
  #person-introduction{
    margin-left: 10px;
    border-left: 5px;
    padding-left: 10px;
    border-left-color: blue;
    display: flex;
    flex-direction: column;
  }
</style>    