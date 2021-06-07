<template>
    <div
        class="text-center bg-image vh-100"
        v-bind:style="{ backgroundImage: 'url(' + img + ')' }"
    >
        <div>
            <div
                class="d-flex justify-content-center align-items-center vh-100 repeat-norepeat"
            >
                <div class="text-white ms-5 me-5">
                    <h1 class="mb-3">Vue Leboration 1</h1>
                    <h4 class="mb-3">
                        Hi, I'm Regan, a student in Lexicon's frontend developer
                        program for vocational education(yrkesutbildning).This
                        is my first leboration for Vue. The purpose of it is to
                        show I know how to create a basic componet in Vue.
                    </h4>
                    <h4 class="mb-3">
                        In the browser dev-tools, open the console and look for
                        the click event when the button below is clicked.
                    </h4>
                    <button
                        v-on:click="click"
                        type="button"
                        class="btn btn-outline-light btn-lg"
                    >
                        Call to action!
                    </button>
                </div>
            </div>
        </div>
    </div></template
>

<script>
export default {
    data() {
        return {
            img: require("@/assets/laptop.jpeg"),
        };
    },
    methods: {
        click() {
            console.log("Button in hero section clicked!");
        },
    },
};
</script>

<style scoped></style>
