<template>
  <div id="app">
    <Header></Header>
    <Landing></Landing>
    <Footer></Footer>
  </div>
</template>

<script>
import Footer from "@/components/Footer";
import Header from "@/components/Header";
import Landing from "@/components/Landing";


export default {
  name: 'App',
  components: {
    Landing,
    Header,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

</style>
