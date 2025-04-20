<template>
  <section id="products" class="py-16">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-4 text-amber-600">Produk Kami</h2>
      <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">Kami menyediakan berbagai macam tinta printer untuk
        semua merek printer terkenal dengan kualitas terjamin.</p>

      <div class="mb-12">
        <h3 class="text-2xl font-semibold mb-6 text-amber-600">Merek Printer yang Kami Dukung</h3>
        <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 gap-6">
          <div class="brand-logo flex flex-col items-center p-4">
            <img src="https://logo.clearbit.com/hp.com" alt="HP" class="h-12 w-auto mb-2">
            <span class="text-sm">HP</span>
          </div>
          <div class="brand-logo flex flex-col items-center p-4">
            <img src="https://logo.clearbit.com/canon.com" alt="Canon" class="h-12 w-auto mb-2">
            <span class="text-sm">Canon</span>
          </div>
          <div class="brand-logo flex flex-col items-center p-4">
            <img src="https://logo.clearbit.com/epson.com" alt="Epson" class="h-12 w-auto mb-2">
            <span class="text-sm">Epson</span>
          </div>
          <div class="brand-logo flex flex-col items-center p-4">
            <img src="https://logo.clearbit.com/brother.com" alt="Brother" class="h-12 w-auto mb-2">
            <span class="text-sm">Brother</span>
          </div>
          <div class="brand-logo flex flex-col items-center p-4">
            <img src="https://logo.clearbit.com/xerox.com" alt="Xerox" class="h-12 w-auto mb-2">
            <span class="text-sm">Xerox</span>
          </div>
          <div class="brand-logo flex flex-col items-center p-4">
            <img src="https://logo.clearbit.com/samsung.com" alt="Samsung" class="h-12 w-auto mb-2">
            <span class="text-sm">Samsung</span>
          </div>
        </div>
      </div>

      <h3 class="text-2xl font-semibold mb-6 text-amber-600">Produk Unggulan Kami</h3>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Product 1 -->
        <div class="product-card bg-white rounded-lg overflow-hidden shadow-md border border-gray-200">
          <img
            src="https://images.unsplash.com/photo-1518770660439-4636190af475?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
            alt="Tinta Printer HP Original" class="w-full h-48 object-cover">
          <div class="p-6">
            <h4 class="text-xl font-semibold mb-2">Tinta HP 664 Original</h4>
            <p class="text-gray-600 mb-4">Tinta original untuk printer HP seri OfficeJet dan Deskjet</p>
            <div class="flex justify-between items-center">
              <span class="text-lg font-bold text-amber-600">Rp 150.000</span>
              <button class="bg-amber-600 hover:bg-amber-600 text-white py-2 px-4 rounded transition">Beli</button>
            </div>
          </div>
        </div>

        <!-- Product 2 -->
        <div class="product-card bg-white rounded-lg overflow-hidden shadow-md border border-gray-200">
          <img
            src="https://images.unsplash.com/photo-1518770660439-4636190af475?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
            alt="Tinta Printer Epson Compatible" class="w-full h-48 object-cover">
          <div class="p-6">
            <h4 class="text-xl font-semibold mb-2">Tinta Epson 003 Compatible</h4>
            <p class="text-gray-600 mb-4">Tinta compatible berkualitas tinggi untuk printer Epson</p>
            <div class="flex justify-between items-center">
              <span class="text-lg font-bold text-amber-600">Rp 75.000</span>
              <button class="bg-amber-600 hover:bg-amber-600 text-white py-2 px-4 rounded transition">Beli</button>
            </div>
          </div>
        </div>

        <!-- Product 3 -->
        <div class="product-card bg-white rounded-lg overflow-hidden shadow-md border border-gray-200">
          <img
            src="https://images.unsplash.com/photo-1518770660439-4636190af475?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
            alt="Toner Printer Brother" class="w-full h-48 object-cover">
          <div class="p-6">
            <h4 class="text-xl font-semibold mb-2">Toner Brother TN-660</h4>
            <p class="text-gray-600 mb-4">Toner original untuk printer laser Brother</p>
            <div class="flex justify-between items-center">
              <span class="text-lg font-bold text-amber-600">Rp 450.000</span>
              <button class="bg-amber-600 hover:bg-amber-600 text-white py-2 px-4 rounded transition">Beli</button>
            </div>
          </div>
        </div>
      </div>

      <div class="text-center mt-12">
        <a href="#"
          class="inline-block bg-amber-600 hover:bg-amber-600 text-white font-bold py-3 px-6 rounded-lg transition">Lihat
          Semua Produk</a>
      </div>
    </div>
  </section>
</template>
