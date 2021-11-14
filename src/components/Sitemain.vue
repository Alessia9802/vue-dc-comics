<template>
  <div id="site_main">
    <div class="jumbo"></div>
    <div class="current_series">
      <blog-post
        v-for="post in posts"
        v-bind:key="post.thumb"
        v-bind:price="post.price"
        v-bind:title="post.series"
        v-bind:type="post.type"
        ><!-- {{ post.thumb }}{{ post.price }}{{ post.series }}{{ post.type }} -->
      </blog-post>
      <img :src="key" />
      <p>{{ price }}</p>
      <h3>{{ title }}</h3>
      <p>{{ type }}</p>
    </div>
    <div class="buy_comics">
      <div class="digital">
        <img
          class="dc_comics dg_comics"
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
          class="dc_comics shop"
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
export default {
  props: {
    key: String,
    price: String,
    title: String,
    type: String,
  },
  data() {
    return {
      posts: [
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
          price: "$19.99",
          series: "Action Comics",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
          price: "$3.99",
          series: "American Vampire 1976",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
          price: "$16.99",
          series: "Aquaman",
          type: "graphic novel",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
          price: "$2.99",
          series: "Batgirl",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$3.99",
          series: "Batman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$2.99",
          series: "Batman Beyond",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
          price: "$3.99",
          series: "Batman/Superman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
          price: "$4.99",
          series: "Batman/Superman Annual",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
          price: "$5.99",
          series: "Batman: The Joker War Zone",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
          price: "$6.99",
          series: "Batman: Three Jokers",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
          price: "$4.99",
          series: "Batman: White Knight Presents: Harley Quinn",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
          price: "$16.99",
          series: "Catwoman",
          type: "graphic novel",
        },
      ],
    };
  },
};
</script>

<style lang="scss">
#site_main {
  color: white;
  height: 1000px;
}

#site_main p {
  width: 1100px;
  margin: auto;
  line-height: 200px;
}

#site_main .jumbo {
  height: 400px;
  background-image: url(../assets/vue-dc-comics-1/img/jumbotron.jpg);
  background-size: cover;
}

#site_main .current_series {
  height: 400px;
  background-color: #1c1c1c;
}

#site_main .buy_comics {
  height: 200px;
  background-color: #0282f9;
  display: flex;
  justify-content: center;
  align-items: center;
  text-transform: uppercase;
  padding-left: 150px;
  padding-right: 150px;
}

#site_main .digital {
  display: flex;
  justify-content: center;
  align-items: center;
}

.dc_comics {
  padding: 1rem;
  width: 120px;
}

.shop {
  width: 90px;
}

.dg_comics {
  width: 100px;
}

.visa {
  width: 120px;
}
</style>
