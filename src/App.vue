<template>
  <div id="app">
    <img src="./assets/logo.png" alt="">
    <Hero/>
  </div>
</template>

<script>
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    Hero
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
  margin: auto;
  padding: 0;
}
img {
  position: absolute;
  z-index: 2;
  left: 50%;
  top: 50px;
  transform: translate(-50%);
}
</style>
