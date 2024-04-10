<script>
import AppHeaderMenu from "./AppHeaderPartials/AppHeaderMenu.vue"

export default {
    name: "AppHeader",
    components: {
        AppHeaderMenu,
    },
    data() {
        return {
            menuOptions: ['HOMES', 'PAGES', 'BLOG', 'SHOP', 'EVENTS', 'ELEMENTS',],
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
                    <img src="/public/img/mylogo/logo-img-01.png" alt="" class="mylogo">
                </a>

                <!-- Inserisco dinamicamente il menu-->
                <div class="collapse navbar-collapse flex-grow-0 ml-auto" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <!--Qui con la Props passata alla componente-->
                        <AppHeaderMenu :option="option" v-for="option in menuOptions" />

                        <!--Qui con un semplice ciclo-->
                        <li v-for="icon in menuIcons">
                            <a class="nav-link" href="#"> <i :class="icon"></i></a>
                        </li>
                    </ul>

                </div>
            </div>
        </nav>
        <!--/NavBar-->

        <!--Jumbo/Carosuel-->
        <div id="jumbocarosuel" class="carousel slide">
            <div class="carousel-inner">
                <div class="carousel-item active">>
                    <img src="/public/img/jumbo-slider/rev-slider-main-home-img-01.jpg" class="d-block w-100" alt="...">
                    <div class="carousel-caption text-dark text-start">
                        <h1 class="">Our Team<span class="text_myprimary">.</span></h1>
                        <p class="fs-6 text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione eveniet
                            dicta eaque quos atque veritatis saepe similique sequi ipsam mollitia?</p>
                        <button type="" class="my_btn bg_myprimary">READ MORE <span class="linebye">|</span> &#10230</button>
                        <button type="" class="my_btn bg_mylight">PURCHASE <span class="linebye">|</span> &#10230</button>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="/public/img/jumbo-slider/rev-slider-main-home-img-02.png" class="d-block w-100" alt="...">
                    <div class="carousel-caption text-dark text-start">
                        <h1 class="">Another Team<span class="text_myprimary">.</span></h1>
                        <p class="fs-6 text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione eveniet
                            dicta eaque quos atque veritatis saepe similique sequi ipsam mollitia?</p>
                        <button type="" class="my_btn bg_myprimary">READ MORE <span class="linebye">|</span> &#10230</button>
                        <button type="" class="my_btn bg_mylight">PURCHASE <span class="linebye">|</span> &#10230</button>
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#jumbocarosuel" data-bs-slide="prev">
                <span class="" aria-hidden="true"></span>
                <span class=""><i class="fa-solid fa-arrow-left-long fa-2x text-dark"></i></span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#jumbocarosuel" data-bs-slide="next">
                <span class="" aria-hidden="true"></span>
                <span class=""><i class="fa-solid fa-arrow-right-long fa-2x text-dark"></i></span>
            </button>
        </div>
    </header>
</template>

<style>
header {
    margin-top: -2rem;
    margin-bottom: -2rem;

    nav {
        font-size: 12px;

        li {
            .arrow {
                visibility: opacity 0.5s linear;
                display: none;
            }
        }

        li:hover {
            .nav-link {
                transition: 0.5s;
                background-color: rgba(0, 0, 0, 0.065);
                color: var(--bool-bg-primary);
                opacity: 1;
            }


            .arrow {
                transition: opacity 0.5s linear;
                display: inline;
                opacity: 1;
            }

        }
    }

    .mylogo {
        max-width: 130px;
        max-height: 40px;
    }

}

#jumbocarosuel {
    z-index: 0;
    .carousel-caption {
        width: 35%;
        top: 40%;
        .my_btn{
            margin-right: 1rem;
        }
    }
}
</style>
