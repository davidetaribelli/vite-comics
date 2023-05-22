<script>
export default {
    name: "AppMainDown",
}
</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col-12 d-flex align-items-center justify-content-evenly p-5 text-white">
                <div class="option p-3">
                    <img src="/img/buy-comics-digital-comics.png" alt="digital-comics">
                    <span class="mx-3">DIGITAL COMICS</span>
                </div>
                <div class="option">
                    <img src="/img/buy-comics-merchandise.png" alt="merch">
                    <span class="mx-3">DC MERCHANDISE</span>
                </div>
                <div class="option">
                    <img src="/img/buy-comics-subscriptions.png" alt="sub">
                    <span class="mx-3">SUBSCRIPTION</span>
                </div>
                <div class="option">
                    <img src="/img/buy-comics-shop-locator.png" alt="shop">
                    <span class="mx-3">COMIC SHOP LOCATOR</span>
                </div>
                <div class="option">
                    <img class="visa" src="/img/buy-dc-power-visa.svg" alt="visa">
                    <span class="mx-3">DC POWER VISA</span>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.col-12 {
    min-height: 6.5rem;
}

span {
    font-size: 10px;
}

img {
    height: 50px;
}

.visa {
    height: 40p;
}
</style>