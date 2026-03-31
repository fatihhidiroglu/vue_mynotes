<template>
  <AuthLayout>
    <H1 class="card-title">Login</H1>
    <form>
      <div class="form-control">
        <label class="label">
          <span class="label-text">Email</span>
        </label>
        <input type="text" placeholder="email@example.com" class="input input-bordered" />
      </div>
      <div class="form-control mt-4">
        <label class="label">
          <span class="label-text">Password</span>
        </label>
        <input type="password" placeholder="*********" class="input input-bordered" />
      </div>
      <div class="form-control mt-6">
        <button class="btn btn-primary">Login</button>
      </div>
    </form>
  </AuthLayout>
</template>

<script setup lang="ts">
import H1 from "@/components/H1.vue";
import AuthLayout from "@/layouts/AuthLayout.vue";
</script>

<style scoped></style>
