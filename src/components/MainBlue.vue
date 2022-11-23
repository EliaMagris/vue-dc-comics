<template>
  <div class="MainBlue">
    <div class="blueContainer">
      <ul>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
          <span>digital comics</span>
        </li>
        <li>
          <img src="../assets/img/buy-comics-merchandise.png" alt="" /><span
            >dc merchandise</span
          >
        </li>
        <li>
          <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
          <span>subscriptions</span>
        </li>
        <li>
          <img
            class="location"
            src="../assets/img/buy-comics-shop-locator.png"
            alt=""
          />
          <span>comic shop locator</span>
        </li>
        <li>
          <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
          <span>dc power visa</span>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainBlue",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.MainBlue {
  background-color: rgb(7, 130, 245);
  z-index: 2;
  height: 60%;
  display: flex;
  align-items: center;
  .blueContainer {
    width: 80%;
    margin: auto;
    padding: 15px 0;
    color: white;

    ul {
      list-style: none;
      display: flex;
      align-items: center;
      img {
        width: 50px;
      }

      .location {
        width: 40px;
      }
      li {
        display: flex;
        align-items: center;
        flex-basis: 20%;
        justify-content: center;
        font-size: 0.9rem;

        span {
          padding: 0 8px;
        }
      }
    }
  }
}
</style>
