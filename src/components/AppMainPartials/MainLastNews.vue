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


    <!--Creative leader-->
    <div id="creativeleader" class="d-flex container w-75 py-5 my-5">
        <div class="row ">
            <div class="col-6 ">
                <div class="card border border-0">
                    <div class="card-title">
                        <h2>Creative Leader<span class="text_myprimary">.</span> </h2>
                        <div class="riga">----------</div>
                    </div>
                    <div class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore,
                        harum. Lorem ipsum, dolor sit amet consectetur adipisicing elit. Id, debitis
                        expedita?
                        Nesciunt architecto totam similique velit repudiandae quod voluptates tempore unde
                        molestias </div>
                    <h6 class="fw-bold pt-3">READ MORE</h6>
                </div>
            </div>
            <div class="col-6">
                <div class="card border border-0 h-100">
                    <div class="col-12 mb-3">
                        <div class="d-flex w-100 justify-content-between fw-bold mb-1">
                            <div class="">Mentorship</div>
                            <div class="numer">78%</div>
                        </div>
                        <div class="riga chiara riga_grafico">----------------------------------------------------------
                        </div>
                    </div>
                    <div class="col-12 mb-3">
                        <div class="d-flex w-100 justify-content-between fw-bold mb-1">
                            <div class="">Education</div>
                            <div class="numer">95%</div>
                        </div>
                        <div class="riga riga_grafico">
                            ----------------------------------------------------------------------</div>
                    </div>
                    <div class="col-12 mb-3">
                        <div class="d-flex w-100 justify-content-between fw-bold mb-1">
                            <div class="">Learning</div>
                            <div class="numer">65%</div>
                        </div>
                        <div class="riga riga_grafico">-------------------------------------------------</div>
                    </div>
                    <div class="col-12 mb-3">
                        <div class="d-flex w-100 justify-content-between fw-bold mb-1">
                            <div class="">Motivation</div>
                            <div class="numer">83%</div>
                        </div>
                        <div class="riga chiara riga_grafico">
                            ---------------------------------------------------------------</div>
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
                                        <button class="my_btn bg_myprimary position-absolute text-light fw-normal"><i
                                                class="fa-regular fa-circle-check"></i> Business, Leading</button>
                                    </div>
                                    <div class="date my_text_smaller pt-4">
                                        <i class="fa-regular fa-clock text_myprimary"></i> May 5, 2025,
                                        <i class="fa-regular fa-user text_myprimary"></i> Giacomo Marongiu
                                    </div>
                                    <h5 class="card-title fw-bold pt-1">Next Investment</h5>
                                    <p class="card-text blog_p">Some example text to build on the card title</p>
                                    <h6 class="fw-bold my_text_smaller">READ MORE</h6>
                                </div>
                            </div>
                        </div>
                        <div class="col-4">
                            <div class="card border border-0">
                                <div class="card-body">
                                    <div class="card_wrapper position-relative">
                                        <img src="/public/img/events/h1-img-02.jpg" class="d-block w-100">
                                        <button class="my_btn bg_myprimary position-absolute text-light fw-normal"><i
                                                class="fa-regular fa-circle-check"></i> Business, Leading</button>
                                    </div>
                                    <div class="date my_text_smaller pt-4">
                                        <i class="fa-regular fa-clock text_myprimary"></i> May 5, 2025,
                                        <i class="fa-regular fa-user text_myprimary"></i> Giacomo Marongiu
                                    </div>
                                    <h5 class="card-title fw-bold pt-1">Team Building</h5>
                                    <p class="card-text blog_p">Some example text to build on the card title</p>
                                    <h6 class="fw-bold my_text_smaller">READ MORE</h6>
                                </div>
                            </div>
                        </div>
                        <div class="col-4">
                            <div class="card border border-0">
                                <div class="card-body">
                                    <div class="card_wrapper position-relative">
                                        <img src="/public/img/events/h1-img-03.jpg" class="d-block w-100">
                                        <button class="my_btn bg_myprimary position-absolute text-light fw-normal"><i
                                                class="fa-regular fa-circle-check"></i> Business, Leading</button>
                                    </div>
                                    <div class="date my_text_smaller pt-4">
                                        <i class="fa-regular fa-clock text_myprimary"></i> May 5, 2025,
                                        <i class="fa-regular fa-user text_myprimary"></i> Giacomo Marongiu
                                    </div>
                                    <h5 class="card-title fw-bold pt-1">New Business</h5>
                                    <p class="card-text blog_p">Some example text to build on the card title</p>
                                    <h6 class="fw-bold my_text_smaller">READ MORE</h6>
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

<style >
.card_wrapper{
    button{
        bottom:-10px;
        right: 10px
    }
}

.riga_grafico{
    height: 3px;
}

.chiara{
    background: rgb(244, 167, 153);
}

.blog_p{
    font-size: small;
}
</style>