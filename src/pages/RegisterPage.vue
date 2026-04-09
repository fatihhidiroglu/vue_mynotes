<template>
  <AuthLayout>
    <H1 class="card-title">Register</H1>
    <AuthForm btn-text="Register" />
  </AuthLayout>
</template>

<script setup lang="ts">
import AuthForm from "@/components/AuthForm.vue";
import H1 from "@/components/H1.vue";
import AuthLayout from "@/layouts/AuthLayout.vue";
</script>

<style scoped></style>
