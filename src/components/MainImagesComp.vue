<template>
  <div class="container">
    <div class="container-card">
      <div>
        <img :src="filmsDetails.thumb" alt="" />
      </div>
    </div>
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
.container-card {
  width: 80%;
  margin: 0 auto;
  display: flex;
  background-color: black;
}

.container {
  background-color: black;
}
</style>
