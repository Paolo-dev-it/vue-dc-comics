<template>
    <div class="container">

        <MainContentComp />
        <MainMenuComp/>

    </div>
</template>

<script>
    import MainContentComp from './MainContentComp.vue'
    import MainMenuComp from './MainMenuComp.vue'

    export default {
        name: "MainComp",
        components: {
            MainContentComp,
            MainMenuComp,
        }
    } 
</script>

<style lang="scss" scoped>

</style>