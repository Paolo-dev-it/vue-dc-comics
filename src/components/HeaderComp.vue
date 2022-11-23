<template>
  <div class="container">
    <div>
      <img class="img-style" src="../assets/img/dc-logo.png" alt="Logo DC">
    </div>
    <div>
      <ul class="ul-list-flex">
        <li class="list-style">characters</li>
        <li class="list-style">comics</li>
        <li class="list-style">movies</li>
        <li class="list-style">tv</li>
        <li class="list-style">games</li>
        <li class="list-style">collectibles</li>
        <li class="list-style">videos</li>
        <li class="list-style">fans</li>
        <li class="list-style">news</li>
        <li class="list-style">shop</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderComp',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container {
  background-color: white;
  display: flex;
  text-align: center;
  align-items: center;
  justify-content: space-between;
  width: 80%;
  margin: 0 auto;
  padding: 10px;
}

.img-style {
  width: 80%;
}

.ul-list-flex{
  display: flex;
}

.list-style {
  margin: 7px;
  font-size: 0.8rem;
  list-style: none;
  text-transform: uppercase;
  font-weight: bold;
}
</style>
