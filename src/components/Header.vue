<template>
    <div class="container-header">
        <img src="../assets/img/dc-logo.png" alt="">
        <ul class="container-link">
            <li><a href="#">Charatters</a>
                <hr class="line-blue">
            </li>
            <li><a class="active" href="#">Comics</a>
                <hr class="line-blue">
            </li>
            <li><a href="#">Movies</a>
                <hr class="line-blue">
            </li>
            <li><a href="#">Tv</a>
                <hr class="line-blue">
            </li>
            <li><a href="#">Games</a>
                <hr class="line-blue">
            </li>
            <li><a href="#">Collectibles</a>
                <hr class="line-blue">
            </li>
            <li><a href="#">Videos</a>
                <hr class="line-blue">
            </li>
            <li><a href="#">Fans</a>
                <hr class="line-blue">
            </li>
            <li><a href="#">News</a>
                <hr class="line-blue">
            </li>
            <li><a href="#">Shop</a>
                <hr class="line-blue">
            </li>
        </ul>
    </div>
</template> 
<script>

</script>
<style lang="scss" scoped>
    @import "../assets/scss/partials/_variables.scss";
    .container-header {
        display: flex;
        width: 80%;
        margin: 0 auto;
        height: 150px;
        justify-content: center;
        justify-content: space-between;
        align-items: center;
    }
    .container-link {
        display: flex;
        list-style-type: none;
        li {
            height: 100%;
            margin: 5px;
            &:hover .line-blue ,
            &:active .line-blue {
                display: block;
                border: 1px solid rgb(12,124,236);
                width: 100%;
                margin: 0 auto;
                }
            a {
                display: block;
                text-decoration: none;
                color: black;
                font-size: 0.7em;
                text-transform: uppercase;
                padding: 5em 0.5em;
                height: 90%;
                border-bottom:1px solid white ;
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