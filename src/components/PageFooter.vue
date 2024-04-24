<template>
    <section>
        <footer class="bg-transparent text-center text-lg-start">
            <div class="container p-5">
                <div class="row my-5 py-5">
                    <div class="col me-5">
                        <div class="d-flex align-items-center">
                            <img src="../assets/img/logo (1).png" alt="" />
                        </div>
                        <p class="mt-2 opacity-75">Yacht rentals for people who love sailing across the seas...</p>
                    </div>
                    <div class="col">
                        <ul class="list-unstyled">
                            <li class="mb-2">
                                <a class="text-uppercase mb-4 fw-bold text-dark">yachts</a>
                            </li>
                            <li class="mb-2">
                                <a class="text-uppercase mb-4 fw-bold text-dark">services</a>
                            </li>
                            <li class="mb-2">
                                <a class="text-uppercase mb-4 fw-bold text-dark">reservations</a>
                            </li>
                        </ul>
                    </div>
                    <div class="col">
                        <ul class="list-unstyled">
                            <li class="mb-2">
                                <a class="text-uppercase mb-4 fw-bold text-dark">blog</a>
                            </li>
                            <li class="mb-2">
                                <a class="text-uppercase mb-4 fw-bold text-dark">Privacy policy</a>
                            </li>
                            <li class="mb-2">
                                <a class="text-uppercase mb-4 fw-bold text-dark">terms of use</a>
                            </li>
                        </ul>
                    </div>
                    <div class="col">
                        <h5 class="fw-bold mb-4">Newsletter</h5>
                        <div class="input-group mb-3">
                            <input type="text" class="form-control" placeholder="Enter your e-mail"
                                aria-label="Recipient's username" aria-describedby="button-addon2">
                            <button type="button" class="btn fw-semibold fs-5" id="button-addon2">Subscribe</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="bottom-footer text-center p-3">

                <nav class="navbar navbar-expand-lg">
                    <div class="container px-5">
                        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                            <div class="navbar gap-3">
                                <span>ZEMEZ</span><span class="opacity-50">&#169;. ALL RIGHTS RESERVED.</span>
                                <span>|</span>
                                <a class="nav-link" href="#">PRIVACY POLICY</a>
                                <span>|</span>
                                <a class="nav-link" href="#">TERMS OF USE</a>
                            </div>
                        </div>
                        <div class="text-end text-white opacity-50">
                            <i class="fa-brands fa-facebook"></i>
                            <i class="fa-brands fa-square-twitter mx-4"></i>
                            <i class="fa-brands fa-square-instagram"></i>
                        </div>
                    </div>
                </nav>

            </div>
        </footer>
    </section>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;

#button-addon2 {
    background-color: $second-color;
    color: white;
}

a {
    text-decoration: none;
    cursor: pointer;
}

.bottom-footer {
    background-color: $third-color;
}

span {
    color: white;
}

.nav-link {
    color: white;

    &:hover {
        color: $second-color;
    }
}

i {
    border-radius: 75%;
    font-size: 1.5rem;
    cursor: pointer;

    &:hover {
        color: $second-color;
    }
}
</style>