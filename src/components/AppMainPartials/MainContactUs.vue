<script>
export default {
    name: "MainContactUs",
    data() {
        return {
            logos: [
                {
                    main: "01",
                    hover: "02",
                },
                {
                    main: "03",
                    hover: "04",
                },
                {
                    main: "05",
                    hover: "06",
                },
                {
                    main: "07",
                    hover: "08",
                },
                {
                    main: "09",
                    hover: "10",
                },
            ]
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
                    <div class="card position-relative border border-0">
                        <img src="/public/img/contactus/h1-contact-rev-01.png" class="d-block w-100">
                        <div class="position-absolute location shadow-sm">
                            <img class="location" src="/public/img/contactus/h1-contact-rev-02.png" alt="">
                            <div class="where">
                                <h6 class="fw-bold">New York Coaching</h6>
                                <p class="fw-bold my_text_smaller mb-1">READ MORE</p>
                            </div>
                        </div>
                        <div class="position-absolute locationtwo shadow-sm">
                            <img class=" " src="/public/img/contactus/h1-contact-rev-02.png" alt="">
                        </div>
                        <div class="position-absolute locationthree shadow-sm">
                            <img class="" src="/public/img/contactus/h1-contact-rev-02.png" alt="">
                        </div>
                    </div>
                </div>

                <div class="col-6 h-100">
                    <div class="card h-100 border border-0">
                        <div class="card-body">
                            <div class="card-title">
                                <h2 class="fw-bold">Contact Us<span class="text_myprimary">.</span></h2>
                                <div>Lorem ipsuAsperiores, error?</div>
                                <div class="riga my-3">_________</div>
                            </div>
                            <p class="row gy-4 column-gap-1 justify-content-between">
                                <input type="text" class="my_input col-5" placeholder="Your name...">
                                <input type="text" class="my_input col-5" placeholder="Your email...">
                                <input type="text" class="my_input pb-5" placeholder="Some text...">
                            </p>
                            <button class="border border-0 bg_myprimary w-25 my_text_smaller py-3 fw-bold bg_mypr">SEND <span class="linebye">|</span>
                                &#10230;</button>
                        </div>

                    </div>
                </div>
            </div>
        </div>

        <!--Una serie di loghi-->
        <div class="logos">
            <div class="row row-cols-5">
                <div class="col" v-for="logo in logos">
                    <img class="main-img" :src="'/public/img/clients/h4-clients-img-' + logo.main + '.png'" alt="">
                    <img class="hover-img" :src="'/public/img/clients/h4-clients-img-' + logo.hover + '.png'" alt="">
                </div>
            </div>
        </div>

    </div>
</template>

<style>
.location {
    top: 40%;
    left: 22%
}

.locationtwo {
    top: 72%;
    right: 13%
}

.locationthree {
    top: 22%;
    right: 45%
}

.where {
    background: white;
    padding: 0.5rem 1rem;

}

.my_input {
    border: none;
    border-bottom: 1px solid black;
}

.hover-img {
    visibility: hidden;
    opacity: 0;
    transition: visibility 0s, opacity 0.5s linear;
}

.col:hover {
    .main-img {
        display: none;
        visibility: hidden;
    }

    .hover-img {
        visibility: visible;
        opacity: 1;
    }
}
</style>