<script setup lang="ts">
import logo from '../components/Logo.vue'
</script>

<template>
    <div class="contact">
      <logo/>
      <h1>This is a Contact page</h1>
    </div>
  </template>
  
  <style>
  @media (min-width: 1024px) {
    .contact {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }
  }
  </style>
  