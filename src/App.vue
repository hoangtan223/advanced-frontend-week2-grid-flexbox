<template>
  <div id="app">
    <Weather/>
  </div>
</template>

<script>
import Weather from './components/Weather'
import './assets/main.scss'

export default {
  name: 'App',
  components: {
    Weather
  }
}
</script>

<style>
#app {
  font-family: 'PT Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  height: 100vh;
}
</style>
