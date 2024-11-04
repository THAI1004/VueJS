<template>
  <div>Count:{{ count }}</div>
  <button @click="tang">Tăng</button>
</template>

<script setup>
import { ref } from 'vue'
const count = ref(0)
const tang = () => {
  count.value++
}
</script>

<style lang="scss" scoped></style>
