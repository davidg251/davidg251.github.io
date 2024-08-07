<script setup lang="ts">
const route = useRoute()

const links = [ {
  label: 'Home',
  icon: 'i-heroicons-home',
  to: '/'
}, {
  label: 'About',
  icon: 'i-heroicons-chart-bar',
  to: `/about`
},
{
  label: 'Blog',
  icon: 'i-heroicons-chart-bar',
  to: `/blog/example`
}]
</script>

<template>
  <UHorizontalNavigation :links="links" class="border-b border-gray-200 dark:border-gray-800" />
</template>

