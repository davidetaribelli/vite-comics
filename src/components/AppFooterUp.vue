<script>
export default {
    name: "AppFooterUp",
}
</script>

<template>
    <div class="container">
        <div class="row justify-content-between">
            <div class="col-5 p-2">
                <div class="row text-white">
                    <div class="col-4">
                        <ul class="my-3">
                            <h5>DC COMICS</h5>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                        <ul class="my-3">
                            <h5>SHOP</h5>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>

                    <div class="col-4">
                        <ul class="my-3">
                            <h5>DC</h5>
                            <li>Terms Of Use</li>
                            <li>Privacy policy (New)</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Subscriptions</li>
                            <li>Talent workshops</li>
                            <li>CPSC Certificates</li>
                            <li>Ratings</li>
                            <li>Shop Help</li>
                            <li>Contact Us</li>
                        </ul>
                    </div>

                    <div class="col-4">
                        <ul class="my-3">
                            <h5>SITES</h5>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Vista</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="col-6">
                <div class="img"></div>
            </div>
        </div>
    </div>
</template>


<style scoped lang="scss">
li {
    cursor: pointer;
    list-style: none;
    color: #787373;
    font-size: 13px;

    &:hover {
        color: #0282f9;
    }
}

.col-6>.img {
    height: 100%;
    background-image: url(img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: 0;
}
</style>
