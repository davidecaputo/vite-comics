<template>
    <main>
        <div class="bg-dark p-4">
            <div class="container py-5 d-flex flex-wrap gap-5">
                <CardsComponent v-for="(card, index) in data" :key="index" :data="card" />
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
    import CardsComponent from './CardsComponent.vue';
    import { comics } from '../data/dc-comics';

    export default {
    data() {
        return {
            data: comics,
        };
    },
    components: { 
        CardsComponent 
    }
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