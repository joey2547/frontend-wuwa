<script setup>
import { RouterLink, RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue'
import SignIn from './components/SignIn.vue'
import SignUp from './components/SignUp.vue'
</script>

<template>
  <v-app>
    <NavBar></NavBar>
    <RouterView></RouterView> <!-- To handle route views if you have a router setup -->
    
  </v-app>
</template>

<style scoped>
/* Add any scoped styles here if needed */
</style>
