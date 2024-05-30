<script>
export default {
    name: 'AppMain'
}
</script>


<template>
    <div class="container">
        <div class="row d-flex a-items-center j-c-center">
            <!-- PRIMO PRODOTTO -->
            <div class="col33">
                <div class="prodotto position-relative">
                    <img class="img-prodotto" src="../../public/img/1.webp" alt="prodotto-1">
                    <img class="img-prodotto-secondo" src="../../public/img/1b.webp" alt="prodotto-1-bis">
                    <input class="cuore position-absolute" type="button" value="&hearts;">
                    <div class="etichette"><span class="percentuale-sconto">50%</span><span
                            class="sostenibilità">Sostenibilit&agrave;</span></div>
                </div>
                <div class="testo-prodotto">
                    <span>Levi's</span>
                    <h3>RELAXED FIT TEE UNISEX</h3>
                    <span class="prezzo-scontato">14,99&euro;</span> <span class="prezzo-originale">29,99&euro;</span>
                </div>
            </div>
            <!-- SECONDO PRODOTTO -->
            <div class="col33">
                <div class="prodotto position-relative">
                    <img class="img-prodotto" src="../../public/img/2.webp" alt="prodotto-2">
                    <img class="img-prodotto-secondo" src="../../public/img/2b.webp" alt="prodotto-2-bis">
                    <input class="cuore position-absolute" type="button" value="&hearts;">
                    <div class="etichette"><span class="percentuale-sconto">30%</span></div>
                </div>
                <div class="testo-prodotto">
                    <span>Guess</span>
                    <h3>ROSES TEE</h3>
                    <span class="prezzo-scontato">20,99&euro;</span> <span class="prezzo-originale">29,99&euro;</span>
                </div>
            </div>
            <!-- TERZO PRODOTTO -->
            <div class="col33">
                <div class="prodotto position-relative">
                    <img class="img-prodotto" src="../../public/img/3.webp" alt="prodotto-3">
                    <img class="img-prodotto-secondo" src="../../public/img/3b.webp" alt="prodotto-3-bis">
                    <input class="cuore position-absolute" type="button" value="&hearts;">
                    <div class="etichette"><span class="percentuale-sconto">30%</span></div>
                </div>
                <div class="testo-prodotto">
                    <span>Come Zucchero Filato</span>
                    <h3>VOGLIA DI COLORI PASTELLO</h3>
                    <span class="prezzo-scontato">129,99&euro;</span> <span class="prezzo-originale">184,99&euro;</span>
                </div>
            </div>
            <!-- QUARTO PRODOTTO -->
            <div class="col33">
                <div class="prodotto position-relative">
                    <img class="img-prodotto" src="../../public/img/4.webp" alt="prodotto-4">
                    <img class="img-prodotto-secondo" src="../../public/img/4b.webp" alt="prodotto-4-bis">
                    <input class="cuore position-absolute" type="button" value="&hearts;">
                    <div class="etichette"><span class="percentuale-sconto">50%</span><span
                            class="sostenibilità">Sostenibilit&agrave;</span></div>
                </div>
                <div class="testo-prodotto">
                    <span>Levi's</span>
                    <h3>TEE UNISEX</h3>
                    <span class="prezzo-scontato">14,99&euro;</span> <span class="prezzo-originale">29,99&euro;</span>
                </div>
            </div>
            <!-- QUINTO PRODOTTO -->
            <div class="col33">
                <div class="prodotto position-relative">
                    <img class="img-prodotto" src="../../public/img/5.webp" alt="prodotto-5">
                    <img class="img-prodotto-secondo" src="../../public/img/5b.webp" alt="prodotto-5-bis">
                    <input class="cuore position-absolute" type="button" value="&hearts;">
                </div>
                <div class="testo-prodotto">
                    <span>Maya Deluxe</span>
                    <h3>STRIPE BODICE</h3>
                    <span class="prezzo-scontato">99,99&euro;</span>
                </div>
            </div>
            <!-- SESTO PRODOTTO -->
            <div class="col33">
                <div class="prodotto position-relative">
                    <img class="img-prodotto" src="../../public/img/6.webp" alt="prodotto-6">
                    <img class="img-prodotto-secondo" src="../../public/img/6b.webp" alt="prodotto-6-bis">
                    <input class="cuore position-absolute" type="button" value="&hearts;">
                    <div class="etichette"><span class="sostenibilità">Sostenibilit&agrave;</span></div>
                </div>
                <div class="testo-prodotto">
                    <span>Esprit</span>
                    <h3>MAGIONE - BLACK</h3>
                    <span class="prezzo-scontato">29,99&euro;</span>
                </div>
            </div>
        </div>
    </div>
</template>