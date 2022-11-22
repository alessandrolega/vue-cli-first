<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <AppTitle />
    <HeroJumbo />
  </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue'
import HeroJumbo from './components/HeroJumbo.vue'

export default {
  name: 'App',
  components: {
    AppTitle,
    HeroJumbo
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#jumbotron{
  margin: 0 auto;
  width: 500px;
  height: 200px;
  background-color: #2c3e50;
  color: white;
}
</style>
