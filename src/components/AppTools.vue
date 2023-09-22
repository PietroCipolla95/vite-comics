<script>

export default {
    name: 'AppTools'
}

</script>
<template>
    <section class="py-5">
        <div class="wrapper d-flex my_container justify-content-between align-items-center">
            <div class="col-2">
                <a href="#">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </a>
            </div>
            <div class="col-2">
                <a href="#">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="" srcset="">
                    <span>DC MERCHANDISE</span>
                </a>
            </div>
            <div class="col-2">
                <a href="#">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="" srcset="">
                    <span>SUBSCRIPTION</span>
                </a>
            </div>
            <div class="col-2">
                <a href="#">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="" srcset="" class="comic_shop">
                    <span>COMIC SHOP LOCATION</span>
                </a>
            </div>
            <div class="col-2">
                <a href="#">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="" srcset="">
                    <span>DC POWER VISA</span>
                </a>
            </div>
        </div>
    </section>
</template>



<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

section {

    background-color: $dc-primary;

    img {
        width: 20%;
    }

    .comic_shop {
        width: 15%;
    }

    span {
        font-size: .8rem;
        padding-left: .6rem;
        color: white;
    }

}
</style>