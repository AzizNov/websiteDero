<template>
  <section id="services" class="py-16">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-4 text-black">Layanan Kami</h2>
      <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">
        Selain menjual produk tinta printer, kami juga menyediakan berbagai layanan terkait printer.
      </p>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <ServiceCard v-for="(service, index) in services" :key="index" :icon="service.icon" :title="service.title"
          :description="service.description" />
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import ServiceCard from './ServiceCard.vue'

interface Services {
  icon: string
  title: string
  description: string
}
const services: Services[] = [
  {
    icon: 'fas fa-syringe',
    title: 'Jual Beli Tinta',
    description: 'Layanan isi ulang tinta printer dengan kualitas terbaik dan harga terjangkau untuk semua merek printer.',
  },
  {
    icon: 'fas fa-truck',
    title: 'Pengiriman Cepat',
    description: 'Pengiriman produk ke seluruh wilayah dengan cepat dan aman.',
  },
  {
    icon: 'fas fa-exchange-alt',
    title: 'Jual Beli Cartridge',
    description: 'Jual beli cartridge printer original dan refill, baik baru maupun bekas.',
  },
]
</script>
