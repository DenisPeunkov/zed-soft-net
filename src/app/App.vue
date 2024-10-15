<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './widgets/navbar/ui/navbar.vue'
import Header from './widgets/header/ui/header.vue'
</script>

<template>
  <div class="page">
    <div class="content">
      <Header />
      <Navbar />
      <RouterView />
    </div>
  </div>
</template>

<style scoped></style>
