<script>
export default {
    name: "AppMain",
    data() {
        return {

        }
    },
}
</script>

<template>
    <main> <!--Divided in 4 Sections-->

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

            <!--Carosuel and text-->
            <div class="container w-75 m-auto d-flex pt-5">
                <!--Carosuel-->
                <div id="carouselTwo" class="col-7 carousel slide">
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="../assets/img/events/h1-img-01.jpg" class="d-block w-100" alt="...">
                        </div>
                        <div class="carousel-item">
                            <img src="../assets/img/events/h1-img-02.jpg" class="d-block w-100" alt="...">
                        </div>
                    </div>

                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselTwo"
                        data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselTwo"
                        data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                    </button>

                </div>

                <!--Text-->
                <div class="pippo col-7 align-self-center position-relative">
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

            <!--Carosuel Events-->
            <!--Jumbo/Carosuel-->
            <div id="carouselThree" class="carousel slide ">
                <div class="carousel-inner">
                    <div class="carousel-item active">>
                        <img src="../assets/img/events/h1-img-01.jpg" class="d-block w-100" alt="...">
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

                <button class="carousel-control-prev" type="button" data-bs-target="#carouselThree"
                    data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselThree"
                    data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
            </div>

            <!--Due bei div al 50%-->
            <div id="creativeleader" class="d-flex  pt-5">
                <div class="row">
                    <div class="col-6 h-100">
                        <div class="card">
                            <div class="card-title">
                                <h2>Createive leader</h2>
                            </div>
                            <div class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore,
                                harum. Lorem ipsum, dolor sit amet consectetur adipisicing elit. Id, debitis
                                expedita?
                                Nesciunt architecto totam similique velit repudiandae quod voluptates tempore unde
                                molestias maxime consectetur distinctio iste accusantium praesentium laudantium
                                obcaecati culpa sed maiores, quam eligendi nostrum porro hic error esse! Sequi
                                blanditiis vero sed nulla neque qui, repudiandae voluptatum dolorem.</div>
                            <h6>READ MORE</h6>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="card">
                            <div class="col-12">
                                <div class="card-title">
                                    <h5>Mentorship</h5>
                                    <div class="riga text-warning">__________________________________________</div>
                                </div>
                            </div>
                            <div class="col-12">
                                <div class="card-title">
                                    <h5>Mentorship</h5>
                                    <div class="riga text-warning">__________________________________________</div>
                                </div>
                            </div>
                            <div class="col-12">
                                <div class="card-title">
                                    <h5>Mentorship</h5>
                                    <div class="riga text-warning">__________________________________________</div>
                                </div>
                            </div>
                            <div class="col-12">
                                <div class="card-title">
                                    <h5>Mentorship</h5>
                                    <div class="riga text-warning">__________________________________________</div>
                                </div>
                            </div>
                            <div class="col-12">
                                <div class="card-title">
                                    <h5>Mentorship</h5>
                                    <div class="riga text-warning">__________________________________________</div>
                                </div>
                            </div>

                        </div>
                    </div>
                </div>
            </div>

        </div>

        <!--2nd Section-->
        <div id="latestnews" class="container pt-5">
            <!--Titles-->
            <div class="titles text-center">
                <h2>Latest news</h2>
                <h7>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores, error?</h7>
            </div>

            <!--Carosuel News-->
            <div id="carouselFour" class="carousel carousel-dark slide w-100">


                <div class="carousel-inner">
                    <div class="carousel-item active" data-bs-interval="10000">
                        <!--Row with cards-->
                        <div class="row m-5">
                            <div class="col-4">
                                <div class="card">
                                    <div class="card-body">
                                        <img src="../assets/img/blog/h1-blog-img-01.jpg" class="d-block w-100">
                                        <h5 class="card-title">Card title</h5>
                                        <p class="card-text">Some quick example text to build on the card title and make
                                            up the bulk
                                            of the card's content.</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-4">
                                <div class="card">
                                    <div class="card-body">
                                        <img src="../assets/img/blog/h1-blog-img-02.jpg" class="d-block w-100">
                                        <h5 class="card-title">Card title</h5>
                                        <p class="card-text">Some quick example text to build on the card title and make
                                            up the bulk
                                            of the card's content.</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-4">
                                <div class="card">
                                    <div class="card-body">
                                        <img src="../assets/img/blog/h1-blog-img-03.jpg" class="d-block w-100">
                                        <h5 class="card-title">Card title</h5>
                                        <p class="card-text">Some quick example text to build on the card title and make
                                            up the bulk
                                            of the card's content.</p>
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

        <!--3rd Section-->
        <div id="Testimonial position-relative">
            <!--Titles-->

            <!--Carosuel-->
            <div id="carouselFive" class="carousel position-relative carousel-dark slide w-100">
                <h1 class="text-center position-absolute w-100">Testimonials</h1>
                <div class="carousel-inner testimonials_item d-flex">
                    <div class="carousel-item active position-relative d-flex justify-content-center"
                        data-bs-interval="10000">
                        <img src="../assets/img/testimonials/h3-img-04.png" class="h-25 align-self-center">
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

            <img src="../assets/img/01.jpg" class="d-block w-100">

        </div>

        <!--4th-->
        <div id="contactus" class="py-5 w-75 m-auto">

            <!--Due bei div al 50%-->
            <div class="d-flex">
                <div class="row py-5">
                    <div class="col-6">
                        <div class="card position-relative">
                            <img src="../assets/img/contactus/h1-contact-rev-01.png" class="d-block w-100">
                            <div class="position-absolute end-50 top-50">
                                <img src="../assets/img/contactus/h1-contact-rev-02.png" alt="">
                                <h4>New York Coaching</h4>
                                <h6>READ MORE</h6>
                            </div>
                        </div>
                    </div>
                    <div class="col-6 h-100">
                        <div class="card h-100">
                            <div class="card-body">
                                <div class="card-title">
                                    <h2>Contact Us</h2>
                                    <h7>Lorem ipsuAsperiores, error?</h7>
                                </div>
                                <p class="card-text">
                                    <input type="text" class="w-50">
                                    <input type="text" class="w-50">
                                    <input type="text" class="w-100">

                                </p>
                                <a href="#" class="my_btn bg_myprimary">SEND | -></a>
                            </div>

                        </div>
                    </div>
                </div>
            </div>

            <!--Una serie di loghi-->
            <div class="logos">
                <div class="row row-cols-5">
                    <div class="col">
                        <img src="../assets/img/clients/h4-clients-img-01.png" alt="">
                    </div>
                </div>
            </div>
        </div>
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
