<template>
  <div id="app">
    <Toolbar/>
    <Hero/>
    <Social/>
    <Footer/> 
  </div>
</template>

<script>

import Toolbar from './components/Toolbar.vue';
import Hero from './components/Hero.vue';
import Social from './components/Social.vue';
import Footer from './components/Footer.vue';


export default {
  name: 'App',
  components: {
    Toolbar,
    Hero,
    Social,
    Footer,
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
}z

  * {
    margin: 0 !important;
  }
</style>
