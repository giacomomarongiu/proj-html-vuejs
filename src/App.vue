<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFooter from "./components/AppFooter.vue"

export default {
  name: "App",
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  },
  data() {
    return {

    }
  }
}
</script>

<template>

  <body class="">
    <AppHeader />
    <AppMain />
    <AppFooter />
  </body>

</template>

<style></style>
