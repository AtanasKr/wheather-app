<template>
  <main class="container text-white">
    <div class="pt-4 mb-8 relative">
      <input type="text" placeholder="Search for city or state"
      v-model="searchQuery"
      class="py-2 px-1 w-full bg-transparent border-b focus:border-wather-secondary focus:outline-none focus:shadow-[0px_1px_0_0_#004E71]">
    </div>
  </main>
</template>

<script setup>
const searchQuery = ref("")
</script>
