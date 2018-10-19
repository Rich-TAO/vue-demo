<template>
  <div id="app">
    <hello-world></hello-world>
    <router-view></router-view>
    <!-- <a-a></a-a> -->
  </div>
</template>

<script>
import  HelloWorld  from './components/HelloWorld'
// import a from './components/Home/Swiper'
export default {
  name: 'App',
  components: {
        'hello-world':HelloWorld,
        // 'a-a':a
    }
}
</script>

<style>
  #app{
    height: 100%;
    overflow:scroll;
  }
</style>
