<script setup lang="ts">
import logo from '../components/Logo.vue'
</script>


<template>
  <div class="about">
    <logo/>
    <h1>This is an About page</h1>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
