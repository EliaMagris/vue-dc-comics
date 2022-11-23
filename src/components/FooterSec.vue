<template>
    <footer>
        <FooterElement/>
        <FooterSocial/>
    </footer>
  </template>
  
  <script>
  import FooterElement from './FooterElement.vue';
  import FooterSocial from './FooterSocial.vue'

  export default {
    name: 'FooterSec',
    components:{
        FooterElement,
        FooterSocial
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">
  footer{
    color: white;
    //padding: 10px;
    height: 60%;
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    z-index: 2;
  }
  
  </style>
  