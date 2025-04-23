<template>
  <div class="product-card bg-white rounded-lg overflow-hidden shadow-md border border-gray-200">
    <img :src="image" :alt="title" class="w-full h-48 object-cover" />
    <div class="p-6">
      <h4 class="text-xl font-semibold mb-2">{{ title }}</h4>
      <p class="text-gray-600 mb-4">{{ description }}</p>
      <div class="flex justify-between items-center">
        <span class="text-lg font-bold text-black">{{ price }}</span>
        <a :href="waLink" target="_blank" rel="noopener noreferrer"
          class="bg-[#f8b62d] text-white py-2 px-4 rounded transition inline-block">
          Beli
        </a>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { computed } from 'vue'

const props = defineProps<{
  image: string
  title: string
  description: string
  price: string
}>()

const waNumber = '6281293651300'
const message = computed(() =>
  `Halo, saya tertarik dengan produk "${props.title}" (${props.price}). Saya ingin menanyakan lebih lanjut tentang produk ini.`
)

const waLink = computed(() =>
  `https://wa.me/${waNumber}?text=${encodeURIComponent(message.value)}`
)
</script>
