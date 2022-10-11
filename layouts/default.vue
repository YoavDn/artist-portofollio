<script setup lang="ts">
import Footer from '~/components/Footer.vue'
import Navbar from '~/components/Navbar.vue'
</script>

<template>
  <div id="app-layout">
    <main id="app">
      <Navbar />
      <slot />
      <Footer />
    </main>
  </div>
</template>
