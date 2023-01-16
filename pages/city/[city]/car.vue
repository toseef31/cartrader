<script setup>
const route = useRoute()
useHead({
    title: `${route.params.make ? toCapetalize(route.params.make) : 'Cars'} in ${route.params.city}`
})

function toCapetalize(string) {
    return string.charAt(0).toUpperCase() + string.slice(1);
}
</script>
<template>
    <div>
        <!-- <NavBar /> -->
        <div class="mx-auto mb-96 max-w-7xl space-y-4 px-4 xs:px-8 sm:px-10 lg:px-16 pb-16 w-4/5 ">
            <div class="mt-32 flex h-48">
                <CarSideBar />
                <NuxtPage />
                <!-- <CarCards /> -->
            </div>
        </div>
    </div>
</template>