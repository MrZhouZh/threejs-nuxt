<script setup lang="ts">
import '@unocss/reset/tailwind.css'
useSeoMeta({
  titleTemplate: 'Nuxt HN | %s',
  description: 'Three.js examples built with Nuxt.',
  ogImage: 'https://hn.nuxt.space/cover.jpg',
  ogImageAlt: 'Three.js examples',
  twitterImage: 'https://hn.nuxt.space/cover.jpg',
  twitterSite: '@nuxt_js',
  twitterCreator: '@nuxt_js',
  twitterCard: 'summary_large_image',
})
useHead({
  link: [
    { rel: 'icon', type: 'image/svg+xml', href: '/logo.svg' }
  ]
})
</script>

<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
