<template>
  <main>
    <MainBlack/>
    <MainBlue/>
  </main>
</template>

<script>

import MainBlack from './MainBlack.vue'
import MainBlue from './MainBlue.vue'

export default {
  name: 'MainSec',
  components: {
    MainBlack,
    MainBlue
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
main{
  height: 30%;
  position: relative;
  z-index: 2;
}
  .MainBlue{
    font-weight: bold;
    text-transform: uppercase;
  }
</style>
