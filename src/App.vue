<template>
  <div id="App">
    <Siteheader />
    <Sitemain />
    <Sitefooter />
  </div>
</template>

<script>
//import HelloWorld from "./components/HelloWorld.vue";
import Siteheader from "./components/Siteheader.vue";
import Sitemain from "./components/Sitemain.vue";
import Sitefooter from "./components/Sitefooter.vue";

export default {
  name: "App",
  components: {
    Siteheader,
    Sitemain,
    Sitefooter,
  },
};
</script>
<style lang="scss">
@import "./assets/vue-dc-comics-1/scss/common.scss";
@import url("https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@700&display=swap");
</style>
