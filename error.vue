<script setup>
const error = useError()
const handleError = () => {
    navigateTo('/')
}
</script>

<template>
    <div class="flex h-screen justify-center items-center flex-col">
        <h1 class="text-9xl">{{ error.statusCode }}</h1>
        <p class="mt-7 text-4xl">{{ error.message }}</p>
        <button @click="handleError()" class="mt-7 text-2xl px-7 py-4 text-white rounded bg-blue-400">Go Back</button>
    </div>
</template>