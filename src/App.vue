<template>
  <div id="app">
    <Header></Header>
    <home></home>
    <awesome-feature></awesome-feature>
    <key-feature></key-feature>
    <price-plan></price-plan>
    <testemonial></testemonial>
    <div style="margin-top:100px"></div>
    <f-a-q></f-a-q>
    <div style="margin-top:100px"></div>

    <download-page></download-page>
    <Footer></Footer>
  </div>
</template>

<script>
import "./assets/css/main.css";
import Header from "./components/Header.vue";
import Home from "./views/Home.vue";
import AwesomeFeature from "./views/AwesomeFeatures.vue";
import KeyFeature from "./views/KeyFeature.vue";
import PricePlan from "./views/PricePlan.vue";
import Testemonial from "./views/Testemonial.vue";
import FAQ from "./views/FAQ.vue";
import Footer from "./components/Footer.vue";
import DownloadPage from "./views/DownloadPage.vue";

export default {
  name: "App",
  components: {
    Header,
    Home,
    AwesomeFeature,
    KeyFeature,
    PricePlan,
    Testemonial,
    FAQ,
    DownloadPage,
    Footer
  }
};
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
