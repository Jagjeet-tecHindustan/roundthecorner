<template>
  <div id="app">
      <app-headers></app-headers>
      <app-home></app-home>
      <app-footer></app-footer>  
  </div>
</template>

<script>
import Header from "./components/header/Header.vue";
import Home from "./components/home/Home.vue";
import Footer from "./components/footer/Footer.vue";
export default {
  components: {
    "app-headers": Header,
    "app-home": Home,
    "app-footer": Footer
  },
  name: "App"
};
</script>

 <style>
</style>