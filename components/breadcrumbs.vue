<template>
  <div class="py-[12px] border-b border-solid border-[#ECEDEE] text-[#60656D] lato text-[12px] lato-m">
    <h1 class="flex items-center leading-[12px]">
      <nuxt-link to="/" class="text-[#60656D] hover:!text-[#419B44] hover:underline">
        Домашня сторінка
      </nuxt-link>

      <span class="mx-[8px] block">
        /
      </span>

      <span class="text-[#383E48] lato-b">
        {{ props.page }}
      </span>
    </h1>
  </div>
</template>

<script setup>
  const props = defineProps({
    page: {
        type: String
    }
  });
</script>
