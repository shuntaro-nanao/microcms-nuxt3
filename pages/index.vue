<script setup lang="ts">
const title = "Hello Nuxt3!!";

useMeta({
  meta: [{ name: "description", content: `This is ${title} page` }],
});
</script>

<template>
  <h1>{{ title }}</h1>
</template>
