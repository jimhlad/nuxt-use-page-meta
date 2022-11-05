<script setup>
const route = useRoute()
useHead({
  title: route.meta.title,
})
</script>
<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
