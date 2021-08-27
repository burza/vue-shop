// Define a new component called button-counter
<script setup>
import { ref } from 'vue'
const count = ref(0)
</script>

<template>
  <button v-on:click="count++">You clicked me {{ count }} times.</button>  
</template>

<style scoped>
/* component specific styles goes here */
</style>
