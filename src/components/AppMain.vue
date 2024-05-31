<script>
import ProductsList from './ProductsList.vue';

export default {
    name: 'AppMain',


    components:{
        ProductsList,
    },

    
}
</script>


<template>
    <div class="container">
        <div class="row d-flex a-items-center j-c-center">
            <ProductsList />
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/styles/main.scss';
</style>