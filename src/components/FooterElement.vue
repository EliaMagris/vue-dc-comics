<template>
  <div class="ElementContainer">
    <div class="listContainer"><div>
      <ul class="ul-style">
        <h3>dc comics</h3>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>Games</li>
        <li>Videos</li>
        <li>News</li>
      </ul>
      <ul class="ul-style">
        <h3>shop</h3>
        <li>Shop DC</li>
        <li>Shop DC Collectibles</li>
      </ul>
    </div>
    <div>
      <ul class="ul-style">
        <h3>dc</h3>
        <li>Term Of Use</li>
        <li>Privacy Policy (New)</li>
        <li>Ad Choices</li>
        <li>Advertising</li>
        <li>Jobs</li>
        <li>Subscriptions</li>
        <li>Talent Workshops</li>
        <li>CPSC Certificates</li>
        <li>Ratings</li>
        <li>Shop Help</li>
        <li>Contact Us</li>
      </ul>
    </div>
    <div>
      <ul class="ul-style">
        <h3>sites</h3>
        <li>DC</li>
        <li>MAD Magazine</li>
        <li>DC Kids</li>
        <li>DC Universe</li>
        <li>DC Power Visa</li>
      </ul>
    </div></div>
    
    <div class="imgContainer">
      <img src="../assets/img/dc-logo-bg.png" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterElement",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.ElementContainer {
  display: flex;
  align-items: center;
  position: relative;
  width: 80%;
  margin: auto;
  height: 80%;

  .listContainer{
    display: flex;
  }

  ul{
    list-style: none;
    padding: 10px;

    li{
        color: rgb(153, 153, 153);
        padding: 2px 0;
        font-size: 0.9rem;
    }

    h3{
        text-transform: uppercase;
    }
  }
  .imgContainer {
    z-index: 0;
    position: absolute;
    right: 0;
    top: - 90px;
    
    img{
        width: 100%;

    }
  }
}
</style>
