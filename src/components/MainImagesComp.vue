<template>
  <div class="card">
    <img :src="filmsDetails.thumb" alt="" />
    <h4>{{ filmsDetails.series }}</h4>
  </div>
</template>

<script>
export default {
  name: "MainImagesComp,",
  props: {
    filmsDetails: Object,
  },
};
</script>

<style lang="scss" scoped>
.card {
  width: calc(100% / 6);
  padding: 30px 0px;
  text-align: center;

  img {
    width: 150px;
    height: 150px;
  }

  h4 {
    color: white;
  }
}
</style>
