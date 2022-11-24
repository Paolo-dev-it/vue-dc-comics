<template>
    <div class="container">
        <div class="container-dim">
            <div>
                <ul class="ul-style">
                    <h4>dc comics</h4>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <ul class="ul-style">
                    <h4>shop</h4>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>
            <div>
                <ul class="ul-style">
                    <h4>dc</h4>
                    <li>Term Of Use</li>
                    <li>Privacy Policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>
            <div>
                <ul class="ul-style">
                    <h4>sites</h4>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>

            <div class="img-cont">
                <img class="img-style" src="../assets/img/dc-logo-bg.png" alt="">
            </div>
            
            
            
        </div>
        
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
.container {
        width: 100%;
        padding: 30px;
        background-image: url('../assets/img/footer-bg.jpg');
    }

    .container-dim {
        width: 80%;
        margin: 0 auto;
        display: flex;
        position: relative;
    }

    .ul-style {
        color: white;
        list-style: none;
        margin-left: 10px;
        
        h4{
            text-transform: uppercase;
            margin-bottom: 15px;
        }
        li{
            color: gray;
            font-size: 0.7rem;
            line-height: 20px;
        }
    }

    .img-cont{
        display: flex;
        align-items: center;
        z-index: 0;
    }

    .img-style {
        width: 40%;
        position: absolute;
        right: 0;
    }
</style>