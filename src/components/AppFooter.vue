<script>
import AppFooterMenu from "./AppFooterPartials/AppFooterMenu.vue"

export default {
    name: "AppFooter",
    components: {
        AppFooterMenu,
    },
    data() {
        return {
            footerSections: [
                {
                    title: "About",
                    body: {
                        insides:
                            [{
                                text: 'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Officia, adipisci.',
                            },
                            ],
                    },
                    bottomicons: ["fa-brands fa-linkedin", "fa-brands fa-linkedin", "fa-brands fa-linkedin"]
                },
                {
                    title: "Twitter",
                    body: {
                        insides:
                            [{
                                icon: 'fa-brands fa-twitter',
                                text: 'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Officia, adipisci.',
                            },
                            {
                                icon: 'fa-brands fa-twitter',
                                text: 'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Officia, adipisci.',
                            }
                            ],
                    }
                },
                {
                    title: "Important Links",
                    body: {
                        insides:
                            [{
                                text: 'About me',
                            },
                            {
                                text: 'About us',
                            },
                            {
                                text: 'Language packs',
                            },
                            {
                                text: 'Monthly event',
                            }
                            ],
                    }
                },
                {
                    title: "Contact me",
                    body: {
                        insides:
                            [{
                                icon: 'fa-brands fa-twitter',
                                text: 'Lorem ipsum dolor sit ',
                            },
                            {
                                icon: 'fa-brands fa-twitter',
                                text: 'Lorem ipsum dolor sit ',
                            },
                            {
                                icon: 'fa-brands fa-twitter',
                                text: 'Lorem ipsum dolor sit ',
                            }
                            ],
                    }
                },
            ]
        }
    },

}
</script>

<template>
    <footer class="bg-dark py-5 m-auto">
        <div class="container  w-75">
            <div class="row py-5">
                <AppFooterMenu :section="section" v-for="section in footerSections" />
            </div>
        </div>
        <div class="text-light text-center bg-warning">Copyright</div>
    </footer>
</template>

<style></style>
