<template>
  <MainLayout>
    <div>Index</div>
    <div>
      The message: {{ message }}
    </div>
  </MainLayout>
</template>

<script setup>
  import MainLayout from '../../Layouts/MainLayout.vue'

  defineProps({
    message: {
      type: String
    }
  })
</script>