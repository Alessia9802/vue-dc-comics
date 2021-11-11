<template>
  <div id="site_main">
    <p>--> Content goes here --></p>
    <div class="buy_comics">
      <div class="digital">
        <img
          class="dc_comics"
          src="../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png"
          alt=""
        />
        <div>digital comics</div>
        <img
          class="dc_comics"
          src="../assets/vue-dc-comics-1/img/buy-comics-merchandise.png"
          alt=""
        />
        <div>dc merchandise</div>
        <img
          class="dc_comics"
          src="../assets/vue-dc-comics-1/img/buy-comics-subscriptions.png"
          alt=""
        />
        <div>subscription</div>
        <img
          class="dc_comics"
          src="../assets/vue-dc-comics-1/img/buy-comics-shop-locator.png"
          alt=""
        />
        <div>comic shop locator</div>
        <img
          class="dc_comics visa"
          src="../assets/vue-dc-comics-1/img/buy-dc-power-visa.svg"
          alt=""
        />
        <div>dc power visa</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
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
</style>
