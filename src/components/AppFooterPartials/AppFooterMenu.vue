<script>
export default {
    name: "AppFooterMenu",
    props: {
        section: Object
    },
    data() {
        return {

        }
    },
}
</script>

<template>
    <div class="col-3">
        <section class="text-light ">
            <h6 class="py-1">{{ section.title }}</h6>
            <div class="riga my-3">----</div>
            <div class="footer_wrapper d-flex pt-1" v-for="inside in section.body.insides">
                <i class="ps-0 pt-1" v-if="inside.icon" :class="inside.icon"></i>
                <p class="py-0 my-0">{{ inside.text }}</p>
            </div>
            <i class="pe-2 mt-4" v-for="icon in section.bottomicons" :class="icon"></i>
            <div class="footer_form pt-4 d-flex justify-content-between" v-if="section.input">
                <input type="text" placeholder="Your name..."
                    class="footer_input border-0 bg-transparent text-light ">
                <button class="border-0 bg-transparent text-light">SUBSCRIBE</button>
            </div>
        </section>
    </div>
</template>

<style>
.footer_wrapper {
    i {
        padding: 0.5rem;
        color: var(--bool-bg-primary);
    }

}
</style>