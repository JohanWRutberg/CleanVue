<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>
<template>
  <!-- Navbar -->
  <ul>
    <li>
      <RouterLink to="/">Hem</RouterLink>
    </li>
    <li>
      <RouterLink to="/about">About</RouterLink>
    </li>
  </ul>
  <RouterView />
</template>
