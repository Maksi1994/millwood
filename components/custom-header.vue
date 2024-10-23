<template>
  <div class="flex lg:py-[20px] py-[14px] items-center">
    <!--
    <img class="w-[16px] h-[16px] cursor-pointer mr-[16px]" draggable="false" src="/assets/img/icons/menu-line.svg" alt="">
    <img class="w-[16px] h-[16px] cursor-pointer mr-[16px] hidden" draggable="false" src="/assets/img/icons/x.svg" alt="">
    -->

    <img src="/assets/img/icons/logo.svg" draggable="false" class="w-[200px] mr-[50px] lg:block hidden">
    <img src="/assets/img/logo-mobile.svg" draggable="false" class="w-[172px] mr-[28px] lg:hidden">


    <div class="gap-[20px] lg:flex hidden">
      <a class="text-[#464B57] text-[16px] lato-s lato">
        Про Мілвуд
      </a>
      <a class="px-[14px] lato lato-s">
        Продукти і рішення
      </a>
      <a class="text-[#464B57] text-[16px] lato-s lato">
        Стійкість
      </a>
      <a class="text-[#464B57] text-[16px] lato-s lato">
        Новини
      </a>
    </div>

    <div class="lg:ml-20 ml-auto items-center flex">
      <div class="lg:w-[125px] w-[96px] lg:leading-[42px] leading-[36px] lg:text-[16px] text-[14px] text-center cursor-pointer bg-[#419B44] text-white">
        Звʼязатися
      </div>

      <div class="ml-[12px] py-[6px] pl-[7px] pr-[10px] border border-[#ECEDEE] border-solid cursor-pointer h-[42px]">

      </div>
    </div>
  </div>
</template>


<script>
const isOpenLand = ref(false)

function toggleLang() {

}
</script>
