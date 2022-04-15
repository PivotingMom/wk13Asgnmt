<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->

    <firstHeader/> 
    <firstFooter/>
    <firstBody/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

 import firstHeader from './components/firstHeader.vue' //import

import firstBody from './components/firstBody.vue'
import firstFooter from './components/firstFooter.vue'

export default {
  name: 'App',
  components: {
     // HelloWorld
    firstHeader,//registration
    firstFooter,
    firstBody
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
  margin-top: 60px;
}
</style>
