<template>
  <div id="app">
    <Nav />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <PortfolioSlider />
    <img alt="Vue logo" src="./assets/logo.png">
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Nav from './components/Nav.vue'
import PortfolioSlider from './components/PortfolioSlider.vue'

export default {
  name: 'App',
  components: {
    Nav,
    HelloWorld,
    PortfolioSlider
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
}
</style>
