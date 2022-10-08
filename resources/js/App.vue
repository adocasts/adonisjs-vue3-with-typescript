<template>
  <div>
    <h1>Test, {{ isWorking }}</h1>
    <Test />
  </div>
</template>

<script lang="ts" setup>
  import Test from '@/components/Test.vue'
  const isWorking = true
</script>