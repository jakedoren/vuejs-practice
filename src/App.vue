<script setup>
import { ref } from 'vue'
  const res = ref(['Betty', 'Jake', 'Meagan', "Bella"])
  console.log(res)
</script>

<template>
  <input type="text" :value="res[2]">
</template>

<style>
  .red {
    color: purple;
  }
</style>
