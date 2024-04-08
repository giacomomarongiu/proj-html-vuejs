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
    <!--Divided in 4 Sections-->

    <!--1st section Our Specialities-->
    <div id="ourspecialties">
        <div class="container">
            <!--Titles-->
            <div class="titles">
                <h2>Our Specialities</h2>
                <h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores, error?</h3>
            </div>

            <!--Row with cards-->
            <div class="row m-5">
                <div class="col-3">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk
                                of the card's content.</p>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk
                                of the card's content.</p>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk
                                of the card's content.</p>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk
                                of the card's content.</p>
                        </div>
                    </div>
                </div>
            </div>

            <!--Carosuel and text-->
            <div class="d-flex">
                <!--Carosuel-->
                <div id="carouselExampleDark" class="carousel carousel-dark slide w-50">
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active"
                            aria-current="true" aria-label="Slide 1"></button>
                        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1"
                            aria-label="Slide 2"></button>
                        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2"
                            aria-label="Slide 3"></button>
                    </div>
                    <div class="carousel-inner">
                        <div class="carousel-item active" data-bs-interval="10000">
                            <img src="../assets/img/01.jpg" class="d-block w-100">
                            <div class="carousel-caption d-none d-md-block">
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

                <!--Text-->
                <div class="col">
                    <div class="card">
                        <div class="card-body">
                            <div class="card-title">Jason Bickford</div>
                            <div class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore,
                                harum.</div>
                            <div>Pippo Pluto Paperino</div>
                        </div>
                    </div>
                </div>
            </div>

            <!--Due bei div al 50%-->
            <div class="d-flex">
                <div class="row">
                    <div class="col-6">
                        <div class="card">
                            <div class="card-title">Jason Bickford</div>
                            <div class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore,
                                harum. Lorem ipsum, dolor sit amet consectetur adipisicing elit. Id, debitis expedita?
                                Nesciunt architecto totam similique velit repudiandae quod voluptates tempore unde
                                molestias maxime consectetur distinctio iste accusantium praesentium laudantium
                                obcaecati culpa sed maiores, quam eligendi nostrum porro hic error esse! Sequi
                                blanditiis vero sed nulla neque qui, repudiandae voluptatum dolorem.</div>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="card">
                            <div class="card-title">Jason Bickford</div>
                            <div class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore,
                                harum.</div>
                            <div class="card-title">Jason Bickford</div>
                            <div class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore,
                                harum.</div>
                            <div class="card-title">Jason Bickford</div>
                            <div class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore,
                                harum.</div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <!--2nd Section-->
</template>

<style scoped></style>
