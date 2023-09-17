<template>
  <navbar />
  <section1 />
  <section2 />
</template>

<script setup>
import navbar from "./components/Navbar.vue";
import section1 from "./components/Section1.vue";
import section2 from "./components/Section2.vue";
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
}
#app {
  width: 1440px;
  height: 5163px;
  background: #fff;
  font-family:Arial, Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
