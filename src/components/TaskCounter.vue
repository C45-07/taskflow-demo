<script setup>
defineProps({
  count: { type: Number, required: true },
  label: { type: String, default: 'Знайдено' },
})
</script>
<template>
  <div class="tf3-counter">{{ label }}: {{ count }}</div>
</template>
