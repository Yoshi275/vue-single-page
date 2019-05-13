<template>
    <span>
        <home-hero></home-hero>
    </span>
</template>

<script>
// @ is an alias to /src
import HomeHero from "@/components/HomeHero.vue";
import HomeDetails from"@/components/HomeDetails.vue";

export default {
    name: "home",
    components: {
        HomeHero,
        HomeDetails
    }
};
</script>
