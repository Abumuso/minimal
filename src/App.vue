<template>
  <navbar />
  <section1 />
  <section2 />
  <section3 />
</template>

<script setup>
import navbar from "./components/Navbar.vue";
import section1 from "./components/Section1.vue";
import section2 from "./components/Section2.vue";
import section3 from "./components/Section3.vue";
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
}
#app {
  margin: 0 auto;
  width: 1440px;
  // height: 5163px;
  background: #fff;
  font-family: Arial, Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.conteiner {
  width: 940px;
}
@media (max-width: 990px) {
  .conteiner {
    width: 740px;
  }
}
@media (max-width: 769px) {
  .conteiner {
    width: 440px;
  }
}
@media (max-width: 447px) {
  .conteiner {
    width: 100%;
  }
}
</style>
