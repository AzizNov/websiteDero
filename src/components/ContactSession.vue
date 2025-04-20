<template>
  <section class="py-16">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-4 text-amber-700">Hubungi Kami</h2>
      <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">Silakan hubungi kami untuk informasi produk, layanan,
        atau pertanyaan lainnya.</p>

      <div class="flex flex-col lg:flex-row gap-8">
        <div class="lg:w-1/2">
          <div class="bg-white p-6 rounded-lg shadow-md border border-gray-200">
            <h3 class="text-xl font-semibold mb-6 text-amber-600">Kirim Pesan</h3>
            <form id="contact-form">
              <div class="mb-4">
                <label for="name" class="block text-gray-700 mb-2">Nama Lengkap</label>
                <input type="text" id="name" name="name"
                  class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"
                  required>
              </div>
              <div class="mb-4">
                <label for="email" class="block text-gray-700 mb-2">Email</label>
                <input type="email" id="email" name="email"
                  class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"
                  required>
              </div>
              <div class="mb-4">
                <label for="phone" class="block text-gray-700 mb-2">Nomor Telepon</label>
                <input type="tel" id="phone" name="phone"
                  class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
              </div>
              <div class="mb-4">
                <label for="message" class="block text-gray-700 mb-2">Pesan</label>
                <textarea id="message" name="message" rows="4"
                  class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"
                  required></textarea>
              </div>
              <button type="submit"
                class="bg-amber-600 hover:bg-blue-700 text-white font-bold py-2 px-6 rounded-lg transition w-full">Kirim
                Pesan</button>
            </form>
          </div>
        </div>

        <div class="lg:w-1/2">
          <div class="bg-white p-6 rounded-lg shadow-md border border-gray-200 h-full">
            <h3 class="text-xl font-semibold mb-6 text-amber-600">Informasi Kontak</h3>

            <div class="space-y-6">
              <div class="flex items-start">
                <div class="text-blue-600 mr-4 mt-1">
                  <i class="fas fa-map-marker-alt text-2xl"></i>
                </div>
                <div>
                  <h4 class="font-semibold mb-1">Alamat Toko</h4>
                  <p class="text-gray-600">Jl. Printer No. 123, Kel. Tinta Sejahtera, Kec. Cartridge, Kota Jakarta
                    Selatan, DKI Jakarta 12345</p>
                </div>
              </div>

              <div class="flex items-start">
                <div class="text-blue-600 mr-4 mt-1">
                  <i class="fas fa-phone-alt text-2xl"></i>
                </div>
                <div>
                  <h4 class="font-semibold mb-1">Telepon</h4>
                  <p class="text-gray-600">(021) 12345678</p>
                  <p class="text-gray-600">0812-3456-7890 (WhatsApp)</p>
                </div>
              </div>

              <div class="flex items-start">
                <div class="text-blue-600 mr-4 mt-1">
                  <i class="fas fa-envelope text-2xl"></i>
                </div>
                <div>
                  <h4 class="font-semibold mb-1">Email</h4>
                  <p class="text-gray-600">info@namatokotinta.com</p>
                  <p class="text-gray-600">cs@namatokotinta.com</p>
                </div>
              </div>

              <div class="flex items-start">
                <div class="text-blue-600 mr-4 mt-1">
                  <i class="fas fa-clock text-2xl"></i>
                </div>
                <div>
                  <h4 class="font-semibold mb-1">Jam Operasional</h4>
                  <p class="text-gray-600">Senin - Jumat: 08.00 - 17.00 WIB</p>
                  <p class="text-gray-600">Sabtu: 08.00 - 15.00 WIB</p>
                  <p class="text-gray-600">Minggu & Hari Libur: Tutup</p>
                </div>
              </div>
            </div>

            <!-- <div class="mt-8">
              <h4 class="font-semibold mb-4 text-blue-700">Ikuti Kami</h4>
              <div class="flex space-x-4">
                <a href="#"
                  class="bg-blue-600 text-white rounded-full w-10 h-10 flex items-center justify-center hover:bg-blue-700 transition">
                  <i class="fab fa-facebook-f"></i>
                </a>
                <a href="#"
                  class="bg-pink-600 text-white rounded-full w-10 h-10 flex items-center justify-center hover:bg-pink-700 transition">
                  <i class="fab fa-instagram"></i>
                </a>
                <a href="#"
                  class="bg-blue-400 text-white rounded-full w-10 h-10 flex items-center justify-center hover:bg-blue-500 transition">
                  <i class="fab fa-twitter"></i>
                </a>
                <a href="#"
                  class="bg-green-500 text-white rounded-full w-10 h-10 flex items-center justify-center hover:bg-green-600 transition">
                  <i class="fab fa-whatsapp"></i>
                </a>
              </div>
            </div> -->
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
