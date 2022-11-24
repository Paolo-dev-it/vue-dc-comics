<template>
  <div class="container">
    <div>
      <img class="img-style" src="../assets/img/dc-logo.png" alt="Logo DC">
    </div>
    <div class="ul-cont-dim">
      <ul class="ul-list-flex">
        <li class="list-style"><a>characters</a></li>
        <li class="list-style"><a>comics</a></li>
        <li class="list-style"><a>movies</a></li>
        <li class="list-style"><a>tv</a></li>
        <li class="list-style"><a>games</a></li>
        <li class="list-style"><a>collectibles</a></li>
        <li class="list-style"><a>videos</a></li>
        <li class="list-style"><a>fans</a></li>
        <li class="list-style"><a>news</a></li>
        <li class="list-style"><a>shop</a></li>
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
  padding: 20px;
  margin: 0 auto;
  
}

.img-style {
  width: 80%;
  
}

.ul-cont-dim{
  height: 100%;
  
}

.ul-list-flex{
  display: flex;
  height: 100%;
}

.list-style {
  margin-right: 15px;
  font-size: 0.8rem;
  list-style: none;
  text-transform: uppercase;
  font-weight: bold;
  display: flex;
  align-items: center;
  height: 100%;
}

.list-style :hover {
  color: #0082F9;
  border-bottom: 2px solid #0082F9;
}
</style>
