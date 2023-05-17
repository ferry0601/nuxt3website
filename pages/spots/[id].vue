<template>
  <div class=" container max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700 mx-5 px-5 my-10">
    <p class="mb-2 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white">Gambar pemandangan untuk {{ id }}</p>
    <p class="text-gray-900 dark:text-white">akan egera ditampilkan mulai dari beberapa minggu ke depan, untuk saat ini program lagi error</p>
  </div>
  <TheFooter />
</template>

<script setup>
    const { id } = useRoute().params
    
</script>

<style>

</style>