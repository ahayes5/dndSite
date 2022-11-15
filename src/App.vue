<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>

    <div class="wrapper">
      <nav>
        
      </nav>
    </div>
  </header>

  <v-app>
    <v-app-bar absolute dense elevation="5" color="white" hide-on-scroll>
        <v-btn><RouterLink to="/" class="navitem">Home</RouterLink></v-btn>
        <v-btn><RouterLink to="/about" class="navitem">About</RouterLink></v-btn>
        <v-btn><a href="/foundry" class="navitem">Foundry</a></v-btn>
    </v-app-bar>
    <v-main>
      <RouterView />
    </v-main>
  </v-app>
  
</template>

<style scoped>

</style>
