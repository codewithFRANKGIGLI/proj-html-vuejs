<template>
    <div class="container-fluid">
        <div class="container">
            <PageHeader></PageHeader>
        </div>
        <PageHero></PageHero>
        <OurHistory></OurHistory>
        <PageServices></PageServices>
        <OurYachts></OurYachts>
        <PageEvent></PageEvent>
        <PageBlog></PageBlog>
        <PageTestimonials></PageTestimonials>
    </div>
</template>

<script>
// IMPORTAZIONE COMPONENTI
import PageHeader from "./components/PageHeader.vue";
import PageHero from "./components/PageHero.vue";
import OurHistory from "./components/OurHistory.vue";
import PageServices from "./components/PageServices.vue";
import OurYachts from "./components/OurYachts.vue";
import PageEvent from "./components/PageEvent.vue";
import PageBlog from "./components/PageBlog.vue";
import PageTestimonials from "./components/PageTestimonials.vue";
export default {
    components: {
        PageHeader,
        PageHero,
        OurHistory,
        PageServices,
        OurYachts,
        PageEvent,
        PageBlog,
        PageTestimonials
    }
}
</script>
<style lang="scss">
@import "bootstrap/scss/bootstrap";
.container-fluid {
    background-color: #f5f6f9;
}
</style>