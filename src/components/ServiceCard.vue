<template>
  <div class="bg-[#f8b62d] p-6 rounded-lg shadow-md border border-gray-200">
    <!-- <div class="text-blue-600 mb-4">
      <i :class="[icon, 'text-4xl']"></i>
    </div> -->
    <h3 class="text-xl font-bold mb-3">{{ title }}</h3>
    <p>{{ description }}</p>
  </div>
</template>

<script setup lang="ts">
defineProps({
  // icon: String,
  title: String,
  description: String,
})
</script>
