<script setup>
const route = useRoute()
useHead({
  title: route.meta.title,
  meta: [{ name: 'og:title', content: `App Name - ${route.meta.title}` }],
})
</script>
<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
