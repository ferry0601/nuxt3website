<template>
    
    <div class="max-sm rounded overflow-hidden shadow-lg w-80 text-justify">
    <a href="#">
    <img class="w-full object-scale-down h-30 w-60 ... px-3 mx-5" :src= "image" alt="polo next" />
    <div class="px-6 py-4">
        <div class="font-bold text-xl mb-2 "> {{ title }} </div>
        <p class="text-gray-700 text-base w-60">{{ desc }}</p>
        
    </div>
    </a>
    </div>
    
</template>

<script setup>
    defineProps({
        title: {
            type: String,
        },
        desc: {
            type: String,
        },
        image: {
            type:String,
            required: true,
        },
    })
</script>