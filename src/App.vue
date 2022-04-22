<template>
  <div class="app">
    <HeaderComp />
    <HomePage />
  </div>
</template>

<script>
import HeaderComp from "./components/HeaderComp.vue";
import HomePage from "@/views/HomePage.vue";

export default {
  components: { HeaderComp, HomePage },
};
</script>

<style>
#app {
  /*   font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}
</style>
