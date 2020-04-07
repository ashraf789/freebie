<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <home></home>
    <awesome-feature></awesome-feature>
    <!-- <router-view/> -->
  </div>
</template>

<script>
import './assets/css/main.css'
//  import HelloWorld from './components/HelloWorld.vue'
import Home from './views/Home.vue'
import AwesomeFeature from './views/AwesomeFeatures.vue'

export default {
  name: 'App',
  components: {
    Home,
    AwesomeFeature,
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
  margin-top: 20px;
}
</style>
