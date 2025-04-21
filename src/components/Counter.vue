<!-- Counter.vue -->
<template>
    <button @click="count++">你点了我 {{ count }} 次</button>
</template>
  
<script setup>
import { ref } from 'vue'
const count = ref(0)
</script>