<script setup lang="ts">
import type { NavigationMenuItem } from '@nuxt/ui'

const items = ref<NavigationMenuItem[][]>([
  [
    {
      label: 'Home',
      icon: 'i-lucide-book-open',
      to: '/'
    },
    {
      label: 'About',
      icon: 'i-lucide-database',
      to: '/about'
    },
  ],
  [
    {
      label: 'GitHub',
      icon: 'i-simple-icons-github',
      badge: '3.8k',
      to: 'https://github.com/nuxt/ui',
      target: '_blank'
    }
  ]
])
</script>

<template>
  <UHeader title="Nuxt UI">
    <UNavigationMenu color="neutral" :items="items" class="w-full" />
  </UHeader>
</template>