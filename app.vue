<template>
  <NuxtLayout>
    <custom-header class="fixed flex justify-center top-0 left-0 w-full z-[3] transition-100" :class="{scrolled: isScrolled}"/>

    <div class="relative pt-[82px]">
      <NuxtPage />
    </div>
  </NuxtLayout>
  <custom-footer/>
</template>
<script setup lang="ts">
import CustomHeader from '~/components/custom-header.vue';
import CustomFooter from '~/components/custom-footer.vue';
const isShownMenu = useState('showMenu')
const isScrolled = ref(false);

function onScroll() {
  isScrolled.value = window.scrollY > 0
}

onMounted(async () => {
  window.addEventListener('scroll', onScroll)
});

onDeactivated(() => {
  window.removeEventListener('scroll', onScroll)
});
</script>

<style scoped>
.scrolled {
  box-shadow: 0px 158px 44px 0px rgba(0, 0, 0, 0.00), 0px 101px 40px 0px rgba(0, 0, 0, 0.00), 0px 57px 34px 0px rgba(0, 0, 0, 0.01), 0px 25px 25px 0px rgba(0, 0, 0, 0.02), 0px 6px 14px 0px rgba(0, 0, 0, 0.02);
  border-bottom: 1px solid #ECEDEE;
}
</style>
