<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <HeaderOne></HeaderOne>
  <MiddlePart1></MiddlePart1>
  <MiddlePart2></MiddlePart2>
  <MiddlePart3></MiddlePart3>
  <EndPart></EndPart>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HeaderOne from './components/HeaderOne.vue'
import MiddlePart1 from './components/MiddlePart1.vue'
import MiddlePart2 from './components/MiddlePart2.vue'
import MiddlePart3 from './components/MiddlePart3.vue'
import EndPart from './components/EndPart.vue'
export default {
  name: 'App',
  components: {
    // HelloWorld
    HeaderOne,
    MiddlePart1,
    MiddlePart2,
    MiddlePart3,
    EndPart
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}
</style>