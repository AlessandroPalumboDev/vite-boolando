<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <div class="container">
        <div class="row-header d-flex a-items-center">
            <div class="col25">
                <a class="selezione" href="#">Donna</a>
                <a class="selezione" href="#">Uomo</a>
                <a class="selezione" href="#">Bambino</a>
            </div>
            <div class="col50 txt-a-center">
                <a href="#"><img class="logo" src="../../public/img/boolean-logo.png" alt="logo"></a>
            </div>
            <div class="col25 txt-a-right">
                <a class="selezione" href="#"><img class="img-piccole" src="../../public/img/user.png" alt=""></a>
                <a class="selezione" href="#"><img class="img-piccole" src="../../public/img/like--v1.png" alt=""></a>
                <a class="selezione" href="#"><img class="img-piccole" src="../../public/img/shopping-bag.png" alt=""></a>
            </div>
        </div>
    </div>
</template>

<style scoped>
.selezione {
    margin: 10px;
}

.logo {
    height: 50%;
}

.col50 .logo {
    width: 30%;
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

.col25 {
    width: 25%;
}

.col50 {
    width: 50%;
}

/* CLASSI DI UTILITY */
.d-flex {
    display: flex;
}

.a-items-center {
    align-items: center;
}

.txt-a-right {
    text-align: right;
}

.txt-a-center {
    text-align: center;
}
</style>