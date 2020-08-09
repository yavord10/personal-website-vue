<template>
  <div id="app">
    <Nav />
    <Intro />
    <PortfolioSlider />
  </div>
</template>

<script>
import Intro from './components/Intro.vue'
import Nav from './components/Nav.vue'
import PortfolioSlider from './components/PortfolioSlider.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Intro,
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
}
</style>
