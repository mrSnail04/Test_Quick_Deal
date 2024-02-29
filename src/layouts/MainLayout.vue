<template>
  <div class="h-screen flex flex-col">
    <header>
      <NavbarMain />
    </header>
    <main class="bg-gray-200 flex-grow">
      <slot></slot>
    </main>
  </div>
</template>

<script setup>
import NavbarMain from '../components/NavbarMain.vue';
</script>
