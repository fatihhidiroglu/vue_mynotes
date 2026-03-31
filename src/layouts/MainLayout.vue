<template>
  <AppNavbar />
  <main class="grow container mx-auto px-4">
    <slot />
  </main>
  <AppFooter />
</template>

<script setup lang="ts">
import AppFooter from "@/components/AppFooter.vue";
import AppNavbar from "@/components/AppNavbar.vue";
</script>

<style scoped></style>
