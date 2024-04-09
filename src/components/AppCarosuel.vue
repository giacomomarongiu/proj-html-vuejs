<script>

export default {
    name: "AppCarosuel",
    props: {
        carosuel: Object
    },
    data() {
        return {
            
        }
    },

}
</script>

<template>
    <!--Carosuel-->
    <!--Stampo l'id dinamicamente-->
    <div :id="carosuel.name" class="carousel slide">
        <div class="carousel-inner">
            <!--La prima immagine è sempre stampata e saraà quella attiva-->
            <div class="carousel-item active">>
                <img :src="carosuel.imgActive" class="d-block w-100" alt="...">
                <div class="carousel-caption text-dark text-start">
                    <h1 class="">Our Team</h1>
                    <p class="fs-6 text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione eveniet
                        dicta eaque quos atque veritatis saepe similique sequi ipsam mollitia?</p>
                    <button type="" class="my_btn bg_myprimary">READ MORE | -></button>
                    <button type="" class="my_btn bg_mylight">PURCHASE | -></button>
                </div>
            </div>

            <div class="carousel-item" v-for="item in carosuel.items">
                <img :src="item.imgUrl" class="d-block w-100" alt="...">
                <div class="carousel-caption text-dark text-start">
                    <h1 class="">{{ item.imgTitle }}</h1>
                    <p class="fs-6 text">{{item.imgText}}</p>
                    <button type="" class="my_btn bg_myprimary">READ MORE | -></button>
                    <button type="" class="my_btn bg_mylight">PURCHASE | -></button>
                </div>
            </div>
        </div>

        <button class="carousel-control-prev" type="button" :data-bs-target="'#'+ carosuel.name" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" :data-bs-target="'#'+ carosuel.name" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
</template>

<style></style>