<template>
    <div id="b1-1" >
     <br>
   <div class="container">
    
 <div style="display:flex;justify-content:center;align-items:center;"> 
     <img class="img" src="../assets/img-lab@2x.png" alt="">
 </div>
   <br>
 
   <h2>云端编程实验室</h2>
   <div id="b1-2" > <font size="3">每人拥有自己完全独立的编程实验室，内置所有基础软件及学习素材。打开浏览器，即刻开始编程！</font> </div>
   <br>
   
   <div id="b1-3"  ><input type="button" value="了解详情" @click="alarm" style="width: 100%;height: 30px;background:transparent;border: 1px solid rgb(6, 6, 6);border-radius: 2px;color: rgb(130, 131, 132);font-size: 12px;"></div>
   <br>
   </div>
    </div>
 </template>
 
 <script>
 export default {
     name:'MiddlePart1',
     methods:{
        alarm(){
            alert("你点了我一下")
        }
     }
 
 }
 </script>
 
 <style>
 
 #b1-1{
     background-color: #eaeaea;
 }
 
 #b1-2{
     text-align: left;
     color: rgb(116, 116, 116);
 }
 
 #b1-3{
     text-align: center;
 }
 img{
 
 display: block;
 
 height: auto;
 
 max-width: 100%;
 
 text-align: center;
 }
 </style>