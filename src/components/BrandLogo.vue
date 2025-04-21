<template>
  <div class="brand-logo flex flex-col items-center p-4">
    <img :src="logo" :alt="name" class="h-12 w-auto mb-2" />
    <span class="text-sm">{{ name }}</span>
  </div>
</template>

<script setup lang="ts">
defineProps<{
  logo: string
  name: string
}>()
</script>
