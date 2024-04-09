<script>
    export default {
        name: "AppHeaderMenu",
        props: {
            option: String
        },
        data() {
            return {
                menuOptions: ['HOMES', 'PAGES', 'BLOG', 'SHOP', 'EVENTS', 'ELEMENTS',],
                menuIcons: ['fa-solid fa-magnifying-glass', 'fa-solid fa-bars']
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