<script setup lang="ts">
defineProps<{
  btnText: "Login" | "Register";
}>();
</script>

<template>
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
      <button class="btn btn-primary">{{ btnText }}</button>
    </div>
    <p class="mt-2">
      {{ btnText === "Login" ? "Don't have an account?" : "Already have an account?" }}
      <RouterLink :to="btnText === 'Login' ? '/register' : '/login'" class="link link-primary">
        {{ btnText === "Login" ? "Register" : "Login" }}
      </RouterLink>
    </p>
  </form>
</template>

<style lang="scss" scoped></style>
