<template>
  <DefaultLayout>
    <HeroSection />
    <AboutSection />
    <StatSection />
    <ProductSection />
    <ServiceSession />
    <ContactSession />
    <div class="h-96 w-full">
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d15864.78613104934!2d106.8271536!3d-6.1753926!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69f3e977790bfb%3A0x6c67664ef0f8a2a2!2sMonas!5e0!3m2!1sen!2sid!4v1614064092872!5m2!1sen!2sid"
        width="100%" height="100%" style="border:0;" loading="lazy">
      </iframe>
    </div>
  </DefaultLayout>
</template>

<script setup lang="ts">
import AboutSection from './components/AboutSection.vue';
import ContactSession from './components/ContactSession.vue';
import HeroSection from './components/HeroSection.vue';
import ProductSection from './components/ProductSection.vue';
import ServiceSession from './components/ServiceSession.vue';
import StatSection from './components/StatSection.vue';
import DefaultLayout from './layouts/DefaultLayout.vue';
</script>
