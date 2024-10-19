<template>
  <NuxtLayout>
    <custom-header/>
    <div>
      <NuxtPage />
    </div>
    <custom-footer/>
  </NuxtLayout>
</template>
<script setup lang="ts">
import CustomHeader from '~/components/custom-header.vue';
import CustomFooter from '~/components/custom-footer.vue';
</script>
