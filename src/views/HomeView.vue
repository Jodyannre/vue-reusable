<template>
    <MainLayout>
      <template v-slot:main>
        <h5>Main content</h5>
      </template>

      <template #aux>
        <p> Aux content</p>
      </template>
    </MainLayout>
</template>
  
<script lang="ts" setup>
  import MainLayout from '@/layouts/MainLayout.vue';
  
</script>
  
<style scoped>
</style>
  