<script>
import MainOurSpecialties from "./AppMainPartials/MainOurSpecialties.vue"
import MainLastNews from "./AppMainPartials/MainLastNews.vue"
import MainEventsCarosuel from "./AppMainPartials/MainEventsCarosuel.vue"
import MainTestimonialsCarousel from "./AppMainPartials/MainTestimonialsCarousel.vue"
import MainContactUs from "./AppMainPartials/MainContactUs.vue"


export default {
    name: "AppMain",
    components: {
        MainOurSpecialties,
        MainLastNews,
        MainEventsCarosuel,
        MainTestimonialsCarousel,
        MainContactUs
    },
    data() {
        return {
            eventImgs: ["02", "03"]
        }
    },
}
</script>

<template>
    <main>
        <!--Divided in 5 Sections-->

        <!--1st OurSpecialities-->
        <MainOurSpecialties :eventImgs="eventImgs" />

        <!--2nd EventsCarosue-->
        <MainEventsCarosuel :eventImgs="eventImgs" />

        <!--3rd LastNews-->
        <MainLastNews />

        <!--4th Testimonials-->
        <MainTestimonialsCarousel />

        <!--5th Contactus-->
        <MainContactUs />
    </main>

</template>

<style>

</style>
