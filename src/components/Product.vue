<template>
        <div class="product">
            <div class="container-img">
                <img 
                    :src="thumb"
                    :alt="alt"
                >
            </div>
            <h2>{{series}}</h2>
        </div>
</template>

<script>
    export default {
        name: "Product",
        props: ['thumb', 'alt', 'series'],
    }
</script>

<style lang="scss">
    .product {
        flex-basis: calc(( 100% / 6) - 0.4em);
        margin: 0.2em;
        padding: 1em;
        .container-img {
            overflow: hidden;
            width: 200px;
            height: 200px;
            img{
                width: 100%;
            }
        }
        h2 {
            width: 100%;
            color: white;
            font-size: 0.7em;
            text-transform: uppercase;
            padding: 0.8em 0 0 0;
        }
    }
</style>