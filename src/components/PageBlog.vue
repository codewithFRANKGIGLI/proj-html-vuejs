<template>
    <section id="services" class="w-100">
        <div class="container text-center">
            <div class="row py-5">
                <h1 class="fw-bold">Yachtsmen's Blog</h1>
            </div>
            <hr class="">
            <div class="card-group">
                <div class="card border-light p-3">
                    <img src="../assets/img/post1.jpg" class="card-img-top" alt="...">
                    <div class="card-footer">
                        <small class="text-body-secondary">December 30, 2020</small>
                    </div>
                    <div class="card-body">
                        <h5 class="card-title fw-bold">Is greece a Good Cgoice for Yacht Sailing?</h5>
                    </div>
                </div>
                <div class="card border-light p-3">
                    <img src="../assets/img/post2.jpg" class="card-img-top" alt="...">
                    <div class="card-footer">
                        <small class="text-body-secondary">December 16, 2020</small>
                    </div>
                    <div class="card-body">
                        <h5 class="card-title fw-bold">Seattle Yachts and Northwest Yachts Announce Merger</h5>
                    </div>
                </div>
                <div class="card border-light p-3">
                    <img src="../assets/img/post3.jpg" class="card-img-top" alt="...">
                    <div class="card-footer">
                        <small class="text-body-secondary">December 16, 2020</small>
                    </div>
                    <div class="card-body">
                        <h5 class="card-title fw-bold">Video: Superyacht 'Project Jupiter' Launched By Lurssen</h5>
                    </div>
                </div>
            </div>
            <button id="learnBtn" type="button" class="btn mt-3 px-4 py-3 fw-bold fs-5">View All Blog Posts</button>

        </div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;

#learnBtn {
    background-color: $second-color;
    color: white;
}
</style>