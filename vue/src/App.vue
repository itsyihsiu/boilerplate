<script setup>
</script>

<template>
  <nav class="flex gap-3">
    <router-link to="/">Go to Home</router-link>
    <router-link to="/about">Go to About</router-link>
  </nav>
  
  <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
    Button
  </button>

  <main>
    <router-view />
  </main>
</template>

<style scoped>

</style>
