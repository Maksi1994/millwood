<template>
  <div ref="wrap" class="lg:py-[22px] py-[42px] lg:px-[32px] px-[16px] bg-[#F4F9F4] flex justify-center flex-wrap gap-[62px] lg:mx-0 -mx-[16px]">
    <div class="w-full lg:w-[205px]">
      <h1 class="text-[#464B57] lg:text-[16px] text-[18px] lato-e mb-[12px] leading-[19px] font-bold">Будівельні матеріали</h1>

      <ul>
        <li class="mb-[2px] lg:py-0 py-[10px] lg:border-0 border-b border-[#ECEDEE] border-solid">
          <nuxt-link href="/material-1" exactActiveClass="!text-[#419B44] underline" class="text-[#464B57] lg:text-[14px] text-[16px] lato-m hover:text-[#419B44] hover:underline underline-offset-[3px]">
            Конструкційна деревина C24
          </nuxt-link>
        </li>
        <li class="mb-[2px] lg:py-0 py-[10px] lg:border-0 border-b border-[#ECEDEE] border-solid">
          <nuxt-link href="/material-2" exactActiveClass="!text-[#419B44] underline" class="text-[#464B57] lg:text-[14px] text-[16px] lato-m hover:text-[#419B44] hover:underline underline-offset-[3px]">
            Клеєна деревина KVH C24
          </nuxt-link>
        </li>
        <li class="lg:py-0 py-[10px] lg:border-0 border-b border-[#ECEDEE] border-solid">
          <nuxt-link href="/material-3" exactActiveClass="!text-[#419B44] underline" class="text-[#464B57] lg:text-[14px] text-[16px] lato-m hover:text-[#419B44] hover:underline underline-offset-[3px]">
            Клеєна деревина Gulam GL24h
          </nuxt-link>
        </li>
      </ul>
    </div>

    <div class="w-full lg:w-auto">
        <h1 class="text-[#464B57] lg:text-[16px] text-[18px] lato-e mb-[12px] leading-[19px] font-bold">Будівельні концепції</h1>

        <ul>
          <li class="mb-[2px] lg:py-0 py-[10px] lg:border-0 border-b border-[#ECEDEE] border-solid">
            <nuxt-link to="/solution-1" exactActiveClass="!text-[#419B44] underline" class="text-[#464B57] lg:text-[14px] text-[16px] lato-m hover:text-[#419B44] underline-offset-[3px] hover:underline underline-offset-[3px]">
              Індустріальні будівлі
            </nuxt-link>
          </li>
          <li class="mb-[2px] lg:py-0 py-[10px] lg:border-0 border-b border-[#ECEDEE] border-solid">
            <nuxt-link to="/solution-2" exactActiveClass="!text-[#419B44] underline" class="text-[#464B57] lg:text-[14px] text-[16px] lato-m hover:text-[#419B44] hover:underline underline-offset-[3px]">
              Житлові будівлі
            </nuxt-link>
          </li>
          <li class="lg:py-0 py-[10px] lg:border-0 border-b border-[#ECEDEE] border-solid">
            <nuxt-link to="/solution-3" exactActiveClass="!text-[#419B44] underline" class="text-[#464B57] lg:text-[14px] text-[16px] lato-m hover:text-[#419B44] hover:underline underline-offset-[3px]">
              Соціальні будівлі
            </nuxt-link>
          </li>
        </ul>
      </div>
  </div>
</template>


<script setup>
const wrap = ref(null)
const route = useRoute()

function toggleMenu(e) {
  const showMenu = useState('showMenu')

  if (showMenu.value && wrap.value && !wrap.value.contains(e.target)) {
    showMenu.value = false
  }
}

watch(
    () => route.path,
    () => {
      const showMenu = useState('showMenu')
      showMenu.value = false
    }
);

onMounted(async () => {
  await nextTick();

  document.body.addEventListener('click', toggleMenu)
});

onDeactivated(() => {
  document.body.removeEventListener('click', toggleMenu)
});

</script>
