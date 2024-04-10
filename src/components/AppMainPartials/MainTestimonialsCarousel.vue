<script>
export default {
    name: "MainTestimonialsCarousel",
    data() {
        return {
            myTestimonials: ["07", "08"]
        }
    },
}
</script>

<template>
    <div id="Testimonial position-relative">
        <!--Titles-->

        <!--carousel-->
        <div id="carouselFive" class="carousel position-relative carousel-dark slide w-100">
            <h1 class="text-center w-100 position-absolute">Testimonials.</h1>
            <div class="carousel-inner testimonials_item d-flex">
                <div class="carousel-indicators pb-5">
                    <button type="button" data-bs-target="#carouselFive" data-bs-slide-to="0" class="active"
                        aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#carouselFive" data-bs-slide-to="1"
                        aria-label="Slide 2"></button>
                    <button type="button" data-bs-target="#carouselFive" data-bs-slide-to="2"
                        aria-label="Slide 3"></button>
                </div>
                <div class="carousel-item active position-relative d-flex justify-content-center pb"
                    data-bs-interval="10000">
                    <img src="/public/img/testimonials/h3-img-04.png" class="h-25 align-self-center">
                    <div class="carousel-caption bottom-0 text-light">
                        <h6 class="fw-bold">Cinthia Clark</h6>
                        <p class="fs-6">Some representative placeholder content for the first slide.</p>
                    </div>

                </div>
            </div>

            <button class="carousel-control-prev" type="button" data-bs-target="#carouselFive" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselFive" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>

        <!--Video-->
        <div class="video_container position-relative">
            <img src="/public/img/events/h1-img-04.jpg" class="d-block w-100">
            <i class="fa-solid fa-play fa-5x position-absolute top-50 start-50 text-light"></i>
        </div>
    </div>
</template>

<style>
.testimonials_item {
    height: 400px;
    background: #1e1c1cf5;
    padding-bottom: 5rem
}

#carouselFive {
    height: ;
    h1 {

        font-size: 160px;

    }
}
</style>