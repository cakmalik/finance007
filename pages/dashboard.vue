<template>
  <NuxtLayout name="treasurer">
    Ini adalah halaman dashboard admin
  </NuxtLayout>
</template>

<script setup lang="ts">
definePageMeta({
  middleware: ['auth', 'treasurer'],
})
</script>
