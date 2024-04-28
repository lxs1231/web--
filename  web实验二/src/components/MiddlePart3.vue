<template>
    <div>
    <div class="container">
      <h3>课程特色</h3>
  
      <hr>
  
      <br>
  
    <div class="row" style="display: flex; flex-direction: row ;justify-content:flex-start ;">
  
      <div class="col-md-4" style="display: inline;">
        <img src="../assets/截屏2024-03-25 21.08.44.png">
        <br>
        <h3 >丰富的教学服务</h3>
        <div id="b3-text1" > <font size="3">特色教学服务功能，各种配套教学服务，在线学习从未如此轻松。</font> </div>
        
        <a href="" @click="alarm">马上学习 ></a>
        <br>
      </div>
      
      <div class="col-md-4" style="display: inline;">
        <img src="../assets/截屏2024-03-25 21.08.56.png">
        <br>
        <h3 >多元的学习方式</h3>
        <div id="b3-text2" > <font size="3">知识提炼、答疑解惑、实时互动、开发有特色的教学服务方式。</font> </div>
        
        <a href="" @click="alarm">马上学习 ></a>
        <br>
      </div>
  
      <div class="col-md-4" style="display: inline;">
        <img src="../assets/截屏2024-03-25 21.09.05.png">
        <br>
        <h3 >高品质的学习体验</h3>
        <div id="b3-text3" > <font size="3">多屏合一，随时学习，随时在线，学习记录一目了然，知识充电不再受限。</font> </div>
        
        <a href="" @click="alarm">马上学习 ></a>
        <br>
      </div>
  
    </div>
  
    </div>
    <br>
  </div>
  </template>
  
  <script>
  export default {
  name:'MiddlePart3',
  methods:{
    alarm(){
            alert("你点了我一下")
        }
  }
  }
  </script>
  
  <style>
  #b3-text1{
      text-align: left;
      color: rgb(0, 0, 0);
  }
  
  #b3-text2{
      text-align: left;
      color: rgb(0, 0, 0);
  }
  
  #b3-text3{
      text-align: left;
      color: rgb(0, 0, 0);
  }
  img{
  
  display: block;
  
  height: auto;
  
  max-width: 100%;
  
  text-align: center;
  }
  </style>