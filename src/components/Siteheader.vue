<template>
  <div id="site_header">
    <div class="logo">
      <img src="../assets/vue-dc-comics-1/img/dc-logo.png" alt="" />
    </div>
    <nav class="main_menu">
      <ul>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Collectibles</a></li>
        <li><a href="#">Videos</a></li>
        <li><a href="#">Fans</a></li>
        <li><a href="#">News</a></li>
        <li><a href="#">Shop</a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
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
</style>
