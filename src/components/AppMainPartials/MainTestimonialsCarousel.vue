<script>
export default {
    name: "MainTestimonialsCarousel",
    data() {
        return {

        }
    },
}
</script>

<template>
    <div id="Testimonial position-relative">
        <!--Titles-->

        <!--carousel-->
        <div id="carouselFive" class="carousel position-relative carousel-dark slide w-100">
            <h1 class="text-center position-absolute w-100">Testimonials</h1>
            <div class="carousel-inner testimonials_item d-flex">
                <div class="carousel-item active position-relative d-flex justify-content-center"
                    data-bs-interval="10000">
                    <img src="/public/img/events/h1-img-01.jpg" class="h-25 align-self-center">
                    <div class="carousel-caption bottom-0">
                        <h5>First slide label</h5>
                        <p>Some representative placeholder content for the first slide.</p>
                    </div>
                </div>
            </div>

            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark"
                data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark"
                data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>

        <!--Video-->

        <img src="/public/img/events/h1-img-01.jpg" class="d-block w-100">

    </div>
</template>

<style></style>