<script>
export default {
    name: "AppFooter",

    data() {
        return {
            footerSections:[
                {
                    title: "Twitter",
                    icons: ['<i class="fa - brands fa - twitter"></i>', '<i class="fa - brands fa - twitter"></i>'],
                    texts: ['Lorem ipsum dolor sit amet consectetur, adipisicing elit. Officia, adipisci.','Lorem ipsum dolor sit amet consectetur, adipisicing elit. Officia, adipisci.']
                }
            ]
        }
    },

}
</script>

<template>
    <footer class="bg-dark py-5 m-auto">
        <div class="container  w-75">
            <div class="row py-5">
                <div class="col-3">
                    <section class="text-light">
                        <h6>Pippo</h6>
                        <div>___</div>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Officia, adipisci.</p>
                    </section>
                </div>
            </div>
        </div>
        <div class="text-light text-center bg-warning">Copyright</div>
    </footer>
</template>

<style scoped></style>
