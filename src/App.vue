<template>
  <div id="app">
    <Toolbar/>
    <Footer/>

  </div>
</template>

<script>

import Toolbar from "./components/Toolbar";
import Footer from "./components/Footer";

export default {
  name: 'App',
  components: {
    Footer,
    Toolbar
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

  * {
    margin: 0 !important;
  }
</style>
