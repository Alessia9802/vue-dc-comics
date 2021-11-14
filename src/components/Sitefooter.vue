<template>
  <div id="site_footer">
    <div class="section">
      <div class="menu_footer">
        <div class="menu_dc_comics">
          <h2>DC Comics</h2>
          <nav class="comics">
            <ul>
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">TV</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Videos</a></li>
              <li><a href="#">News</a></li>
            </ul>
          </nav>
          <div class="menu_shop">
            <h2>Shop</h2>
            <nav>
              <ul>
                <li><a href="#">Shop DC</a></li>
                <li><a href="#">Shop DC Collectibles</a></li>
              </ul>
            </nav>
          </div>
        </div>
        <div class="menu_dc">
          <h2>Dc</h2>
          <nav>
            <ul>
              <li><a href="#">Terms Of Use</a></li>
              <li><a href="#">Privacy Policy(New)</a></li>
              <li><a href="#">Ad Choises</a></li>
              <li><a href="#">Advertising</a></li>
              <li><a href="#">Jobs</a></li>
              <li><a href="#">Subscriptions</a></li>
              <li><a href="#">Talent Workshops</a></li>
              <li><a href="#">CPSC Certificates</a></li>
              <li><a href="#">Ratings</a></li>
              <li><a href="#">Shop Help</a></li>
              <li><a href="#">Contact us</a></li>
            </ul>
          </nav>
        </div>
        <div class="menu_sites">
          <h2>Sites</h2>
          <nav>
            <ul>
              <li><a href="#">DC</a></li>
              <li><a href="#">MAD Magazine</a></li>
              <li><a href="#">DC Kids</a></li>
              <li><a href="#">DC Universe</a></li>
              <li><a href="#">DC Power Visa</a></li>
            </ul>
          </nav>
        </div>
      </div>
      <div class="logo_footer">
        <img
          class="logo"
          src="../assets/vue-dc-comics-1/img/dc-logo-bg.png"
          alt=""
        />
      </div>
    </div>
    <div class="copyright">
      <div class="btn_register">Sign-up now!</div>
      <div class="social">
        <p>Follow us</p>
        <img src="../assets/vue-dc-comics-1/img/footer-facebook.png" alt="" />
        <img src="../assets/vue-dc-comics-1/img/footer-twitter.png" alt="" />
        <img src="../assets/vue-dc-comics-1/img/footer-youtube.png" alt="" />
        <img src="../assets/vue-dc-comics-1/img/footer-pinterest.png" alt="" />
        <img src="../assets/vue-dc-comics-1/img/footer-periscope.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
#site_footer {
  height: 400px;
  margin: auto;
  background-image: url("../assets/vue-dc-comics-1/img/footer-bg.jpg");
  background-size: cover;
  font-family: "Roboto Condensed", sans-serif;
}

.section {
  display: flex;
  justify-content: space-between;
  padding-left: 200px;
  padding-right: 200px;
}

h2 {
  color: white;
  text-transform: uppercase;
}

.menu_footer {
  padding: 1rem;
  display: flex;
  justify-content: space-between;
}

.menu_dc_comics,
.menu_dc,
.menu_sites {
  padding: 1rem;
}

.menu_dc_comics > nav ul li {
  list-style: none;
  a {
    text-decoration: none;
    color: gray;
    font-size: 13px;
  }
}

.comics {
  padding-bottom: 1rem;
}

.menu_shop > nav ul li {
  list-style: none;
  a {
    text-decoration: none;
    color: gray;
    font-size: 13px;
  }
}

.menu_dc > nav ul li {
  list-style: none;
  a {
    text-decoration: none;
    color: gray;
    font-size: 13px;
  }
}
.menu_sites > nav ul li {
  list-style: none;
  a {
    text-decoration: none;
    color: gray;
    font-size: 13px;
  }
}

.logo_footer {
  width: 400px;
  height: 400px;
}

.logo_footer > .logo {
  width: 400px;
  height: 400px;
  margin-top: -50px;
}

.copyright {
  background-color: #303030;
  width: 100%;
  height: 100px;
  margin-top: -50px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-left: 200px;
  padding-right: 200px;
}

.btn_register {
  border: 2px solid #0282f9;
  width: 150px;
  height: 50px;
  text-transform: uppercase;
  color: white;
  text-align: center;
  line-height: 50px;
  font-family: "Roboto Condensed", sans-serif;
}
.social {
  width: 400px;
  height: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: "Roboto Condensed", sans-serif;
}

.social > p {
  color: #0282f9;
  padding: 1rem;
}

.social img {
  padding: 10px;
}
</style>
