<script>
export default {
    name: "AppHeader",
}
</script>

<template>
    <div class="container">
        <div class="row justify-content-between p-2">
            <div class="col-4 d-flex align-items-center">
                <img src="./img/dc-logo.png" alt="">
            </div>
            <div class="col-8 d-flex align-items-center justify-content-evenly">
                <a class="text-decoration-none text-black mx-3" href="#">CHARACTERS</a>
                <a class="text-decoration-none text-black mx-3" href="#">COMICS</a>
                <a class="text-decoration-none text-black mx-3" href="#">MOVIES</a>
                <a class="text-decoration-none text-black mx-3" href="#">TV</a>
                <a class="text-decoration-none text-black mx-3" href="#">GAMES</a>
                <a class="text-decoration-none text-black mx-3" href="#">COLLECTIBLES</a>
                <a class="text-decoration-none text-black mx-3" href="#">VIDEOS</a>
                <a class="text-decoration-none text-black mx-3" href="#">FANS</a>
                <a class="text-decoration-none text-black mx-3" href="#">NEWS</a>
                <a class="text-decoration-none text-black mx-3" href="#">SHOP</a>
            </div>
        </div>
    </div>
</template>

<style scoped>
img {
    height: 80%;
}

div>a {
    font-size: 10px;
}
</style>