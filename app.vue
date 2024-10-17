<script setup lang="ts">

// When adding VueUse as a nuxt module, vueusecore is not added

const {height} = useWindowSize()
</script>
<template>
  <div>
    {{ height }}
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>
