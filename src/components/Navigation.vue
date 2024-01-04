<template>
  <nav class="flex justify-between items-center">
    <img class="img-navigation" src="../assets/icons/AionLogo.png" alt="Aion logo" />
    <section class="text-white flex gap-10">
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </section>
  </nav>
</template>

<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<style scoped lang="scss">
nav {
  .img-navigation {
    width: 150px;
  }

  padding: 1rem;
  background-color: $color-tertiary;
}
</style>
