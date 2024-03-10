<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'

</script>

<template>
  <Navbar />
  <RouterView />
  <Footer />
</template>

<style>
  body {
    margin: 0;
    background: #1a1a1a;
    color: white;
    font-family: "Roboto", sans-serif;
  }
</style>
