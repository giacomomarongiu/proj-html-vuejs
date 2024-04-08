<script>
export default {
    name: "AppHeader",
    data() {
        return {
            menuOptions: ["HOMES", "PAGES", "BLOG", "SHOP", "EVENTS", "ELEMENTS",],
            menuIcons: ['fa-solid fa-magnifying-glass', 'fa-solid fa-bars']
        }
    },
}
</script>

<template>
    <header class="">
        <!--NavBar-->
        <nav class="navbar navbar-expand-lg position-absolute z-1 w-100 pt-5 text-dark fw-bold">
            <div class="container-fluid">
                <!--Qui il Logo-->
                <a class="navbar-brand" href="#">
                    <img src="../assets/img/mylogo/logo-img-01.png" alt="" class="mylogo">
                </a>

                <!-- Inserisco dinamicamente il menu-->
                <div class="collapse navbar-collapse flex-grow-0 ml-auto" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li v-for="option in menuOptions" class="nav-item">
                            <a class="nav-link" href="#">{{ option }}</a>
                        </li>
                        <li v-for="icon in menuIcons">
                            <a class="nav-link" href="#"> <i :class="icon"></i></a>
                        </li>
                    </ul>

                </div>
            </div>
        </nav>
        <!--/NavBar-->

        <!--Jumbo/Carosuel-->
        <div id="carouselExample" class="carousel slide">
            <div class="carousel-inner">
                <div class="carousel-item active">>
                    <img src="../assets/img/jumbo-slider/rev-slider-main-home-img-01.jpg" class="d-block w-100"
                        alt="...">
                    <div class="carousel-caption text-dark text-start">
                        <h1 class="">Our Team</h1>
                        <p class="fs-6 text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione eveniet
                            dicta eaque quos atque veritatis saepe similique sequi ipsam mollitia?</p>
                        <button type="" class="my_btn bg_myprimary">READ MORE | -></button>
                        <button type="" class="my_btn bg_mylight">PURCHASE | -></button>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="../assets/img/jumbo-slider/rev-slider-main-home-img-02.png" class="d-block w-100"
                        alt="...">
                    <div class="carousel-caption text-dark text-start">
                        <h1 class="">Our Team</h1>
                        <p class="fs-6 text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione eveniet
                            dicta eaque quos atque veritatis saepe similique sequi ipsam mollitia?</p>
                        <button type="" class="my_btn bg_myprimary">READ MORE | -></button>
                        <button type="" class="my_btn bg_mylight">PURCHASE | -></button>
                    </div>
                </div>
            </div>

            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </header>
</template>

<style>
header {
    margin-top: -2rem;
    margin-bottom: -2rem;

    .mylogo {
        max-width: 100px;
    }

}

.carousel-caption {
    width: 35%;
    top: 35%
}
</style>
