<template>
  <div id="products" class="font-sans antialiased text-gray-800">
    <section class="py-12 px-4 sm:px-6 lg:px-8 text-center bg-white">
      <h2 class="text-3xl font-bold mb-4">Produk Kami</h2>
      <p class="text-lg text-gray-600 mb-8 max-w-2xl mx-auto">
        Kami menyediakan berbagai macam tinta printer untuk semua merek printer
        terkenal dengan kualitas terjamin.
      </p>
      <div class="flex flex-wrap justify-center items-center gap-8">
        <BrandLogo
          v-for="(brand, index) in brands"
          :key="index"
          :logo="brand.logo"
          :name="brand.name"
        />
      </div>
    </section>

    <section class="py-12 px-4 sm:px-6 lg:px-8 bg-gray-50">
      <h2 class="text-3xl font-bold text-center mb-10">Produk Unggulan Kami</h2>

      <div
        class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6 xl:gap-8 max-w-6xl mx-auto"
      >
        <ProductCard
          v-for="(product, index) in products"
          :key="index"
          :imageSrc="product.imageSrc"
          :productName="product.title"
        />
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
import BrandLogo from "./BrandLogo.vue";
import ProductCard from "./ProductCard.vue";

interface Brand {
  logo: string;
  name: string;
}

interface Product {
  imageSrc: string;
  title: string;
}

const brands: Brand[] = [
  { logo: "https://logo.clearbit.com/hp.com", name: "HP" },
  { logo: "https://logo.clearbit.com/canon.com", name: "Canon" },
  { logo: "https://logo.clearbit.com/epson.com", name: "Epson" },
  { logo: "https://logo.clearbit.com/brother.com", name: "Brother" },
  { logo: "https://logo.clearbit.com/xerox.com", name: "Xerox" },
  { logo: "https://logo.clearbit.com/samsung.com", name: "Samsung" },
];

const products: Product[] = [
  {
    id: 1,
    title: "HP 76A Original LaserJet",
    imageSrc: "/products/laserjet-871.avif",
  },
  {
    id: 2,
    title: "HP 87A Original LaserJet",
    imageSrc: "/products/laserjet-76a.avif",
  },
  {
    id: 3,
    title: "HP 147A Original LaserJet",
    imageSrc: "/products/hp-laserjet-147a.avif",
  },
  {
    id: 4,
    title: "HP 680 Original Ink Advantage Cartridge",
    imageSrc: "/products/hp-680.webp",
  },
  {
    id: 5,
    title: "HP 682 Original Ink Advantage Cartridge",
    imageSrc: "/products/hp-682.webp",
  },
  {
    id: 6,
    title: "HP 802 Original Ink Advantage Cartridge",
    imageSrc: "/products/hp-802.webp",
  },
  {
    id: 7,
    title: "HP 803 Original Ink Advantage Cartridge",
    imageSrc: "/products/hp-803.webp",
  },
  {
    id: 8,
    title: "HP 955 Original Ink Advantage Cartridge",
    imageSrc: "/products/hp-955.webp",
  },
  {
    id: 9,
    title: "HP GT52 Original Ink Advantage Cartridge",
    imageSrc: "/products/hp-gt52.webp",
  },
  {
    id: 10,
    title: "Canon 810 Original Ink",
    imageSrc: "/products/cartridge-canon-810.jpg",
  },
  {
    id: 11,
    title: "Brother 5000 Original Ink",
    imageSrc: "/products/tinta-brother-5000.png",
  },
  {
    id: 12,
    title: "Brother 563 Original Ink",
    imageSrc: "/products/tinta-brother-lc563.png",
  },
];
</script>
