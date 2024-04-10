<script>
export default {
    name: "MainOurSpecialties",
    props: {
        eventImgs: Array
    },
    data() {
        return {
            svgImgs: [{
                url: 'public/img/svgs/svg-0.svg',
                name: 'Knowing'
            },
            {
                url: 'public/img/svgs/svg-1.svg',
                name: 'Selling'
            },
            {
                url: 'public/img/svgs/svg-2.svg',
                name: 'Learning'
            }, {
                url: 'public/img/svgs/svg-3.svg',
                name: 'Contact'
            }
            ],
            bottomicons: ["fa-brands fa-linkedin", "fa-brands fa-facebook", "fa-brands fa-twitter"]
        }
    },
}
</script>

<template>
    <!--1st part Our Specialities-->
    <div id="ourspecialities" class=" ">

        <!--Titles & cards-->
        <div class="window-wrapper m-auto container">
            <div class="titles text-center">
                <h2 class="fw-bold">Our Specialities<span class="text_myprimary">.</span></h2>
                <h6 class="fw-normal">Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores, error?</h6>
            </div>
            <div class="riga m-auto my-3">_______</div>
            <!--Row with cards-->
            <div class="row m-5 gx-5">
                <div class="col-3" v-for="item in svgImgs">
                    <div class="card border border-0 m-5">
                        <img :src="item.url" class="card-img-top p-3 pb-1" alt="...">
                        <div class="card-body text-center">
                            <h5 class="card-title fw-bold pt-0">{{ item.name }}</h5>
                            <p class=" my_text_smaller">Some quick text to build on the card </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!--carousel and text-->
        <div class="container w-75 m-auto d-flex pt-5 position-relative">
            <!--Bg circle-->
            <div class="position-absolute top-0 circle">
                <img class="w-75" src="/public/img/svgs/svg-4.svg" alt="">
            </div>

            <!--carousel-->
            <div id="carouselTwo" class="col-6 carousel slide">
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="/public/img/events/h1-img-01.jpg" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item" v-for="img in eventImgs">
                        <img :src="'/public/img/events/h1-img-' + img + '.jpg'" class="d-block w-100" alt="...">
                    </div>
                </div>

                <button class="carousel-control-prev" type="button" data-bs-target="#carouselTwo" data-bs-slide="prev">
                    <span class="" aria-hidden="true"></span>
                    <span class="">&#10229;</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselTwo" data-bs-slide="next">
                    <span class="" aria-hidden="true"></span>
                    <span class="">&#10230</span>
                </button>
                <div class="my_buttons position-absolute">
                    <button class="border border-0 bg_myprimary w-25">&#10229;</button>
                    <button class="border border-0 bg_myprimary w-25">&#10230;</button>
                </div>
            </div>

            <!--Text-->
            <div class="mini-window col-6 align-self-center position-relative">
                <div class="card py-5 px-3 border border-0 rounded-0">
                    <div class="card-body">
                        <h3 class="card-title">Jason Bickford</h3>
                        <p class="card-title text_smaller">Founder and Executor Director</p>
                        <div class="riga mb-2">---------</div>
                        <div class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore,
                            harum.</div>
                        <i class="text_myprimary pt-2 pe-2" v-for="icon in bottomicons" :class="icon"></i>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!--/1st section Our Specialities-->
</template>

<style>
#ourspecialities {
    background: var(--bool-bg-lightgrey);
    padding-bottom: 8rem;
}

.window-wrapper {
    width: 90%;
    margin: auto;
    position: relative;
    z-index: 1;
    background-color: white;
    padding-top: 2rem;
}

.mini-window {
    margin-left: -2rem;

    .card-text {
        font-size: smaller;
    }

    .text_smaller {
        font-size: small;
    }

}

.my_buttons {
    width: 35%;
    bottom: 0;
    z-index: 2;

    button {
        height: 50px;
    }
}

.circle{
    right:-16%
}
</style>