<template>
  <div>
    <p>Product id is {{  id  }}</p>
  </div>
</template>

<script setup>
  const { id } = useRoute().params
  // acess http://localhost:3000/products/123, you'll see the value
</script>

<style scoped>

</style>