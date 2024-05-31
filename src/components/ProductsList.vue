<script>
import products from '../data/db.json';
import ProductCard from './ProductCard.vue';


export default{
    name: 'ProductsList',
    data(){
        return{
            products: products.products,
        }
    },

    components:{
        ProductCard,
    }

};

</script>

<template>
<div class="col33" v-for="(element, index) in products" :key="index">

<ProductCard :element="element"/>

</div>
</template>


<style lang="scss" scoped>
@use '../assets/styles/main.scss';
</style>