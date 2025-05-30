<template>
  <div
    class="bg-white rounded-lg shadow-md overflow-hidden transform transition duration-300 hover:scale-105"
  >
    <div class="p-4 flex justify-center items-center h-48">
      <img
        :src="imageSrc"
        :alt="productName"
        class="max-h-full max-w-full object-contain"
      />
    </div>
    <div class="p-4 border-t border-gray-100 text-center">
      <h3 class="text-lg font-semibold text-gray-700 mb-4">
        {{ productName }}
      </h3>
      <a
        :href="waLink"
        target="_blank"
        class="inline-block bg-green-500 hover:bg-green-600 text-white font-semibold py-2 px-6 rounded-lg text-sm transition duration-300 ease-in-out"
      >
        WhatsApp Kami
      </a>
    </div>
  </div>
</template>

<script setup lang="ts">
import { computed } from "vue";

const props = defineProps<{
  imageSrc: string;
  productName: string;
}>();

const waNumber = "6281293651300";
const message = computed(
  () =>
    `Halo Dero, saya tertarik dengan produk "${props.title}" (${props.price}). Saya ingin menanyakan lebih lanjut tentang produk ini.`,
);

const waLink = computed(
  () => `https://wa.me/${waNumber}?text=${encodeURIComponent(message.value)}`,
);
</script>
