<script>
export default {
    name: "AppMainUp",
    props: [
        "cards"
    ],
    data() {
        return {

        }
    }
}
</script>

<template>
    <div class="container-fluid p-0">
        <div class="row">
            <img class="p-0" src="/img/jumbotron.jpg" alt="jumbotron">
        </div>
    </div>


    <div class="container">
        <div class="row">
            <div class="col-12 bg-dark d-flex align-items-center p-4">
                <div class="currentSeries text-white p-2">
                    <span> CURRENT SERIES</span>
                </div>
                <div id="contentHere" class="text-white d-flex flex-wrap justify-content-between align-items-center p-3">
                    <div v-for="card in cards" class="card_">
                        <img :src="card.thumb" alt="card.type">
                        <small>{{ card.series }}</small>
                    </div>
                </div>
            </div>
            <div class="load_ text-center">
                <button class="py-1 px-4 border-0 m-4 text-white"> LOAD MORE </button>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.container-fluid {
    height: 16rem;

    .row {
        height: 100%;

        img {
            height: 100%;
            object-fit: cover;
            object-position: top;
        }
    }
}

.col-12 {
    position: relative;

    .currentSeries {
        position: absolute;
        top: -1.4rem;
        font-weight: 700;
        background-color: #0282f9;
    }
}

.card_ {
    width: calc(100vw / 8 - 2em);
    height: calc(100vw / 8 - 2em);
    margin: 1em;

    img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        object-position: top;
    }
}

.load_>button {
    cursor: pointer;
    background-color: #0282f9;
}
</style>