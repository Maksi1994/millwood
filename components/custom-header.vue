<template>
  <div class="flex lg:py-[20px] px-[16px] bg-white py-[12px] items-center lg:border-b-0 border-b border-solid border-[#ECEDEE]">
    <div class="lg:hidden mr-[14px]" @click.stop="toggleMenu">
      <img class="w-[24px] h-[24px] cursor-pointer" v-if="!isShownMenu" draggable="false" src="/assets/img/icons/menu-line.svg" alt="">
      <img class="w-[24px] h-[24px] cursor-pointer" v-else draggable="false" src="/assets/img/icons/x.svg" alt="">
    </div>

    <nuxt-link to="/">
      <img src="/assets/img/icons/logo.svg" draggable="false" class="w-[200px] mr-[40px] lg:block hidden">
      <img src="/assets/img/logo-mobile.svg" draggable="false" class="w-[133px] mr-[28px] lg:hidden">
    </nuxt-link>


    <div class="lg:flex hidden">
      <nuxt-link to="/about" exactActiveClass="!text-[#419B44] bg-[#F4F9F4]" class="text-[#464B57] mr-[10px] px-[10px] text-[16px] lato-s lato leading-[42px] duration-100 hover:!text-[#419B44] hover:bg-[#F4F9F4]">
        Про Мілвуд
      </nuxt-link>
      <div @click.stop="toggleMenu" :class="{'!text-[#419B44] bg-[#F4F9F4]': isShownMenu}" class="px-[14px] mr-[12px] duration-100 text-[#464B57]	select-none leading-[42px] pr-[10px] lato lato-s flex items-center cursor-pointer hover:!text-[#419B44] hover:bg-[#F4F9F4]">
        Продукти і рішення

        <img class="w-[24px] h-[24px] ml-[10px]" :hidden="isShownMenu" draggable="false" src="/assets/img/icons/caret-down.svg"/>
        <img class="w-[24px] h-[24px] ml-[10px]" :hidden="!isShownMenu" draggable="false" src="/assets/img/icons/green-caret-up.svg"/>
      </div>
      <nuxt-link to="/strong" exactActiveClass="!text-[#419B44] bg-[#F4F9F4]" class="text-[#464B57] px-[10px] text-[16px] lato-s lato leading-[42px] duration-100	hover:!text-[#419B44] hover:bg-[#F4F9F4]">
        Стійкість
      </nuxt-link>
      <nuxt-link to="/news" exactActiveClass="!text-[#419B44] bg-[#F4F9F4]" class="text-[#464B57] ml-[5px] px-[10px] text-[16px] lato-s lato leading-[42px] duration-100	hover:!text-[#419B44] hover:bg-[#F4F9F4]">
        Новини
      </nuxt-link>
    </div>

    <div class="lg:ml-[30px] ml-auto items-center flex">
      <nuxt-link to="/contacts" class="lg:w-[125px] w-[96px] lg:leading-[42px] leading-[32px] lg:text-[16px] text-[14px] text-center cursor-pointer bg-[#419B44] text-white">
        Звʼязатися
      </nuxt-link>

      <div @click.stop="toggleLang" ref="langWrap" :class="{'!border-b-[transparent] z-[5]': isOpenLand}" class="ml-[12px] h-[42px] items-center w-[88px] relative select-none lg:flex hidden py-[6px] pl-[7px] pr-[10px] border border-[#ECEDEE] border-solid cursor-pointer h-[42px]">
        <img class="w-[38px]" src="/assets/img/icons/ua-flag.svg" alt="">

        <img class="w-[24px] h-[24px] ml-[8px]" :class="{'is-open-arrow': isOpenLand}" draggable="false" src="/assets/img/icons/caret-down.svg"/>

        <div v-if="isOpenLand" class="absolute top-[100%] -left-[1px] w-[88px] m-auto py-[6px] pl-[7px] pb-[12px] bg-[#F4F9F4] !border-t-0 border border-[#ECEDEE] border-solid cursor-pointer">
          <img class="w-[38px] cursor-pointer" src="/assets/img/icons/uk-flag.svg" alt="">
        </div>
      </div>
    </div>

    <div class="absolute top-[calc(100%+1px)] left-0 bottom-0 m-auto w-full z-[2]" v-if="isShownMenu">
      <navigation-board />
    </div>
  </div>
</template>


<script setup>
const langWrap = ref();
const isOpenLand = ref(false)
const isShownMenu = computed(() => useState('showMenu').value)

function toggleLang() {
  isOpenLand.value = !isOpenLand.value
}

function toggleMenu() {
  const isShownState = useState('showMenu');
  isShownState.value = !isShownMenu.value
}


function toggleLangMenu(e) {
  if (isOpenLand.value && langWrap.value && !langWrap.value.contains(e.target)) {
    isOpenLand.value = false
  }
}

onMounted(async () => {
  await nextTick();

  document.body.addEventListener('click', toggleLangMenu)
});

onDeactivated(() => {
  document.body.removeEventListener('click', toggleLangMenu)
});


</script>


<style scoped>
.is-open-arrow {
  transform: rotate(180deg);
}
</style>
