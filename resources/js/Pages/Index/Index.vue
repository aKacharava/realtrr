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

<script>
import MainLayout from '../../Layouts/MainLayout.vue';
export default {
  layout: MainLayout
}
</script>