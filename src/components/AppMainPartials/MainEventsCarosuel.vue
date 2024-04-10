<script>
export default {
    name: "MainEventsCarosuel",
    props: {
        eventImgs: Array
    },
    data() {
        return {

        }
    },
}
</script>

<template>
    <div id="eventscarousel" class="carousel slide ">
        <div class="carousel-inner">
            <div class="carousel-item active">>
                <img src="/public/img/events/h1-img-01.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item" v-for="img in eventImgs">
                <img :src="'/public/img/events/h1-img-' + img + '.jpg'" class="d-block w-100" alt="...">
            </div>
            <div class="event_tab w-50 carousel-caption text-dark text-start">
                <div class="wrapper col-6 bg-light">
                    <h3 class="p-3 ps-4 fw-bold">Upcoming Events</h3>
                    <div class="row flex-column">
                        <div class="col" v-for="index in 3">
                            <div class="left_event events-card border d-flex p-4 pb-2">
                                <div class="col-3 d-flex justify-content-center ">
                                    <div
                                        class="text-light  bg_myprimary square d-flex flex-column align-items-center justify-content-center">
                                        <div class="fw-bold">07</div>
                                        <span>June 2022</span>
                                    </div>
                                </div>
                                <div class="ps-3 right_event col-9 d-flex flex-column align-items-start">
                                    <h6 class="fw-bold">New York Coaching</h6>
                                    <p class="date m-0">
                                        <i class="text_myprimary fa-regular fa-clock "></i>
                                        9:00 am - 5 p.m, Jan 7, 2022
                                    </p>
                                    <p class="date "><i class="text_myprimary fa-solid fa-location-dot"></i> Cambridge,
                                        MA 30245, USA</p>
                                    <p class="fw-bold my_text_smaller">READ MORE</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <button class="carousel-control-prev" type="button" data-bs-target="#eventscarousel" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#eventscarousel" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
</template>

<style>
.event_tab {
    position: absolute;
    top: 25%;

    .square {
        width: 70px;
        height: 55px;
        font-size: small;
    }
    .date{
        font-size: x-small;
    }
}


</style>