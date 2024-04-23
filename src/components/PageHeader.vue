<template>
    <section class="opacity-75">
        <div class="row justify-content-between p-3">
            <div class="col-6">
                <i class="fa-solid fa-location-dot"></i>
                7087 Richmond hwy, Alexandria, VA
                <i class="fa-solid fa-phone ms-5"></i>
                800-2345-6789
            </div>
            <div class="col-6 text-end links-social">
                <i class="fa-brands fa-facebook"></i>
                <i class="fa-brands fa-square-twitter"></i>
                <i class="fa-brands fa-square-instagram"></i>
            </div>
        </div>
    </section>
    <!-- <section class="">
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
    </section> -->
</template>

<script>
    export default {

    }
</script>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;
.fa-solid {
    color: $second-color;
    margin: 0 1rem;
    font-size: 1.5rem;
}
.fa-brands {
    color: $third-color;
    margin: 0 1rem;
    font-size: 1.5rem;
}
</style>