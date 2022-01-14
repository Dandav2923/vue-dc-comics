<template>
    <div>
        <div class="product">
            <img 
                :class="color"
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
        flex-basis: calc((100%/6) - 0.4em);
        margin: 0.2em;
        padding: 1em;
        img {
            width: 150px;
            height: 150px;
        }
    }

</style>