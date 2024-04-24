<template>
    <section class="position-relative">
        <div id="imgTextContainer" class="text-white position-absolute z-2">
            <h1 id="imgTitle" class="fw-bold">ENJOY</h1>
            <h2 class="fw-normal">WORLD RALLY 2017-19</h2>
            <p class="fw-semibold fs-1 w-75">Explore some of the most beatiful regions of the world. Make your dream come tru and join the Yachtec World Rally 2017-19</p>
            <button id="learnBtn" type="button" class="btn mt-3 px-4 py-3 fw-bold fs-5">More Details</button>
        </div>
        <img src="../assets/img/bg7.jpg" class="d-block w-100" alt="">
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
    h2 {
        font-size: 6rem;
    }
    #learnBtn {
    background-color: $second-color;
    color: white;
}
</style>