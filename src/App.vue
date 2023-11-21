<script setup>
</script>

<template>
  <div class="app-container" :class="authStore.user && 'bg-light'">
    <Nav />
    <Alert />
    <div class="container pt-4 pb-4">
      <router-view />
    </div>
  </div>
</template>

<style scoped>
@import '@/assets/base.css';
</style>
