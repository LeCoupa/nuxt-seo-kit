<script lang="ts" setup>
definePageMeta({
  breadcrumbTitle: 'Home',
  image: '/images/og-image.png'
})

useHead({
  title: null,
})
</script>
<template>
  <h1>Hello world</h1>
  <p>Welcome to my website</p>
  <NuxtLink to="/about">about</NuxtLink>
  <NuxtLink to="/no-set-title">/no-set-title</NuxtLink>
</template>
