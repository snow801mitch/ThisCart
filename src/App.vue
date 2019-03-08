<template>
  <v-app>
    <app-navigation></app-navigation>
    <v-content transition="slide-x-transition">
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
import AppNavigation from '@/components/AppNavigation';
// import HomeHero from '@/components/HomeHero';
// import Home from '@/components/Home'

export default {
  name: 'App',
  components: {
    AppNavigation,
    // Home,
    // HomeHero
  }
};
</script>

<style>
</style>
