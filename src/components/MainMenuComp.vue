<template>
    <div class="cont-menu">
        <div class="cont-menu-dim">
          <ul class="ul-list-style">
            <li class="list-style">
                <img class="img-style" src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span class="span-style">digital comics</span>
            </li>
            <li class="list-style">
                <img class="img-style" src="../assets/img/buy-comics-merchandise.png" alt="">
                <span class="span-style">dc merchandise</span>
            </li>
            <li class="list-style">
                <img class="img-style" src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span class="span-style">subscription</span>
            </li>
            <li class="list-style">
                <img class="img-style" src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span class="span-style">comic shop locator</span>
            </li>
            <li class="list-style">
                <img class="img-style" src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span class="span-style">dc power visa</span>
            </li>
        </ul>  
        </div>
        
    </div>
</template>

<script>
    export default {
    name: 'MainContentComp',
    
    }
</script>

<style lang="scss" scoped>
.cont-menu {
    width: 100%;
    height: 20vh;
    z-index: 1;
    background-color: #0082F9;
    position: relative;
    z-index: 1;
    display: flex;
    align-items: center;
}

.cont-menu-dim {
    width: 80%;
    margin: auto;
    color: white;
    padding: 30px;
    
}

.ul-list-style {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.list-style {
    list-style: none;
    display: flex;
    justify-content: center;
    align-items: center;
}

.img-style {
    width: 40px;
}

.span-style{
    text-transform: uppercase;
    margin-left: 10px;
    font-size: 0.8rem;
}
</style>