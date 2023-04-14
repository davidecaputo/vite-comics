<template>
    <main>
        <div class="bg-dark">
            <div class="container p-5">
                <span class="text-white fs-2">-- Content goes here --</span>
            </div>
        </div>
        <div class="bg-primary">
            <div class="container">
                <ul class="d-flex align-items-center p-5 text-white text-uppercase gap-3">
                    <li>
                        <img src="../../public/img/buy-comics-digital-comics.png" alt="" class="pe-3">
                        <span>Digital comics</span>
                    </li>
                    <li>
                        <img src="../../public/img/buy-comics-merchandise.png" alt="" class="pe-3">
                        <span>Dc merchandise</span>
                    </li>
                    <li>
                        <img src="../../public/img/buy-comics-subscriptions.png" alt="" class="pe-3">
                        <span>Subscription</span>
                    </li>
                    <li>
                        <img src="../../public/img/buy-comics-shop-locator.png" alt="" class="w-25 pe-3">
                        <span>Comic shop locator</span>
                    </li>
                    <li>
                        <img src="../../public/img/buy-dc-power-visa.svg" alt="" class="pe-3">
                        <span>Dc power visa</span>
                    </li>
                </ul>
            </div>
        </div>
    </main>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    li{
        width: 30%;

        & img{
            width: 30%;
        }
    }
</style>