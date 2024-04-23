<template>
    <section class="position-relative">
        <nav id="navbarFix" class="navbar navbar-light position-absolute z-2">
            <div class="container p-5">
                <a class="navbar-brand">
                    <img src="../assets/img/logo.png" alt="">
                </a>
                <div class="justify-content-between d-flex text-white fw-bold gap-4">
                    <p><a href="#" class="link-light link-offset-2 link-underline-opacity-0 link-underline-opacity-100-hover">ABOUT</a></p>
                    <p><a href="#" class="link-light link-offset-2 link-underline-opacity-0 link-underline-opacity-100-hover">SERVICES</a></p>
                    <p><a href="#" class="link-light link-offset-2 link-underline-opacity-0 link-underline-opacity-100-hover">YACHTS</a></p>
                    <p><a href="#" class="link-light link-offset-2 link-underline-opacity-0 link-underline-opacity-100-hover">RESERVATIONS</a></p>
                    <p><a href="#" class="link-light link-offset-2 link-underline-opacity-0 link-underline-opacity-100-hover">BLOG</a></p>
                    <p><a href="#" class="link-light link-offset-2 link-underline-opacity-0 link-underline-opacity-100-hover">CONTACTS</a></p>
                </div>
                <form class="d-flex input-group w-auto">
                <span><i class="fa-solid fa-magnifying-glass"></i></span>
                </form>
            </div>
        </nav>
        <div id="imgTextContainer" class="text-white position-absolute z-2">
            <h1 id="imgTitle" class="">QuickWind</h1>
            <p class="fs-3 w-75">all kinds of boats, yacht charters and sailing destinations for hobbyist yachtsmen and women!</p>
            <button type="button" class="btn btn-outline-light">Learn More</button>
        </div>
        <div id="carouselExampleIndicators" class="carousel slide">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="../assets/img/bg1-1.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="../assets/img/bg2.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="../assets/img/bg3.jpg" class="d-block w-100" alt="...">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;
    i {
        color: $second-color;
    }
    #imgTitle {
        font-size: 12rem;
    }
    #imgTextContainer {
        top: 35%;
        left: 20%;
    }
    #navbarFix {
        top: 0;
        left: 0;
        right: 0;
    }
    
</style>