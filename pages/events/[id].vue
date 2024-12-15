<script setup lang="ts">
const route = useRoute();
const nuxtApp = useNuxtApp();

console.log(route.params.id);
console.log(nuxtApp);
</script>

<template>
  <h1>event id: {{ $route.params.id }}</h1>
</template>
