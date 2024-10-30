<template>
    <MainLayout>
      <template #main>
        <h1>Contact</h1>
        <p> X position = {{ x }} | y position = {{ y }}</p>
      </template>
    </MainLayout>
</template>
  
<script lang="ts" setup>
    import MainLayout from '@/layouts/MainLayout.vue';
    import { useMouse } from '@/composables/useMouse';

    const { x, y } = useMouse();  

</script>
  
<style scoped>
</style>
  