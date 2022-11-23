<template>
  <div id="app">
    <HeaderSec/>
  </div>
</template>

<script>
import HeaderSec from './components/HeaderSec.vue'

export default {
  name: 'App',
  components: {
    HeaderSec
  }
}
</script>

<style lang="scss">

body{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  height: 100vh;
}
</style>
