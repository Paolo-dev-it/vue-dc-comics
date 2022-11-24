<template>
    <div class="container">
        <div class="cont-dim">
            <div>
               <button>sign-up now!</button> 
            </div>
            <div>
                <ul class="ul-style">
                    <span>follow us</span>
                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                    <li><img src="../assets/img/footer-twitter.png" alt=""></li>
                    <li><img src="../assets/img/footer-youtube.png" alt=""></li>
                    <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
                    <li><img src="../assets/img/footer-periscope.png" alt=""></li>
                </ul>
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
    padding: 20px;
    background-color: #303030;
    position: relative;
    z-index: 1;
    display: flex;
    align-items: center;
    }

    .cont-dim {
        width: 80%;
        margin: auto;
        padding: 27px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        button{
            background-color: #303030;
            border: 1px solid #0082F9;
            padding: 10px;
            color: white;
            text-transform: uppercase;
            font-weight: 600;
        }
        
        button:hover {
            background-color: #0082F9;
            border:1px solid #303030; ;
        }
                
    }
        

    .ul-style {
        display: flex;
        list-style: none;
        align-items: center;
        
        span{
            color: #0082F9;
            font-weight: bold;
            text-transform: uppercase;
            margin-right: 15px;
        }
        li{
            margin-right: 15px;
        }
    }
</style>