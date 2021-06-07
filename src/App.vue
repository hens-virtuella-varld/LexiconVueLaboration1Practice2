<template>
    <div>
        <Navbar></Navbar>
        <Hero></Hero>
        <app-footer></app-footer>
    </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Hero from "./components/Hero.vue";
import Footer from "./components/Footer.vue";

export default {
    components: {
        Navbar,
        Hero,
        "app-footer": Footer,
    },
    data() {
        return {};
    },
};
</script>

<style></style>
