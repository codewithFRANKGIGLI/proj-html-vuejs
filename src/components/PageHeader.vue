<template>
    <section class="">
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