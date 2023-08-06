<script setup>
    import { ref, reactive } from 'vue'
    const simpletext = ref("Hello")
</script>

<template>
  <section class="mx-auto container">
    <p class="mb-3">{{ simpletext }}</p>
     <input type="text" class="p-5" v-model="simpletext"/>
  </section>
</template>

<style scoped>

</style>
