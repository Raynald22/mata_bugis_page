<template>
  <div id="app">
    <Navbar />
    <Content />
    <Feature />
    <About />
    <!-- <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Navbar from "./components/Navbar.vue";
import Content from "./components/Content.vue";
import Feature from "./components/Feature.vue";
import About from "./components/About.vue";
import "./App.css";

export default {
  name: "App",
  components: {
    Navbar,
    Content,
    Feature,
    About,
  },
};
</script>
