<template>
  <div class="hello">
    <div class="search">
      <search></search>
    </div>
    <div class="banner">
      <banner></banner>
    </div>
    <div class="nav">
      <nav-li></nav-li>
    </div>
    <div class="main">
      <reconmmend></reconmmend>
    </div>
    <div class="sda"></div>
    <div class="tabbar">
      <tabbar></tabbar>
    </div>
  </div>
</template>

<script>
  import  Search  from './Home/Search'
  import  Tabbar  from './Home/Tabbar'
  import Banner from './Home/Banner'
  import Nav from './Home/Nav'
  import swiper from './Home/Swiper'

export default {

  name: "HelloWorld",
  components: {
    'search':Search,
    'tabbar':Tabbar,
    'banner':Banner,
    'nav-li':Nav,
    'reconmmend':swiper
  },
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  },
  methods: {
    
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
.hello{
  overflow:scroll;
}
.nav{
  width: 94%;
  margin: -172px auto;
  border-radius: 20px;
  box-shadow: #ccc 0 0 10px;
  z-index: 10;
  position: relative;
}
.main{
  margin-top: 180px;
}
</style>
