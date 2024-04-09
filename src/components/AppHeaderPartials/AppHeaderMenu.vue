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
        <a class="nav-link" href="#">
            <span class="arrow">
                <i class="fa-solid fa-arrow-right-long"></i></span>
            {{ option }}
        </a>
    </li>
</template>

<style></style>