<template>
  <DefaultLayout>
    <HeroSection />
    <AboutSection />
    <StatSection />
    <ProductSection />
    <ServiceSession />
    <div class="h-96 w-full">
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3966.28363477742!2d106.72519059999999!3d-6.226284799999999!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69f182fc348195%3A0xc7585dcf28450a6a!2sDERO%20CARTRIDGE%20Jual%20Beli%20Cartridge%20Toner%20Tinta%20Terdekat%20HP%20EPSON!5e0!3m2!1sid!2sid!4v1746764992809!5m2!1sid!2sid"
        width="100%"
        height="100%"
        style="border: 0"
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade"
      ></iframe>
    </div>
  </DefaultLayout>
</template>

<script setup lang="ts">
import AboutSection from "./components/AboutSection.vue";
import HeroSection from "./components/HeroSection.vue";
import ProductSection from "./components/ProductSection.vue";
import ServiceSession from "./components/ServiceSection.vue";
import StatSection from "./components/StatSection.vue";
import DefaultLayout from "./layouts/DefaultLayout.vue";
</script>
