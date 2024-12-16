<script setup lang="ts">
const { sayHello } = useUtils();
sayHello();
</script>

<template>
  <div>
    <Alert />
    <p>main page</p>
    <img src="/logo.png" alt="logo" />
    <img src="~/assets/emoji1.png" alt="emoji1" class="size-12" />
  </div>
</template>
