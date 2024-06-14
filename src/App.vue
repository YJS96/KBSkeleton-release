<template>
  <div>
    <NavBar />
    <RouterView />
    <Analytics />
  </div>
</template>

<script setup>
import NavBar from './components/NavBar.vue';
import { Analytics } from '@vercel/analytics';
</script>

<style scoped></style>

<style>
@import './assets/main.css';
</style>
