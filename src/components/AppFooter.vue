<script>
export default {
    name: 'AppFooter'
}
</script>


<template>
    <div class="container">
        <div class="row-header d-flex">
            <div class="col50">
                <a href="#">
                    <h4>Boolando s.r.l.</h4>
                </a>
                <ul class="d-flex">
                    <li><a href="#">Informazioni legali</a></li>
                    <li><a href="#">Informartiva sulla privacy</a></li>
                    <li><a href="#">Diritto di recesso</a></li>
                </ul>
            </div>
            <div class="col50 txt-a-right">
                <h4 class="color-white">Trovaci anche su</h4>
                <ul class="d-flex j-c-right">
                    <li><a href="#"><img class="img-piccole" src="../../public/img/twitter.webp" alt="twitter"></a></li>
                    <li><a href="#"><img class="img-piccole" src="../../public/img/facebook.png" alt="facebook"></a></li>
                    <li><a href="#"><img class="img-piccole" src="../../public/img/Instagram.png" alt="Instagram"></a></li>
                    <li><a href="#"><img class="img-piccole" src="../../public/img/pinterest.webp" alt="pinterest"></a></li>
                    <li><a href="#"><img class="img-piccole" src="../../public/img/youtube.png" alt="youtube"></a></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped>
li {
    margin-top: 5px;
    margin-right: 10px;
}


.color-white {
    color: white;
}

a {
    text-decoration: none;
    color: white;
}

.img-piccole {
    width: 20px;
    height: 20px;
    filter: brightness(0) saturate(100%) invert(100%) sepia(3%) saturate(11%) hue-rotate(61deg) brightness(104%) contrast(100%);
}




/* CLASSI DI LAYOUT */
.container {
    max-width: 1200px;
    margin: 0 auto;
}

.row-header {
    width: 100%;
}

.col50 {
    width: 50%;
}

/* CLASSI DI UTILITY */
.d-flex {
    display: flex;
}

.j-c-right {
    justify-content: right;

}

.txt-a-right {
    text-align: right;
}
</style>