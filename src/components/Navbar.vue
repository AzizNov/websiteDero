<template>
  <nav class="bg-amber-500 text-black shadow-lg sticky top-0 z-50">
    <div class="container mx-auto px-4 py-3 flex justify-between items-center">
      <div class="flex items-center space-x-2">
        <img src="/print-solid.svg" class="w-5 h-5" />
        <a href="#" class="text-xl font-bold">Toko Tinta</a>
      </div>
      <div class="hidden md:flex space-x-6">
        <a href="#home" class="hover:underline transition">Beranda</a>
        <a href="#about" class="hover:underline transition">Tentang Kami</a>
        <a href="#products" class="hover:underline transition">Produk</a>
        <a href="#services" class="hover:underline transition">Layanan</a>
        <a href="#contact" class="hover:underline transition">Kontak</a>
      </div>
      <div class="md:hidden">
        <button id="mobile-menu-button" class="text-white focus:outline-none">
          <i class="fas fa-bars text-2xl"></i>
        </button>
      </div>
    </div>
    <!-- Mobile Menu -->
    <div id="mobile-menu" class="hidden md:hidden bg-blue-700 px-4 pb-4">
      <a href="#home" class="block py-2 hover:underline transition">Beranda</a>
      <a href="#about" class="block py-2 hover:underline transition">Tentang Kami</a>
      <a href="#products" class="block py-2 hover:underline transition">Produk</a>
      <a href="#services" class="block py-2 hover:underline transition">Layanan</a>
      <a href="#contact" class="block py-2 hover:underline transition">Kontak</a>
    </div>
  </nav>
</template>
