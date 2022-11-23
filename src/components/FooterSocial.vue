<template>
  <div class="socialContainer">
    <div class="socialFlex">
      <div><button>SIGN-UP NOW!</button> </div>
      <div>
        <ul>
          <li><h3>FOLLOW US</h3></li>
          <li> <img src="../assets/img/footer-facebook.png" alt=""> </li>
          <li><img src="../assets/img/footer-periscope.png" alt=""></li>
          <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
          <li><img src="../assets/img/footer-twitter.png" alt=""></li>
          <li><img src="../assets/img/footer-youtube.png" alt=""></li>
        </ul>
      </div>
    </div>
  </div>

    
  </template>
  
  <script>
  export default {
    name: 'FooterSocial',
    
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">

  .socialContainer{
    background-color: rgb(42, 41, 41);
    height: 20%;
    position: relative;
    z-index: 2;
    display: flex;
    align-items: center;
  }
  .socialFlex{
    width: 80%;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
    
    button{
      padding: 10px;
      background-color: rgb(42, 41, 41);
      border: 1px solid rgb(20, 103, 246);
      color: white;
    }
    ul{
      list-style: none;
      display: flex;
      align-items: center;

      li{
        padding: 0 10px;
      }

      h3{
        color: rgb(74, 74, 233);
      }
    }
  }
  
  </style>
  