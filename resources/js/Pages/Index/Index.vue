<template>
  <div>Index</div>
  <div>
    The message: {{ message }}
  </div>
</template>

<script setup>
  defineProps({
    message: {
      type: String
    }
  })
</script>