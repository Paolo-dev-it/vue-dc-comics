<template>
    <div class="container">
        <div class="container-dim">
            <h3> Content goes here </h3>
        </div>
        
    </div>
</template>

<script>
    export default {
    name: 'MainContentComp',
    }
</script>

<style lang="scss" scoped>
.container{
    width: 100%;
    background-color: black;
}

.container-dim{
    width: 80%;
    margin: auto;
    padding: 30px;
    background-color: black;
}

h3 {
    color: white;
}
</style>