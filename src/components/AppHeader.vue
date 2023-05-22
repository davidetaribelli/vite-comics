<script>
export default {
    name: "AppHeader",
    data() {
        return {
            listNav: [
                { option: 'CHARACTERS' },
                { option: 'COMICS' },
                { option: 'MOVIES' },
                { option: 'TV' },
                { option: 'GAMES' },
                { option: 'COLLECTIBLES' },
                { option: 'VIDEOS' },
                { option: 'FANS' },
                { option: 'NEWS' },
                { option: 'SHOP' }
            ],
        }
    },
    mounted() {

    }
}
</script>

<template>
    <div class="container">
        <div class="row justify-content-between">
            <div class="col-4 d-flex align-items-center">
                <img src="/img/dc-logo.png" alt="">
            </div>
            <div class="col-8 d-flex align-items-center justify-content-evenly">
                <a v-for="list, i in listNav" class="text-decoration-none text-black mx-3 d-flex align-items-center"
                    href="#">
                    {{ list.option }}
                </a>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
img {
    height: 80%;
}

div>a {
    font-size: 10px;
    height: 100%;

    &:hover {
        border-bottom: 5px solid #0282f9;
    }
}
</style>