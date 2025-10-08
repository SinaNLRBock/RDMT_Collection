<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <p>
      Click on an image to access different views on the RDMT Collection
    </p>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
