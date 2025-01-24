<script setup>
import { ref } from 'vue'

const name = ref('Konkamon')
</script>

<template>
  <input v-model="name" placeholder="Enter Your Name..." type="text" />
  <h1>Hello, {{ name }}!</h1>
</template>
