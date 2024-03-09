<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue'
import TheWelcome from './components/TheWelcome.vue';

</script>

<template>
  <Navbar />
  <!-- <RouterView /> -->
</template>

<style>
  body {
    background: #1a1a1a;
    color: white;
    font-family: "Roboto", sans-serif;
  }
</style>
