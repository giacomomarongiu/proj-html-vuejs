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
            <h6>{{ section.title }}</h6>
            <div class="my_line text-warning">___</div>
            <div class="footer_wrapper d-flex" v-for="inside in section.body.insides">
                <i class="" :class="inside.icon"></i>
                <p>{{ inside.text }}</p>
            </div>
            <i v-for="icon in section.bottomicons" :class="icon"></i>
        </section>
    </div>
</template>

<style></style>