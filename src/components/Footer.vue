<template>
  <footer class="bg-[#f8b62d] text-black py-12">
    <div class="container mx-auto px-4">
      <div class="grid grid-cols-1 md:grid-cols-4 gap-8">

        <!-- Logo & Deskripsi -->
        <div>
          <div class="flex items-center space-x-2 mb-4">
            <img src="/logo.png" class="w-10 h-10" />
            <span class="text-xl font-bold">Dero Cartidge</span>
          </div>
          <p class="">
            🖨️ Jual tinta & toner cartridge berbagai tipe, baik baru maupun bekas! Cocok untuk kebutuhan rumah, kantor, atau bisnis Anda. Kualitas terjamin, harga bersahabat!</p>
        </div>

        <!-- Tautan Cepat -->
        <div>
          <h4 class="text-lg font-semibold mb-4">Tautan Cepat</h4>
          <ul class="space-y-2 ">
            <li><a href="#home" class="hover:underline transition">Beranda</a></li>
            <li><a href="#about" class="hover:underline transition">Tentang Kami</a></li>
            <li><a href="#products" class="hover:underline transition">Produk</a></li>
            <li><a href="#services" class="hover:underline transition">Layanan</a></li>
            <li><a href="#contact" class="hover:underline transition">Kontak</a></li>
          </ul>
        </div>

        <!-- Informasi Kontak -->
        <div class="md:col-span-2">
          <h3 class="text-lg font-semibold mb-4">Informasi Kontak</h3>
          <div class="grid grid-cols-1 md:grid-cols-2 gap-6">

            <!-- Alamat -->
            <div class="flex items-start gap-3">
              <img src="/location-dot-solid.svg" class="w-5 h-5" />
              <div>
                <h4 class="font-semibold mb-1">Alamat Toko</h4>
                <p class="">
                  Gor larangan, Jl. Ciledug Raya, Larangan Utara, Kec. Larangan, Kota Tangerang, Banten 15154
                  Sosial Media
                </p>
              </div>
            </div>

            <!-- Telepon -->
            <div class="flex items-start gap-3">
              <img src="/phone-solid.svg" class="w-5 h-5" />
              <div>
                <h4 class="font-semibold mb-1">Telepon</h4>
                <p class="">0812-9365-1300 (WhatsApp)</p>
              </div>
            </div>

            <!-- Email
            <div class="flex items-start gap-3">
              <img src="/envelope-solid.svg" class="w-5 h-5" />
              <div>
                <h4 class="font-semibold mb-1">Email</h4>
                <p class="">info@namatokotinta.com</p>
                <p class="">cs@namatokotinta.com</p>
              </div>
            </div> -->

            <!-- Jam Operasional -->
            <div class="flex items-start gap-3">
              <img src="/clock-solid.svg" class="w-5 h-5" />
              <div>
                <h4 class="font-semibold mb-1">Jam Operasional</h4>
                <p class="">Tiap Hari buka</p>
              </div>
            </div>

          </div>
        </div>

      </div>
      <div class="border-t border-black mt-12 pt-6 text-center">
        <p class="">&copy; 2025 Dero Catridge. All rights reserved.</p>
      </div>
    </div>
  </footer>
</template>
