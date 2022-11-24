<template>
  <div class="container">
    <div class="container-dim"></div>
  </div>
</template>

<script>
export default {
  name: "MainContentComp",
};
</script>

<style lang="scss" scoped>
.container {
  width: 100%;
  background-color: black;
  position: relative;
  z-index: 1;
  align-items: center;
}

.container-dim {
  width: 100%;
  padding: 150px;
  background-image: url("../assets/img/jumbotron.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}

.container-card {
  width: 80%;
  margin: auto;
  padding: 20px;
  background-color: black;

  img {
    width: calc(100% / 6);
    height: calc(100% / 2);
  }
}
</style>
