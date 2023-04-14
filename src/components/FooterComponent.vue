<template>
    <footer>
        <div class="footer-up">
            <div class="container py-5 text-white d-flex gap-4">
                <div>
                    <ul>
                        <li class="text-uppercase fw-bold fs-5">Dc comics</li>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                    <ul>
                        <li class="text-uppercase fw-bold fs-5">Shop</li>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>
                <ul>
                    <li class="text-uppercase fw-bold fs-5">Dc</li>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
                <ul>
                    <li class="text-uppercase fw-bold fs-5">Sites</li>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
                <div class="logo"></div>
            </div>
        </div>
        <div class="footer-down">
            <div class="container">
                <div><span>Sign-up now!</span></div>
                <div class="">
                    <span>Follow us</span>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    .footer-up{
        background-image: url(../../public/img/footer-bg.jpg);
        background-size: cover;
    }

    .logo{
        width: 30%;
        background-image: url(../../public/img/dc-logo-bg.png);
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
    }
</style>