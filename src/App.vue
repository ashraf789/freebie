<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <!-- <home></home> -->
    <router-view/>
  </div>
</template>

<script>
import './assets/css/main.css'
//  import HelloWorld from './components/HelloWorld.vue'
// import Home from './views/Home.vue';
export default {
  name: 'App',
  // components: {
  //   Home,
  // }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
}
</style>
