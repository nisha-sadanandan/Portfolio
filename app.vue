<script setup lang="ts">
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
</script>

<template>
  <div>
    <AppHeader/>
      <NuxtPage />
      <Skill/>
      <Project/>
      <AppFooter/>
  </div>
</template>
