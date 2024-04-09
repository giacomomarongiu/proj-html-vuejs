<script>
export default {
    name: "MainEventsCarosuel",
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
            <div class="event_tab w-75 carousel-caption text-dark text-start">
                <div class="wrapper col-6 bg-light">
                    <h3 class="p-2 border">Upcoming Events</h3>
                    <div class="row">
                        <div class="col">
                            <div class="events-card border d-flex">
                                <div class="col-3">DATA</div>
                                <div class="col-9">
                                    <h4>Titolo</h4>
                                    <p>Orario</p>
                                    <p>Luogo</p>
                                    <p class="fw-bolg">REAM MORE</p>
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

<style></style>