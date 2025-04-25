<template>
  <section id="products" class="py-16">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-4 text-black">Produk Kami</h2>
      <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">
        Kami menyediakan berbagai macam tinta printer untuk semua merek printer terkenal dengan kualitas terjamin.
      </p>

      <!-- Brand Section -->
      <div class="mb-12">
        <h3 class="text-2xl font-semibold mb-6 text-black">Merek Printer yang Kami Dukung</h3>
        <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 gap-6">
          <BrandLogo v-for="(brand, index) in brands" :key="index" :logo="brand.logo" :name="brand.name" />
        </div>
      </div>

      <!-- Products Section -->
      <h3 class="text-2xl font-semibold mb-6 text-black">Produk Unggulan Kami</h3>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <ProductCard v-for="(product, index) in products" :key="index" :image="product.image" :title="product.title"
          :description="product.description" :price="product.price" />
      </div>

      <!-- CTA -->
      <!-- <div class="text-center mt-12">
        <a href="#" class="inline-block bg-amber-600 hover:bg-amber-600 text-white font-bold py-3 px-6 rounded-lg transition">
          Lihat Semua Produk
        </a>
      </div> -->
    </div>
  </section>
</template>

<script setup lang="ts">
import BrandLogo from './BrandLogo.vue'
import ProductCard from './ProductCard.vue'

interface Brand {
  logo: string
  name: string
}

interface Product {
  image: string
  title: string
  description: string
  price: string
}

const brands: Brand[] = [
  { logo: 'https://logo.clearbit.com/hp.com', name: 'HP' },
  { logo: 'https://logo.clearbit.com/canon.com', name: 'Canon' },
  { logo: 'https://logo.clearbit.com/epson.com', name: 'Epson' },
  { logo: 'https://logo.clearbit.com/brother.com', name: 'Brother' },
  { logo: 'https://logo.clearbit.com/xerox.com', name: 'Xerox' },
  { logo: 'https://logo.clearbit.com/samsung.com', name: 'Samsung' }
]

const products: Product[] = [
  {
    image: '/98.jpg',
    title: 'Tinta Pixma 98 Original',
    description: 'Tinta original untuk printer Canon Pixma',
    price: 'Rp 250.000'
  },
  {
    image: '/745.jpg',
    title: 'Tinta Pixma 745 Original',
    description: 'Tinta original untuk printer Canon Pixma',
    price: 'Rp 230.000'
  },
  {
    image: '/810-811.jpg',
    title: 'Tinta Pixma 810-811 Original',
    description: 'Tinta original untuk printer Canon Pixma',
    price: 'Rp 550.000'
  },
  {
    image: '/810-811.jpg',
    title: 'Tinta Pixma 810-811 Original',
    description: 'Tinta original untuk printer Canon Pixma',
    price: 'Rp 450.000'
  },
  {
    image: '/810-811.jpg',
    title: 'Tinta Pixma 810-811 Original',
    description: 'Tinta original untuk printer Canon Pixma',
    price: 'Rp 450.000'
  },
  {
    image: '/810-811.jpg',
    title: 'Tinta Pixma 810-811 Original',
    description: 'Tinta original untuk printer Canon Pixma',
    price: 'Rp 450.000'
  }
]
</script>
