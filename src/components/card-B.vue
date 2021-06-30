<template>
      <div class="detail">
        <div class="lists">
          <div class="item" v-for="(data,index) in items" :key="index">
            <div class="logo">
              <img src="data.img" alt />
              <p>{{data.item}}</p>
            </div>
            <button class="button">{{data.button}}</button>
          </div>  
        </div>
      </div>
</template>

<script>
export default {
  data () {
    return {
      lists: [
        {
          img: require("../assets/icon-btc-jpy.svg"),
          item: "BTC/JPY",
          button: "詳細"
        },
        {
          img: require("..assets/icon-eth-jpy.svg"),
          item: "ETH/JPY",
          button: "詳細"
        },
        {
          img: require("../assets/icon-bch-jpy.svg"),
          item: "BCH/JPY",
          button: "詳細"
        },
        {
          img: require("../assets/icon-ltc-jpy.svg"),
          item: "LTC/JPY",
          button: "詳細"
        },
        {
          img: require("../assets/icon-xpr-jpy.svg"),
          item: "XPR/JPY",
          button: "詳細"
        }
      ]
    };
  }
};
</script>