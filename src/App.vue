<template>
  <div id="app">
    <Siteheader />
    <Sitemain />
    <div id="site_footer"></div>
  </div>
</template>

<script>
//import HelloWorld from "./components/HelloWorld.vue";
import Siteheader from "./components/Siteheader.vue";
import Sitemain from "./components/Sitemain.vue";

export default {
  name: "App",
  components: {
    Siteheader,
    Sitemain,
  },
};
</script>

<style lang="scss">
#app {
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  #site_header {
    font-family: "Greta Sans Medium", "Greta Sans Regular";
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 1100px;
    height: 120px;
    margin: auto;
  }

  .logo {
    width: 100px;
    height: 100px;
  }

  .main_menu > ul li {
    display: inline-block;
    padding: 1rem;
  }

  .main_menu > ul li a {
    color: #464646;
    text-decoration: none;
  }

  #site_main {
    background-color: #1c1c1c;
    color: white;
    height: 200px;
  }

  #site_main p {
    width: 1100px;
    margin: auto;
    line-height: 200px;
  }

  .buy_comics {
    height: 200px;
    background-color: #0282f9;
    display: flex;
    justify-content: center;
    align-items: center;
    text-transform: uppercase;
  }

  .digital {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .dc_comics {
    padding: 1rem;
  }

  .visa {
    width: 150px;
    height: 150px;
  }
}
</style>
