<script>
export default {
    name: "MainLastNews",
    data() {
        return {

        }
    },
}
</script>

<template>
    <!--2nd Section-->

    <!--Due bei div al 50%-->
    <div id="creativeleader" class="d-flex container w-75 py-5 my-5">
        <div class="row ">
            <div class="col-6 ">
                <div class="card border border-0">
                    <div class="card-title">
                        <h2>Creative Leader.</h2>
                        <p>____</p>
                    </div>
                    <div class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore,
                        harum. Lorem ipsum, dolor sit amet consectetur adipisicing elit. Id, debitis
                        expedita?
                        Nesciunt architecto totam similique velit repudiandae quod voluptates tempore unde
                        molestias maxime consectetur distinctio iste accusantium praesentium laudantium tatum
                        dolorem.</div>
                    <h6 class="fw-bold pt-3">READ MORE</h6>
                </div>
            </div>
            <div class="col-6">
                <div class="card border border-0">
                    <div class="col-12">
                        <div class="card-title ">
                            <h5 class="mb-3">Mentorship</h5>
                            <div class="riga">_</div>
                        </div>
                    </div>
                    <div class="col-12">
                        <div class="card-title ">
                            <h5 class="mb-3">Mentorship</h5>
                            <div class="riga">_</div>
                        </div>
                    </div>
                    <div class="col-12">
                        <div class="card-title ">
                            <h5 class="mb-3">Mentorship</h5>
                            <div class="riga">_</div>
                        </div>
                    </div>
                    <div class="col-12">
                        <div class="card-title ">
                            <h5 class="mb-3">Mentorship</h5>
                            <div class="riga">_</div>
                        </div>
                    </div>
                    <div class="col-12">
                        <div class="card-title ">
                            <h5 class="mb-3">Mentorship</h5>
                            <div class="riga">_</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div id="latestnews" class="container pt-5">
        <!--Titles-->
        <div class="titles text-center">
            <h2>Latest news</h2>
            <h6>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores, error?</h6>
        </div>
        <!--carousel News-->
        <div id="carouselFour" class="carousel carousel-dark slide w-100">
            <div class="carousel-inner">
                <div class="carousel-item active" data-bs-interval="10000">
                    <!--Row with cards-->
                    <div class="row m-5">
                        <div class="col-4">
                            <div class="card border border-0">
                                <div class="card-body">
                                    <div class="card_wrapper position-relative">
                                        <img src="/public/img/events/h1-img-01.jpg" class="d-block w-100">
                                        <button
                                            class="my_btn position-absolute text-light bg-warning end-0 bottom-0 mx-2"><i
                                                class="fa-regular fa-circle-check"></i> Button</button>
                                    </div>
                                    <p>Qualcosa scritto in piccolo</p>
                                    <h5 class="card-title">Next investment</h5>
                                    <p class="card-text">Some quick example text to build on the card title</p>
                                    <h6 class="fw-bold">READ MORE</h6>
                                </div>
                            </div>
                        </div>
                        <div class="col-4">
                            <div class="card border border-0">
                                <div class="card-body">
                                    <div class="card_wrapper position-relative">
                                        <img src="/public/img/events/h1-img-02.jpg" class="d-block w-100">
                                        <button
                                            class="my_btn position-absolute text-light bg-warning end-0 bottom-0 mx-2"><i
                                                class="fa-regular fa-circle-check"></i> Button</button>
                                    </div>
                                    <p>Qualcosa scritto in piccolo</p>
                                    <h5 class="card-title">Team Building</h5>
                                    <p class="card-text">Some quick example text to build on the card title</p>
                                    <h6 class="fw-bold">READ MORE</h6>
                                </div>
                            </div>
                        </div>
                        <div class="col-4">
                            <div class="card border border-0">
                                <div class="card-body">
                                    <div class="card_wrapper position-relative">
                                        <img src="/public/img/events/h1-img-03.jpg" class="d-block w-100">
                                        <button
                                            class="my_btn position-absolute text-light bg-warning end-0 bottom-0 mx-2"><i
                                                class="fa-regular fa-circle-check"></i> Button</button>
                                    </div>
                                    <p>Qualcosa scritto in piccolo</p>
                                    <h5 class="card-title">New Business Day</h5>
                                    <p class="card-text">Some quick example text to build on the card title</p>
                                    <h6 class="fw-bold">READ MORE</h6>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>

            <button class="carousel-control-prev" type="button" data-bs-target="#carouselFour" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselFour" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </div>
</template>

<style>

</style>