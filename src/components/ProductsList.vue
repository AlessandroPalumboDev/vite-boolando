<script>
import products from '../data/db.json';


export default{
    name: 'ProductsList',
    data(){
        return{
            products,
}
        }
    };

</script>

<template>
<div class="col33" v-for="(element, index) in products" :key="index">

    <div class="prodotto position-relative">
        <img class="img-prodotto" :src="product.frontImage" alt="prodotto-1">
        <img class="img-prodotto-secondo" :src="product.backImage" alt="prodotto-1-bis">
        <input class="cuore position-absolute" type="button" value="&hearts;">
        <div class="etichette">
            <span class="percentuale-sconto">{{ element.badges }}</span>
        <span class="sostenibilità">{{ element.badges }}</span>
        </div>
    </div>
    <div class="testo-prodotto">
        <span>{{element.brand}}</span>
        <h3>{{element.name}}</h3>
        <span class="prezzo-scontato">14,99&euro;</span>  <span class="prezzo-originale">{{element.price}}&euro;</span>
    </div>
</div>

</template>

<style lang="scss" scoped>
@use '../assets/styles/main.scss';
</style>