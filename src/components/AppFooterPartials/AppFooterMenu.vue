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
            <h6 class="p-1">{{ section.title }}</h6>
            <div class="my_line riga m-2">----</div>
            <div class="footer_wrapper d-flex pt-1" v-for="inside in section.body.insides">
                <i class="" :class="inside.icon"></i>
                <p>{{ inside.text }}</p>
            </div>
            <i v-for="icon in section.bottomicons" :class="icon"></i>
        </section>
    </div>
</template>

<style>

.footer_wrapper{
    i{
        padding: 0.5rem;
        color:var(--bool-bg-primary);
    }
}
</style>