<template>
  <div id="app">
    <HeaderSec/>
    <MainSec/>
  </div>
</template>

<script>
import HeaderSec from './components/HeaderSec.vue'
import MainSec from './components/MainSec.vue'

export default {
  name: 'App',
  components: {
    HeaderSec,
    MainSec
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
