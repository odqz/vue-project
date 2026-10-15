<script setup>
  defineProps({
    name: String,
  })
</script>

<template>
  <h1 class="font-bold text-2xl text-(--green)">{{ name }}</h1>
</template>