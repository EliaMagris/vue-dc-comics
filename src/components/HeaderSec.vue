<template>
  <header>
     <HeaderElement/>
  </header>
</template>

<script>

import HeaderElement from './HeaderElement.vue'

export default {
  name: 'HeaderSec',
  components: {
    HeaderElement
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  header{
    z-index: 2;
    padding: 5px;
  }

</style>