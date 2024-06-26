<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
    <h1 class="text-primary">{{ msg }}</h1>
</template>