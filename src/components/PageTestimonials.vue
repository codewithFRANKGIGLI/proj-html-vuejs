<template>
    <section class="position-relative pt-5 text-white">
        <img src="../assets/img/bg8.jpg" class="w-100" alt="">
        <div class="row py-5 position-absolute top-0 start-50 translate-middle-x">
            <h1 class="fw-bold p-5 text-center">Testimonials</h1>
            <hr class="pb-5">
            <div id="carouselExampleIndicators" class="carousel slide">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
                </div>
                <div class="carousel-inner">
                    <div class="carousel-item active">

                        <div class="card bg-white bg-opacity-25 m-auto text-white w-75">
                            <div class="row m-5">
                                <div class="col-md-4 d-flex justify-content-end">
                                    <img src="../assets/img/test1.jpg" class="rounded-circle p-3" alt="...">
                                </div>
                                <div class="col-md-8">
                                    <div class="card-body">
                                        <p class="card-text pt-4 fs-4 w-75 position-relative">
                                            <i class="fa-solid fa-quote-right position-absolute opacity-25"></i>
                                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque molestias
                                            dolore earum aliquid corporis sequi nisi incidunt ad quo provident! Tempore
                                            magni eos sint deleniti minus cum reprehenderit ratione nemo?
                                        </p>
                                        <p class="card-text fw-bold">- Albert Winning</p>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>
                    <div class="carousel-item">

                        <div class="card bg-white bg-opacity-25 m-auto text-white">
                            <div class="row m-5">
                                <div class="col-md-4 d-flex justify-content-end">
                                    <img src="../assets/img/test2.jpg" class="rounded-circle p-3" alt="...">
                                </div>
                                <div class="col-md-8">
                                    <div class="card-body">
                                        <p class="card-text pt-4 fs-4 w-75 position-relative">
                                            <i class="fa-solid fa-quote-right position-absolute opacity-25"></i>
                                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque molestias
                                            dolore earum aliquid corporis sequi nisi incidunt ad quo provident! Tempore
                                            magni eos sint deleniti minus cum reprehenderit ratione nemo?
                                        </p>
                                        <p class="card-text fw-bold">- Tizio</p>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>
                    <div class="carousel-item">

                        <div class="card bg-white bg-opacity-25 m-auto text-white">
                            <div class="row m-5">
                                <div class="col-md-4 d-flex justify-content-end">
                                    <img src="../assets/img/test3.jpg" class="rounded-circle p-3" alt="...">
                                </div>
                                <div class="col-md-8">
                                    <div class="card-body">
                                        <p class="card-text pt-4 fs-4 w-75 position-relative">
                                            <i class="fa-solid fa-quote-right position-absolute opacity-25"></i>
                                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque molestias
                                            dolore earum aliquid corporis sequi nisi incidunt ad quo provident! Tempore
                                            magni eos sint deleniti minus cum reprehenderit ratione nemo?
                                        </p>
                                        <p class="card-text fw-bold">- Tizia</p>
                                    </div>
                                </div>
                            </div>
                        </div>

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
    font-size: 5rem;
    top: -1rem;
    left: 0;
}
#carouselExampleIndicators {
    // height: 500px;
    // width: 75%;
    margin: auto;
    margin-top: 5rem;
}
.carousel-inner {
    // height: 300px;
}
</style>