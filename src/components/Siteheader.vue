<template>
  <div id="site_header">
    <div class="logo_header">
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
#site_header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 1200px;
  height: 120px;
  margin: auto;
  font-family: "Roboto Condensed", sans-serif;
}

.logo_header {
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
  :hover {
    border-bottom: 5px solid #0282f9;
    padding-bottom: 45px;
    color: #0282f9;
  }
}
</style>
