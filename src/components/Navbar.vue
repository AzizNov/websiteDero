<template>
  <nav class="bg-[#f8b62d] text-black shadow-lg sticky top-0 z-50">
    <div class="container mx-auto px-4 py-3 flex justify-between items-center">
      <!-- Logo -->
      <div class="flex items-center space-x-2">
        <img src="/logo.png" class="w-5 h-5" />
        <a href="#" class="text-xl font-bold">Dero Cartridge</a>
      </div>

      <!-- Desktop Menu -->
      <div class="hidden md:flex space-x-6">
        <a href="#home" class="hover:underline transition">Beranda</a>
        <a href="#about" class="hover:underline transition">Tentang Kami</a>
        <a href="#products" class="hover:underline transition">Produk</a>
        <a href="#services" class="hover:underline transition">Layanan</a>
      </div>

      <!-- Mobile Hamburger -->
      <div class="md:hidden">
        <button @click="isMobileMenuOpen = !isMobileMenuOpen" class="text-white focus:outline-none">
          <img src="/bars-solid.svg" alt="bars" class="w-6 h-6 text-black">
        </button>
      </div>
    </div>

    <!-- Mobile Menu -->
    <div v-if="isMobileMenuOpen" class="md:hidden bg-[#f8b62d] px-4 pb-4">
      <a @click="isMobileMenuOpen = false" href="#home" class="block py-2 hover:underline transition">Beranda</a>
      <a @click="isMobileMenuOpen = false" href="#about" class="block py-2 hover:underline transition">Tentang Kami</a>
      <a @click="isMobileMenuOpen = false" href="#products" class="block py-2 hover:underline transition">Produk</a>
      <a @click="isMobileMenuOpen = false" href="#services" class="block py-2 hover:underline transition">Layanan</a>
    </div>
  </nav>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const isMobileMenuOpen = ref(false)
</script>
