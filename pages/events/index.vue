<script setup lang="ts">
definePageMeta({
  layout: "custom",
});

const { sayHello } = useUtils();
sayHello();
</script>

<template>
  <h1>events page</h1>
</template>
