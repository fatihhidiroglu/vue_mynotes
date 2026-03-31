<script setup lang="ts">
import AppFooter from "./components/AppFooter.vue";
import AppNavbar from "./components/AppNavbar.vue";
</script>

<template>
  <RouterView />
</template>

<style>
#app {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
</style>
