<script>
export default {
    name: "MainContactUs",
    data() {
        return {

        }
    },
}
</script>

<template>
    <div id="contactus" class="py-5 w-75 m-auto">

        <!--Due bei div al 50%-->
        <div class="d-flex">
            <div class="row py-5">
                <div class="col-6">
                    <div class="card position-relative">
                        <img src="/public/img/contactus/h1-contact-rev-01.png" class="d-block w-100">
                        <div class="position-absolute location">
                            <img class="location" src="/public/img/contactus/h1-contact-rev-02.png" alt="">
                            <div class="where">
                                <h5>New York Coaching</h5>
                                <h6 class="fw-bold">READ MORE</h6>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-6 h-100">
                    <div class="card h-100">
                        <div class="card-body">
                            <div class="card-title">
                                <h2>Contact Us.</h2>
                                <h6>Lorem ipsuAsperiores, error?</h6>
                            </div>
                            <p class="card-text row ">
                                <input type="text" class="px-1 col-6 my_input" placeholder="Your Name">
                                <input type="text" class="px-1 col-6 my_input" placeholder="Your Name">
                                <input type="text" class="px-1 my_input align-self-end" placeholder="Your Name">
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
                <div class="col">
                    <img src="../assets/img/clients/h4-clients-img-03.png" alt="">
                </div>
                <div class="col">
                    <img src="../assets/img/clients/h4-clients-img-05.png" alt="">
                </div>
                <div class="col">
                    <img src="../assets/img/clients/h4-clients-img-07.png" alt="">
                </div>
                <div class="col">
                    <img src="../assets/img/clients/h4-clients-img-09.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style>
.location {
    top: 40%;
    left: 20%
}

.where {
    background: white;
    padding: 0.5rem 1rem;
    border: 1px solid black;
}

.my_input{
    border: none;
    border-bottom: 1px solid black;
}
</style>