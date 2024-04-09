<script>
export default {
    name: "MainOurSpecialties",
    data() {
        return {

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
                <div class="col-3">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up
                                the
                                bulk
                                of the card's content.</p>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up
                                the
                                bulk
                                of the card's content.</p>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up
                                the
                                bulk
                                of the card's content.</p>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up
                                the
                                bulk
                                of the card's content.</p>
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
                    <div class="carousel-item">
                        <img src="/public/img/events/h1-img-02.jpg" class="d-block w-100" alt="...">
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
            <div class="pippo col-6 align-self-center position-relative">
                <div class="card py-5 px-3">
                    <div class="card-body">
                        <div class="card-title">Jason Bickford</div>
                        <div class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore,
                            harum.</div>
                        <div>Pippo Pluto Paperino</div>
                    </div>
                </div>
            </div>
        </div>

    </div>
    <!--/1st section Our Specialities-->
</template>

<style></style>