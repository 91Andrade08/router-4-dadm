<script setup>
import { RouterView } from 'vue-router'

</script>

<template>

  <div id="nav">
  <router-link style="padding: 5px;" to="/">Inicio</router-link>   | 
  <router-link style="padding: 5px;" to="/Brazil">Brasil</router-link>
  <router-link style="padding: 5px;" to="/about">Acerca de </router-link>
</div>
  <div class="container">
   <RouterView />
  </div>


 
</template>

<style scoped>

</style>
