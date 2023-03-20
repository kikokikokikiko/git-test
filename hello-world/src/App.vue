<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <!-- <HelloWorld msg="My first Vue demo!"/> -->
  <header-content></header-content>
  <index-banner></index-banner>
  <home-content></home-content>
  <footer-content></footer-content>
  
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HeaderContent from './components/HeaderContent.vue'
import IndexBanner from './components/IndexBanner.vue'
import HomeContent from './components/HomeContent.vue'
import FooterContent from './components/footerContent.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    HeaderContent,
    IndexBanner,
    HomeContent,
    FooterContent,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
