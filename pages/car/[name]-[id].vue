<script setup>
const route = useRoute();
useHead({
    title: toCapetalize(route.params.name)
});

function toCapetalize(string) {
    return string.charAt(0).toUpperCase() + string.slice(1);
}
</script>

<template>
    <div>
        <!-- <NavBar /> -->
        <div class="mx-auto mb-96 max-w-7xl space-y-4 px-4 xs:px-8 sm:px-10 lg:px-16 pb-16 w-3/5">
            <CarDetailHero />

            <CarAttribute />

            <CarDescription />

            <CarContact />

        </div>
    </div>
</template>