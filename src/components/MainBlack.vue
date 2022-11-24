<template>
  <div class="MainBlack">
    <div class="cards">
      <img :src="dettagliProdotto.thumb" alt="" />
      <h4>{{ dettagliProdotto.series }}</h4>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainBlack",
  props: {
    dettagliProdotto: Object,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.MainBlack {
  width: calc(100% / 6);
  flex-wrap: wrap;
  color: white;
  .cards {
    text-align: center;

    img{
      width: 85%;
    }
  }
}
</style>
