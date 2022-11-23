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

</style>
