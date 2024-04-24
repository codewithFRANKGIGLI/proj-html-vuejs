<template>
    <section class="" id="bg-second-color">
        <div class="container text-center text-white p-5">
            <h1 id="imgTitle" class="fw-bold p-5">Our Yachts</h1>

            <div class="row pt-4">
                <div class="col-3">
                    <img src="../assets/img/services-1.jpg" class="img-fluid" alt="">
                </div>
                <div class="col-3">
                    <img src="../assets/img/services1.jpg" class="img-fluid" alt="">
                </div>
                <div class="col-3">
                    <img src="../assets/img/services2.jpg" class="img-fluid" alt="">
                </div>
                <div class="col-3">
                    <img src="../assets/img/services3.jpg"  class="img-fluid" alt="">
                </div>
            </div>
            <div class="row pt-4 pb-5">
                <div class="col-3">
                    <img src="../assets/img/services4.jpg" class="img-fluid" alt="">
                </div>
                <div class="col-3">
                    <img src="../assets/img/services5.jpg" class="img-fluid" alt="">
                </div>
                <div class="col-3">
                    <img src="../assets/img/services6.jpg" class="img-fluid" alt="">
                </div>
                <div class="col-3">
                    <img src="../assets/img/services7.jpg" class="img-fluid" alt="">
                </div>
            </div>
            <button type="button" class="btn btn-outline-light px-4 py-2">View All</button>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;

#bg-second-color {
    background-color: $second-color;
}
</style>