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

        }
    },
}
</script>

<template>
    <main>
        <!--Divided in 5 Sections-->
        
        <!--1st OurSpecialities-->
        <MainOurSpecialties />

        <!--2nd EventsCarosue-->
        <MainEventsCarosuel />

        <!--3rd LastNews-->
        <MainLastNews />

        <!--4th Testimonials-->
        <MainTestimonialsCarousel />

        <!--5th Contactus-->
        <MainContactUs />
    </main>

</template>

<style>
.window-wrapper {
    width: 90%;
    margin: auto;
    position: relative;
    z-index: 1;
    border: 1px solid black;
    background-color: white;
    padding-top: 2rem;
}


.pippo {
    margin-left: -2rem;

}

.event_tab {
    position: absolute;
    top: 25%
}

.testimonials_item {
    height: 300px;
    background: #000000bf;
}
</style>
