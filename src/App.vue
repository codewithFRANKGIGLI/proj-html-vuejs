<template>
    <div class="container-fluid">
        <div class="container">
            <PageHeader></PageHeader>
        </div>
        <PageHero :links="links"></PageHero>
        <OurHistory></OurHistory>
        <PageServices></PageServices>
        <OurYachts></OurYachts>
        <PageEvent></PageEvent>
        <PageBlog></PageBlog>
        <PageTestimonials></PageTestimonials>
        <PageFooter></PageFooter>
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
import PageFooter from "./components/PageFooter.vue";
export default {
    components: {
        PageHeader,
        PageHero,
        OurHistory,
        PageServices,
        OurYachts,
        PageEvent,
        PageBlog,
        PageTestimonials,
        PageFooter
    },
    data() {
        return {
            links: [
                {
                    name: 'ABOUT',
                    link: '###'
                },
                {
                    name: 'SERVICES',
                    link: '###'
                },
                {
                    name: 'YACHTS',
                    link: '###'
                },
                {
                    name: 'RESERVATIONS',
                    link: '###'
                },
                {
                    name: 'BLOG',
                    link: '###'
                },
                {
                    name: 'CONTACTS',
                    link: '###'
                },
            ]
        }
    }
}
</script>
<style lang="scss">
@import "bootstrap/scss/bootstrap";
.container-fluid {
    background-color: #f5f6f9;
}
</style>