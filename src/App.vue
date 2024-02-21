<script setup>
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <v-app>
    <Navbar></Navbar>
    <main>
      <router-view></router-view>
    </main>
    <Footer/>>
  </v-app>
</template>


