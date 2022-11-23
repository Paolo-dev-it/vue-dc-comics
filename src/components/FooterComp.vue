<template>
    <div class="container">

        <FooterListComp />
        <FooterCtaComp />

    </div>
</template>

<script>
import FooterListComp from './FooterListComp.vue'
import FooterCtaComp from './FooterCtaComp.vue'

export default {
    name: "FooterComp",
    components: {
        FooterListComp,
        FooterCtaComp,
    }
} 
</script>

<style lang="scss" scoped>
.container {
    
}
</style>