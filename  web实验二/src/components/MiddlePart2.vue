<template>
    <div id="b2-1" >
    <br>
    <div class="container">
  
    <div style="display:flex;justify-content:center;align-items:center;">
      <img class="img" src="../assets/img-screens@2x.png" >
    </div>
      <br>
  
      <h2>双屏学习</h2>
      <div id="b2-2" > <font size="3">双屏学习，小屏视频互动，大屏实际操作，学习无障碍。打开浏览器，即刻开始编程！</font> </div>
      <br>
      
      <div id="b2-3" ><input type="button" value="了解详情" @click="alarm" style="width: 100%;height: 30px;background:transparent;border: 1px solid rgb(6, 6, 6);border-radius: 2px;color: rgb(98, 101, 103);font-size: 12px;"></div>
      <br>
  
  </div>
  </div>
  </template>
  
  <script>
  export default {
  name:'MiddlePart2',
  methods:{
    alarm(){
            alert("你点了我一下")
        }
  }

  }
  </script>
  
  <style>
  #b2-1{
      background-color: #ffffff;
  }
  
  #b2-2{
      text-align: left;
      color: rgb(116, 116, 116);
  }
  
  #b2-3{
      text-align: center;
  }
  img{
  
  display: block;
  
  height: auto;
  
  max-width: 100%;
  
  text-align: center;
  }
  </style>