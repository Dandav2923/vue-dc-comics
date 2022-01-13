<template>
    <div class="container-main">
        <div class="container-main-top">

        </div>
        <div class="container-main-bottom">
            <ul class="container-list">
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>Digital Comics</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <span>Dc merchandise</span>
                </li>
                <li>
                    <img class="small-img" src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <span>subscriptions</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <span>Comic shop locator</span>
                </li>
                <li>
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <span>dc power visa</span>
                </li>
            </ul>
        </div>
    </div>
</template> 
<script>

</script>
<style lang="scss" scoped>
    @import "../assets/scss/partials/_variables.scss";
    .container-main {
        height: 350px;
    }
    .container-main-top {
        height: 150px;
        background-color: black;
    }
    .container-main-bottom {
        height: 200px;
        background-color: $text-bg-color-blue;
        .container-list{
            display: flex;
            list-style-type:none;
            justify-content: center;
            justify-content: space-around;
            align-items: center;
            width: 80%;
            height: 100%;
            margin: 0 auto;
            li {
                display: flex;
                justify-content: center;
                align-items: center;
                color: white;
                text-transform: uppercase;
                img {
                    width: 3em;
                    height: auto;
                }
                .small-img {
                    width: 2em;
                    height: auto;
                }
                span {
                    font-size: 0.8em;
                    padding: 0.5em;
                }
            }
        }
    } 
</style>