<script>
export default {
    name: "AppMainUp",
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
            <div class="col-12 bg-dark d-flex align-items-center">
                <div id="contentHere" class="text-white">

                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.container-fluid {
    height: 16rem;
}

.container-fluid>.row {
    height: 100%;
}

.container-fluid>.row>img {
    height: 100%;
    object-fit: cover;
    object-position: top;
}

.col-12 {
    height: 5rem;
}

#contentHere {
    height: 100%;

}
</style>