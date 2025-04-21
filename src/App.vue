<template>
  <DefaultLayout>
    <HeroSection />
    <AboutSection />
    <StatSection />
    <ProductSection />
    <ServiceSession />
    <div class="h-96 w-full">
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3966.2831703060065!2d106.72513269999999!3d-6.2263462999999994!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69f118bd2c7d31%3A0x951be0e03b00db5!2sCALUCA%20PRINT%20Jual%20Tinta%20Printer%20%26%20Jual%20Beli%20Cartridge%20Tinta%20Toner%20Baru%20Dan%20Bekas!5e0!3m2!1sen!2sid!4v1745222313349!5m2!1sen!2sid"
        width="100%" height="100%" style="border:0;" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>
  </DefaultLayout>
</template>

<script setup lang="ts">
import AboutSection from './components/AboutSection.vue';
import HeroSection from './components/HeroSection.vue';
import ProductSection from './components/ProductSection.vue';
import ServiceSession from './components/ServiceSection.vue';
import StatSection from './components/StatSection.vue';
import DefaultLayout from './layouts/DefaultLayout.vue';
</script>
