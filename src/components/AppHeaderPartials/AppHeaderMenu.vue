<script>
    export default {
        name: "AppHeaderMenu",
        props: {
            option: String
        },
        data() {
            return {

            }
        },
    }
</script>

<template>
    <li class="nav-item">
        <a class="nav-link" href="#">{{ option }}</a>
    </li>
</template>

<style>

</style>