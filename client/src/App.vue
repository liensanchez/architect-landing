<script>
import NavBar from "./components/NavBar.vue";
import HomeHero from "./components/HomeHero.vue";

export default {
    components: {
        NavBar,
        HomeHero
    },
    data() {
        return {
            optionSelected: "Home",
        };
    },
};
</script>

<template>
    <div class="home-container">
        <NavBar :optionSelected="optionSelected"/>
        <HomeHero />
    </div>

    
</template>

<style>
* {
    margin: 0;
    padding: 0;
}

.custom-container {
    width: 90%;
    max-width: 1920px;
}

.home-container {
    display: flex;
    flex-direction: column;
}
</style>
