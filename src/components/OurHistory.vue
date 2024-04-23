<template>
    <section class="position-relative">
        <div id="imgTextContainer" class="position-absolute z-2">
            <h1 id="imgTitle" class="fw-bold pb-5">Our History</h1>
            <hr>
            <p class="fw-bold fs-4 pt-5 w-75">Founded by a worldwide-famous yacht racer Alfred Tannernstrick, since its inception back in 1977, this company has been a welcoming harbor for all yachting and sailing enthusiasts, from all across the US!</p>
            <p class="fs-4 pt-5 w-75">We offer a real variety of professional services, from the simple yachts chartering and corporate events, all the way to yacht repair, upgrades and modifications and maintenance checkups.</p>
            <p class="fs-4 pt-5 w-75">With decades of professional experience in renting, repairing and transporting just all kinds of yachts and boats under our belt - we can assure you that we are your best choice!</p>
            <button id="learnBtn" type="button" class="btn mt-5">Learn More</button>
        </div>
        <img src="../assets/img/bg4.jpg" class="w-100" alt="">
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;

    #imgTextContainer {
        left: 50%;
        top: 20%
    }
    #learnBtn {
        background-color: $second-color;
        color: white;
    }
    .h1 {
        color: $third-color;
    }
</style>