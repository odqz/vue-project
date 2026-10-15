<script setup>
  defineProps({
    imageUrl: String,
  })
</script>

<template>
  <img :src="imageUrl" alt="Character photo" class="w-96 h-136">
</template>
