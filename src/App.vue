<template>
    <div class="container-fluid">
        <div class="container">
            <PageHeader></PageHeader>
        </div>
        <PageHero></PageHero>
    </div>
</template>

<script>
// IMPORTAZIONE COMPONENTI
import PageHeader from "./components/PageHeader.vue";
import PageHero from "./components/PageHero.vue";
export default {
    components: {
        PageHeader,
        PageHero
    }
}
</script>
<style lang="scss">
@import "bootstrap/scss/bootstrap";
.container-fluid {
    background-color: #f5f6f9;
}
</style>