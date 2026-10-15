<script setup>
  defineProps({
    label: String,
    value: String,
  })
</script>

<template>
  <div class="flex gap-2">
    <p>{{ label }}:</p>
    <p class="text-(--blue) font-bold">{{ value }}</p>
  </div>
</template>
