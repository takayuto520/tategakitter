<template>
  <img alt="Vue logo" class="vue-logo" src="./assets/logo.png">
  <TategakiApp></TategakiApp>
</template>

<script>
import TategakiApp from "./components/TategakiApp.vue"

export default {
  name: 'App',
  components: {
    TategakiApp
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
  margin-top: 60px;
}
</style>
