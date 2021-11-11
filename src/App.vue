<template>
  <div id="app">
    <Siteheader />
    <div id="site_main"></div>
    <div id="site_footer"></div>
  </div>
</template>

<script>
//import HelloWorld from "./components/HelloWorld.vue";
import Siteheader from "./components/Siteheader.vue";

export default {
  name: "App",
  components: {
    Siteheader,
  },
};
</script>

<style lang="scss">
#app {
}
</style>
