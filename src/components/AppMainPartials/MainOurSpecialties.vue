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
    <!--1st section Our Specialities-->
    <div id="ourspecialities" class="">

        <!--Titles & cards-->
        <div class="window-wrapper m-auto container">
            <div class="titles text-center">
                <h2>Our Specialities</h2>
                <h7>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores, error?</h7>
            </div>

            <!--Row with cards-->
            <div class="row m-5">
                <div class="col-3" v-for="item in svgImgs">
                    <div class="card border border-0">
                        <img :src="item.url" class="card-img-top" alt="...">
                        <div class="card-body text-center">
                            <h5 class="card-title">{{ item.name }}</h5>
                            <p class="card-text">Some quick text to build on the card </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!--carousel and text-->
        <div class="container w-75 m-auto d-flex pt-5">

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
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselTwo" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
            </div>

            <!--Text-->
            <div class="mini-window col-6 align-self-center position-relative">
                <div class="card py-5 px-3 border border-0 rounded-0">
                    <div class="card-body">
                        <h3 class="card-title">Jason Bickford</h3>
                        <p class="card-title">Founder and Executor Director</p>
                        <div class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore,
                            harum.</div>
                        <i v-for="icon in bottomicons" :class="icon"></i>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!--/1st section Our Specialities-->
</template>

<style>
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
}
</style>