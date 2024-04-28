<template>
    <div id="home1" >
    <div class="container">
      <br>

    <div style="display: flex;justify-content: space-between;">
      <img id="logo" src="../assets/logo-white.svg" alt="">
        <div>
            <button  type="button" class="btn btn-outline-primary" style="color: white;border-color: white;" @click="like">登录</button>
            <div class="model-box" v-show="isShow" @click.self="hideModel">
            <div class="center">
                <form action="">
                <h1>登录</h1>
                <br>
                <div>用户名：<input type="text"></div>
                <br>
                <!-- 可以在键盘事件中，使用按键修饰符， .按钮对应的code码 -->
                <div>密&nbsp;&nbsp;&nbsp;&nbsp;码：<input type="password" ></div>
                <br>
                <div style="display: flex;justify-content:space-around;">
                    <button class="btn btn-outline-primary">登录</button>
                    <button type="reset" class="btn btn-outline-primary">重置</button>
                    <button class="btn btn-outline-primary" @click.prevent="handleregister">注册</button>
                </div>
            </form>
            </div>
        </div>
            <button type="button" class="btn btn-outline-primary" style="color: white;border-color: white; " @click="like2" >注册</button>
            <div class="model-box" v-show="isShow2" @click.self="hideModel2">
            <div class="center2">
                <form action="">
                <h1>注册</h1>
                <br>
                <div>用户名&nbsp;&nbsp;&nbsp;&nbsp; <input type="text"></div>
                <br>
                <!-- 可以在键盘事件中，使用按键修饰符， .按钮对应的code码 -->
                <div>密&nbsp;&nbsp;&nbsp;&nbsp;码 &nbsp;&nbsp;&nbsp; <input type="password" ></div>
                <br>
                <div>确认密码 <input type="password"></div>
                <br>
                <div style="display: flex;justify-content:space-around;">
                    <button class="btn btn-outline-primary">提交</button>
                    <button type="reset" class="btn btn-outline-primary">重置</button>
                    <button class="btn btn-outline-primary">返回</button>
                </div>
            </form>
            </div>
        </div>
        </div>
    </div>

      <br>

    <div id="home3" ><font size="6">云端编程，浏览器里边学边练</font></div>
    <div id="home4" > <font size="3">软件定义一切，网络连接时空，学习软件技术，创造未来世界。</font> </div>

    <br>
    <br>

    <div id="home5" ><input id="bnt3" type="button" value="马上学习" @click="alarm"></div>

    <br>
    <br>
    <br>
    <br>
    
    </div>
   </div>

</template>

<script>

   export default {
    name:'HeaderOne',
    data(){
        return{
            isShow: false,
            isShow2: false
        }
    },
    methods:{
        like(){
            this.isShow = true;
        },           
        hideModel() {
            this.isShow = false;
        },
        login() {
            alert("登录")
        },
        like2(){
            this.isShow2 = true;
        },           
        hideModel2() {
            this.isShow2 = false;
        },
        register() {
            alert("登录")
        },
        toregister(){
            this.isShow2 = true;
            this.isShow = false
        },
        alarm(){
            alert("你点了我一下")
        }

    }
   }
   

</script>

<style>

#home1{
    background: url(../assets/home-banner@2x.jpg);
    background-repeat: repeat;
    background-size: 100% 100%;
    
}

#home2{
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; 
    color: #ffffff;
}

#home3{
    text-align: center;
    color: white;
}

#home4{
    text-align: center;
    color: white;
}

#home5{
    text-align: center;
}

#logo{
    width: 100px; 
    height: auto;
}

#bnt1{
    width: 40px;
    height: 30px;
    background:transparent;
    border: 1px solid white;
    border-radius: 2px;
    color: white;
    font-size: 12px;
}

#bnt2{
    width: 40px;
    height: 30px;
    background:transparent;
    border: 1px solid white;
    border-radius: 2px;
    color: white;
    font-size: 12px;
}

#bnt3{
    width: 110px;
    height: 30px;
    background:white;
    border: 1px solid white;
    border-radius: 2px;
    color: rgb(64, 111, 228);
    font-size: 12px;
}

.model-box {
            position: fixed;
            left: 0;
            top: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(20, 20, 151, 0.2);
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .center {
            width: 500px;
            height: 300px;
            background-color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: space-evenly;
        }
        
        .center2 {
            width: 500px;
            height: 400px;
            background-color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: space-evenly;
        }
        #center div {
            text-align: center;
        }
img{

    display: block;
    
    height: auto;
    
    max-width: 100%;
    
    text-align: center;
    }
</style>