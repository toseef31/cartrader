<template>
    <div class="mt-10">
        <div class="flex justify-between w-full mb-4">
            <input type="text" name="name" placeholder="Name" class=" border p-1 ">
            <input type="email" name="email" placeholder="Email" class=" border p-1 ">
            <input type="number" name="phone" placeholder="Phone" class="border p-1 ">
        </div>
        <div class="w-full">
            <textarea name="description" rows="5" placeholder="Description" class="w-full border p-1"></textarea>
        </div>

        <button class="bg-blue-400 text-white px-10 py-3 rounded mt-4">Submit</button>
    </div>
</template>