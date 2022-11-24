<template>
    <button>
      {{propsText}}
    </button>
  </template>
  
  <script>
    export default {
      props: {
        propsText: String,
      }
    }
  </script>
  
  <style lang="scss" scoped>
    button{
      background-color: rgb(93, 93, 231);
      color: white;
      padding: 10px 25px;
      border: 1px solid black;
    }
  </style>
  Footer
  
  