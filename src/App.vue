<template>
    <div>
        <Navbar></Navbar>
        <app-footer></app-footer>
    </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";

export default {
    components: {
        Navbar,
        "app-footer": Footer,
    },
    data() {
        return {};
    },
};
</script>

<style></style>
