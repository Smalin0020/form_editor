<template>
  <div id="app">
    <the-layout />
  </div>
</template>

<script>
import TheLayout from './components/TheLayout.vue'

export default {
  name: 'app',
  components: {
    TheLayout
  }
}
</script>

<style>
html, body {
  list-style: none;
  padding: 0;
  margin: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
