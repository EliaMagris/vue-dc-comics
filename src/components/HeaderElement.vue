<template>
  <div class="containerHeader">
    <div><img src="../assets/img/dc-logo.png" alt="" /></div>
    <div class="navContainer">
      <ul class="navBar">
        <li>CHARATERS</li>
        <li class="active">COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderElement",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.containerHeader {
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-weight: bold;
  width: 80%;
  margin: auto;
  height: 100%;

  img {
    width: 80px;
  }

  .navContainer {
    display: flex;
    align-items: center;
    
  }

  .navBar {
    display: flex;
    font-size: 0.8rem;

    li::after {
      content: "";
      display: block;
      margin: auto;
      height: 2px;
      width: 5px;
      transition: all 0.4s;
    }

    li:hover::after {
      width: 100%;
      background: rgb(31, 5, 224);
    }

    .active {
      color: blue;
    }

    li {
      list-style: none;
      margin: 0 15px;
      cursor: pointer;
      position: relative;
    }
  }
}
</style>
