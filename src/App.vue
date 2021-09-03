<template>
  <div id="app">
    <NavBar />
    <HelloWorld />
    <Footer />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import NavBar from "./components/NavBar";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    NavBar,
    Footer,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: repeat(4, 1fr) 10px;
  min-height: 100vh;
  min-width: auto;
}
</style>
