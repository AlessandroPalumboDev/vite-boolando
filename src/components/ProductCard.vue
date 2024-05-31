<script>

export default {
    name: 'ProductCard',
    props: ['element']
}

</script>


<template>
        <div class="prodotto position-relative">
        <img class="img-prodotto" :src="`../../public/img/${element.frontImage}`" alt="prodotto-1">
        <img class="img-prodotto-secondo" :src="`../../public/img/${element.backImage}`" alt="prodotto-1-bis">
        <input class="cuore position-absolute" type="button" value="&hearts;">
        <div class="etichette">
            <span class="percentuale-sconto" v-for="etichetta in element.badges" v-show="etichetta.type === 'discount'">
                {{ etichetta.value }}
            </span>
        <span class="sostenibilità" v-for="etichetta in element.badges" v-show="etichetta.type === 'tag'">
            {{ etichetta.value }}
        </span>
        </div>
    </div>
    <div class="testo-prodotto">
        <span>{{element.brand}}</span>
        <h3>{{element.name}}</h3>
        <span class="prezzo-scontato" >{{element.price}}&euro;</span>  
        <span class="prezzo-originale">{{}}</span>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/styles/main.scss';
</style>