<template>
    <div class="footer">
        <div class="container-footer-bis">
        <div class="container-footer-bottom">
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
        <div class="container-footer">
            <div class="container-links">
                <div class="container-left">
                    <h2>DC Comics</h2>
                    <ul class="menu">
                        <li><a href="">Characters</a></li>
                        <li><a href="">Comics</a></li>
                        <li><a href="">Movies</a></li>
                        <li><a href="">TV</a></li>
                        <li><a href="">Games</a></li>
                        <li><a href="">Videos</a></li>
                        <li><a href="">News</a></li>
                        <li>
                            <ul class="menu">
                            <li><h2>DC Shop</h2>
                            <li><a href="">Shop DC</a></li>
                            <li><a href="">Shop DC Collectibles</a></li>
                            </ul>
                        </li>
                    </ul>
                </div>
                <div class="container-center">
                    <h2>DC</h2>
                    <ul class="menu">
                        <li><a href="">Terms of Use</a></li>
                        <li><a href="">Privacy Policy (New)</a></li>
                        <li><a href="">Ad Choices</a></li>
                        <li><a href="">Advertising</a></li>
                        <li><a href="">Jobs</a></li>
                        <li><a href="">Subscriptions</a></li>
                        <li><a href="">CPSC Certificates</a></li>
                        <li><a href="">Ratings</a></li>
                        <li><a href="">Shop Help</a></li>
                        <li><a href="">Contact Us</a></li>
                    </ul>
                </div>
                <div class="container-right">
                    <h2>Sites</h2>
                    <ul class="menu">
                        <li><a href="">DC</a></li>
                        <li><a href="">DC UNIVERSE INFINITE</a></li>
                        <li><a href="">DC Kids</a></li>
                        <li><a href="">DC Shop</a></li>
                        <li><a href="">MAD Magazine</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template> 

<script>

</script>

<style lang="scss" scoped>
    @import "../assets/scss/partials/_variables.scss";
    .container-footer-bottom {
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
    .footer {
        background-image: url(../assets/img/footer-bg.jpg);
        .container-footer {
            height: 90%;
            background-image: url(../assets/img/dc-logo-bg.png);
            background-repeat: no-repeat;
            background-position: right center;
            padding: 50px 0 ;
            .container-links {
                width: 80%;
                margin: 0 auto;
                display: flex;
                h2 {
                    color: white;
                }
                .menu {
                    list-style: none;
                    margin: 10px 30px 0 0;
                    li {
                        margin: 5px 0;
                        a{
                            color: #959595;
                            text-decoration: none;
                            &:hover,
                            &:active,
                            &.active {
                                color: $text-bg-color-blue;
                            }
                        }
                    }
                }
            }
        }
    }
</style>