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
    <div id="latestnews" class="container pt-5">
        <!--Due bei div al 50%-->
        <div id="creativeleader" class="d-flex container pt-5">
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
        <!--Titles-->
        <div class="titles text-center">
            <h2>Latest news</h2>
            <h7>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores, error?</h7>
        </div>

        <!--carousel News-->
        <div id="carouselFour" class="carousel carousel-dark slide w-100">
            <div class="carousel-inner">
                <div class="carousel-item active" data-bs-interval="10000">
                    <!--Row with cards-->
                    <div class="row m-5">
                        <div class="col-4">
                            <div class="card">
                                <div class="card-body">
                                    <img src="../" class="d-block w-100">
                                    <h5 class="card-title">Card title</h5>
                                    <p class="card-text">Some quick example text to build on the card title and
                                        make
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
                                    <p class="card-text">Some quick example text to build on the card title and
                                        make
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
                                    <p class="card-text">Some quick example text to build on the card title and
                                        make
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
</template>

<style></style>