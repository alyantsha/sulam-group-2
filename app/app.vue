<template>
  <NuxtPage />
</template>

<script setup lang="ts">
// Use useHead() to inject head elements like fonts
useHead({
  link: [
    {
      rel: 'stylesheet',
      href: 'https://fonts.googleapis.com/css2?family=Merriweather:wght@300;400;700;900&display=swap',
    },
  ],
})
</script>

<style>
/* Apply Merriweather globally */
body {
  font-family: 'Merriweather', serif;
}
</style>
