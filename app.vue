<template>
  <NuxtLayout>
    <custom-header/>
    <div>
      <navigation-board/>
      <NuxtPage />
    </div>
  </NuxtLayout>
  <custom-footer/>
</template>
<script setup lang="ts">
import CustomHeader from '~/components/custom-header.vue';
import CustomFooter from '~/components/custom-footer.vue';
</script>
