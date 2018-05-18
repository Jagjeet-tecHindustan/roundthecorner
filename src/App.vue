<template>
  <div id="app">
    <app-headers></app-headers>
    <app-home></app-home>
    
    
       
  </div>
</template>

<script>
import Header from "./components/header/Header.vue";
import Home from "./components/home/Home.vue";
export default {
  components: {
    "app-headers": Header,
    "app-home": Home
  },
  name: "App"
};
</script>

 <style>
</style>