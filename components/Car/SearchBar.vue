<script setup>
const city = ref("");
const cityError = ref(false);

const handleSearch = () => {
    if (!city.value) {
        console.log("inside if block")
        return cityError.value = true;
    }
    else {
        navigateTo(`/city/${city._value}/car`)
    }
    // router.push(`/city/${city._value}/car`)
}
</script>
<template>
    <div
        class="font-serif w-100 rounded-lg flex justify-between overflow-hidden border-0 bg-white drop-shadow-2xl mx-auto">
        <input type="text" v-model="city" class="py-3 px-5 w-full text-2xl focus:outline-none"
            :class="cityError ? 'test-border border-2 border-red-500' : ''" placeholder="Search by city...">
        <button class="bg-sky-500 px-10 text-white" @click="handleSearch()">search</button>
    </div>
</template>

<style scoped>
.test-border {
    border-top-left-radius: 0.50rem;
    border-bottom-left-radius: 0.5rem
}
</style>