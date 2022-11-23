<template>
  <div class="MainBlue">
    <div class="blueContainer">
      <ul>
        <li> <img src="../assets/img/buy-comics-digital-comics.png" alt=""> <span>DIGITAL COMICS</span> </li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainBlue',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.MainBlue {
  background-color: rgb(7, 130, 245);
  
  .blueContainer {
    width: 80%;
    margin: auto;
    padding: 15px 0;
    color: white;

    ul{
        list-style: none;

        img{
            width: 50px
        };
    }
  }
}
</style>
