<template>
    <div class="container-header">
        <img src="../assets/img/dc-logo.png" alt="">
        <ul class="container-link">
            <li><a href="#">Charatters</a>
            </li>
            <li><a class="active" href="#">Comics</a>
            </li>
            <li><a href="#">Movies</a>
            </li>
            <li><a href="#">Tv</a>
            </li>
            <li><a href="#">Games</a>
            </li>
            <li><a href="#">Collectibles</a>
            </li>
            <li><a href="#">Videos</a>
            </li>
            <li><a href="#">Fans</a>
            </li>
            <li><a href="#">News</a>
            </li>
            <li><a href="#">Shop</a>
            </li>
        </ul>
    </div>
</template> 
<script>

</script>
<style lang="scss" scoped>
    @import "../assets/scss/partials/_variables.scss";
    @import "../assets/scss/partials/_commons.scss";

    .container-header {
        display: flex;
        width: 80%;
        margin: 0 auto;
        justify-content: center;
        justify-content: space-between;
        align-items: center;
    }
    .container-link {
        display: flex;
        list-style-type: none;
        li {
            height: 100%;
            padding:  5px 5px 0 5px;
            border-bottom:3px solid white;
            &:hover,
            &:active {
                display: block;
                border-bottom: 3px solid rgb(12,124,236);
                width: 100%;
                margin: 0 auto;
                }
                a {
                    display: block;
                    text-decoration: none;
                    color: black;
                    font-size: 0.7em;
                    font-weight: bold;
                    text-transform: uppercase;
                    padding: 6em 0.5em;
                    height: 90%;
                    &:hover,
                    &:active,
                    &.active {
                        color: $text-bg-color-blue;
                }
            }
            .line-blue {
                border:1px solid white;
            }
        }
    }
</style>