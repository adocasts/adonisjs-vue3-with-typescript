<template>
  <div>
    <h3>This is a test if this is working, you'll see the date below:</h3>
    <div>{{ dte }}</div>
  </div>
</template>

<script lang="ts" setup>
  const dte = new Date()
</script>