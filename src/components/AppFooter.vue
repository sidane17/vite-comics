
<script>
export default{
    name:"AppFooter"
}
</script>



<template>
<footer>
    <div class="w-100 bg-primary h">
        <div class="container d-flex justify-content-center align-items-center text-light" style="height: 100%;">
            <div class="containerImg d-flex align-items-center justify-content-center"><img width="20%" src="/img/buy-comics-digital-comics.png" alt=""><span class="ms-1 w">DIGITAL COMICS</span></div>
            <div class="containerImg d-flex align-items-center justify-content-center"><img width="20%" src="/img/buy-comics-merchandise.png" alt=""><span class="ms-1 w">DIGITAL COMICS</span></div>
            <div class="containerImg d-flex align-items-center justify-content-center"><img width="20%" src="/img/buy-comics-subscriptions.png" alt=""><span class="ms-1 w">DIGITAL COMICS</span></div>
            <div class="containerImg d-flex align-items-center justify-content-center"><img width="20%" src="/img/buy-comics-shop-locator.png" alt=""><span class="ms-1 w">DIGITAL COMICS</span></div>
            <div class="containerImg d-flex align-items-center justify-content-center"><img width="20%" src="/img/buy-dc-power-visa.svg" alt=""><span class="ms-1 w">DIGITAL COMICS</span></div>
        </div>
    </div> 
    <div class="p d-flex align-items-center ">
        <div class="container d-flex justify-content-between align-items-center">
            <div class="col-7 footerF d-flex ">
                <div class="col-3 d-flex flex-column">
                    <h2 class="fs-4 mb-2">DC COMICS</h2>
                    <span>Character</span>
                    <span>Comics</span>
                    <span>Movies</span>
                    <span>TV</span>
                    <span>Games</span>
                    <span>Videos</span>
                    <span class="mb-2">News</span>
                    <h2 class="mb-2">SHOP</h2>
                    <span>Shop DC</span>
                    <span>Shop DC Collectibles</span>

                    
                </div>
                <div class="col-2 d-flex flex-column">
                    <h2 class="fs-2">DC</h2>
                    <span>Terms Of Use</span>
                    <span>Privacy policy (New)</span>
                    <span>Ad Choises</span>
                    <span>Advertising</span>
                    <span>Jobs</span>
                    <span>Subscription</span>
                    <span>Talent Workshops</span>
                    <span>CPSC Certificates</span>
                    <span>Rating</span>
                    <span>Shop Help</span>
                    <span>Contact Us</span>
                </div>
                <div class="col-2 d-flex flex-column">
                    <h2 class="fs-3">SITES</h2>
                    <span>DC</span>
                    <span>MAD Magazine</span>
                    <span>DC Kids</span>
                    <span>DC Universe</span>
                    <span>DC Power Visa</span>
                </div>
            </div>
            <div><img src="/img/dc-logo-bg.png" alt=""></div>
        </div>
    </div>
    <div class="k">
        <div class="container d-flex justify-content-between align-items-center">
            <a class="text-light ">SIGN-UP NOW!</a>
            <div class="d-flex ">
                <span class="me-2 text-primary d-flex justify-content-between align-items-center fs-6"><b>FOLLOW US</b></span>
                <img class="m-2" src="/img/footer-facebook.png" alt="">
                <img class="m-2" src="/img/footer-twitter.png" alt="">
                <img class="m-2" src="/img/footer-youtube.png" alt="">
                <img class="m-2" src="/img/footer-pinterest.png" alt="">
                <img class="m-2" src="/img/footer-periscope.png" alt="">
            </div>

        </div>
    </div>
</footer>    
</template>



<style scoped>
.h{
    height: 10rem;
}
.containerImg{

}
.p{
    background-image: url(/img/footer-bg.jpg);
    background-color: black;
    height: 25rem;
    width: 100%;
    background-repeat: no-repeat;
    background-size: 100% 100%;
    overflow: hidden;
    color: white;

    
}
.footerF{
    height: fit-content;
}
.w{
    color: white;
}
span{
    color: grey;
}
.k{
    height: 5rem;
    display: flex;
    align-items:center ;
    justify-content: center;
    background-color: rgb(48, 48, 48);
}
a{
    background-color: rgb(48, 48, 48);
    border:3px solid;
    border-color:  rgb(58, 58, 255);
    padding: 0.5rem;
    text-decoration: none;
}
</style>