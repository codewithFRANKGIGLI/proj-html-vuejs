<template>
    <section class="position-relative">
        <div id="imgTextContainer" class="position-absolute top-50 start-50 translate-middle text-center text-white z-2">
            <h1 id="imgTitle" class="fw-bold pb-5 w-75">Yacht Charters, Repairs & Transportation, US-wide!</h1>
            <button id="learnBtn" type="button" class="btn mt-3 px-4 py-3 fw-bold fs-5">More Details</button>
        </div>
        <img src="../assets/img/bg5.jpg" class="w-100" alt="">
    </section>
    <section id="services" class="w-100">
        <div class="container text-center">
            <div class="row py-5">
                <h1 class="fw-bold">Services</h1>
            </div>
            <hr class="pb-5">
            <div class="row row-cols-1 row-cols-md-3 g-4">
                <div class="col">
                    <div class="card pb-5 border-light bg-transparent h-100">
                        <div class="card-body">
                            <div class="d-flex gap-3">
                                <i class="fa-solid fa-anchor"></i>
                                <h5 class="card-title fw-bold fs-3 my-auto">Yacht Rentals</h5>
                            </div>
                            <p class="card-text text-start opacity-75 pt-3 lh-lg">With more than two hundred yacht and boat models on our fleet and both the East and the West coasts covered we are able to offer you the best yacht chartering options.</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card pb-5 border-light bg-transparent h-100">
                        <div class="card-body">
                            <div class="d-flex gap-3">
                                <i class="fa-solid fa-user-tie"></i>
                                <h5 class="card-title fw-bold fs-3 my-auto">Management</h5>
                            </div>
                            <p class="card-text text-start opacity-75 pt-3 lh-lg">On par with providing an amazing range of rentals on boats and yachts of all sizes and comfort levels, we well also gladly pick up on providing all kinds of maintenance...</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card pb-5 border-light bg-transparent h-100">
                        <div class="card-body">
                            <div class="d-flex gap-3">
                                <i class="fa-solid fa-truck-fast"></i>
                                <h5 class="card-title fw-bold fs-3 my-auto">Transportation</h5>
                            </div>
                            <p class="card-text text-start opacity-75 pt-3 lh-lg">Whenever any of our clients wants to try some brand new sailing destination or make a place of residence move to another water area - there comes the issue of logistics.</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card pb-5 border-light bg-transparent h-100">
                        <div class="card-body">
                            <div class="d-flex gap-3">
                                <i class="fa-regular fa-star"></i>
                                <h5 class="card-title fw-bold fs-3 my-auto">Yacht Repair</h5>
                            </div>
                            <p class="card-text text-start opacity-75 pt-3 lh-lg">With decades of professional experience in renting, repairing and transporting just all kinds of yachts and boats under out belt - we can assure you that we are your best choice!</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card pb-5 border-light bg-transparent h-100">
                        <div class="card-body">
                            <div class="d-flex gap-3">
                                <i class="fa-regular fa-thumbs-up"></i>
                                <h5 class="card-title fw-bold fs-3 my-auto">Yacht Upgrades</h5>
                            </div>
                            <p class="card-text text-start opacity-75 pt-3 lh-lg">As far as any personally-owned vehicles are concerned, whether we are talking about cars with four wheels, bikes with two wheels or yacht with no wheels, owners do...</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card pb-5 border-light bg-transparent h-100">
                        <div class="card-body">
                            <div class="d-flex gap-3">
                                <i class="fa-solid fa-suitcase"></i>
                                <h5 class="card-title fw-bold fs-3 my-auto">Corporate Events</h5>
                            </div>
                            <p class="card-text text-start opacity-75 pt-3 lh-lg">When it comes to organizing a corporate yacht charter of a Fortune 500 scale for a big crew of people - we will be able to make it flawless. We will exceed your expectations!</p>
                        </div>
                    </div>
                </div>
                
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

#imgTitle {
    font-size: 6rem;
}

#learnBtn {
    background-color: $second-color;
    color: white;
}

#services {
    background-image: url(../assets/img/bg6.jpg);

}
i {
    font-size: 2.5rem;
    color: white;
    background-color: $second-color;
    border-radius: 50%;
    height: 5rem;
    width: 5rem;
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>