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
  width: calc(85% / 6);
  padding: 30px 0px;
  text-align: center;

  img {
    width: 100%;
    aspect-ratio: 1/1;
    object-fit: cover;
    object-position: top;
  }

  h4 {
    color: white;
  }
}
</style>
