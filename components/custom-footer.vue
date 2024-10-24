<template>
  <div class="w-full bg-[#FAFAFA] lato lg:px-0 px-[16px]">
    <div class="py-[24px] lg:w-[996px] mx-auto flex lg:flex-row flex-col lg:gap-[42px] gap-[32px] justify-between">
      <div class="lg:w-auto lg:w-[270px]">
        <div class="flex w-full">
          <nuxt-link to="/">
            <img src="/assets/img/logo-mobile.svg" draggable="false" class="w-[153px] mb-[5px]"/>
          </nuxt-link>

          <div class="flex lg:hidden ml-auto gap-[10px]">
            <a href="/" class="group">
              <img class="w-[24px] h-[24px] group-hover:hidden" src="assets/img/icons/in.svg">
              <img class="w-[24px] h-[24px] hidden group-hover:block" src="assets/img/icons/in-active.svg">
            </a>
            <a href="" class="group">
              <img class="w-[24px] h-[24px] group-hover:hidden" src="assets/img/icons/youtube.svg">
              <img class="w-[24px] h-[24px] hidden group-hover:block" src="assets/img/icons/youtube-active.svg">
            </a>
          </div>
        </div>

        <p class="text-[#61656F] text-[14px] mb-[13px] lato-s">
          Інноваційна компанія на ринку <br>
          екологічних будівель України
        </p>
        <div class="lg:flex hidden gap-[10px]">
          <a href="/" class="group">
            <img class="w-[24px] h-[24px] group-hover:hidden" src="assets/img/icons/in.svg">
            <img class="w-[24px] h-[24px] hidden group-hover:block" src="assets/img/icons/in-active.svg">
          </a>
          <a href="" class="group">
            <img class="w-[24px] h-[24px] group-hover:hidden" src="assets/img/icons/youtube.svg">
            <img class="w-[24px] h-[24px] hidden group-hover:block" src="assets/img/icons/youtube-active.svg">
          </a>
        </div>
      </div>


      <div class="lg:w-auto w-[270px]">
        <h1 class="text-[#464B57] text-[16px] lato-e mb-[12px] leading-[19px]">Будівельні концепції</h1>

        <ul>
          <li class="mb-[4px]">
            <nuxt-link to="/solution-1" class="text-[#464B57] leading-[22px] text-[14px] lato-m hover:text-[#419B44] hover:underline underline-offset-[3px]">
              Індустріальні будівлі
            </nuxt-link>
          </li>
          <li class="mb-[4px]">
            <nuxt-link to="/solution-2" class="text-[#464B57] leading-[22px] text-[14px] lato-m hover:text-[#419B44] hover:underline underline-offset-[3px]">
              Житлові будівлі
            </nuxt-link>
          </li>
          <li>
            <nuxt-link to="/solution-3" class="text-[#464B57] leading-[22px] text-[14px] lato-m hover:text-[#419B44] hover:underline underline-offset-[3px]">
              Соціальні будівлі
            </nuxt-link>
          </li>
        </ul>
      </div>

      <div class="lg:w-auto w-[270px]">
        <h1 class="text-[#464B57] text-[16px] lato-e mb-[12px] leading-[19px]">Будівельні матеріали</h1>

        <ul>
          <li class="mb-[4px]">
            <nuxt-link to="/material-1" class="text-[#464B57] leading-[22px] text-[14px] lato-m hover:text-[#419B44] hover:underline underline-offset-[3px]">
              Конструкційна деревина C24
            </nuxt-link>
          </li>
          <li class="mb-[4px]">
            <nuxt-link to="/material-2" class="text-[#464B57] leading-[22px] text-[14px] lato-m hover:text-[#419B44] hover:underline underline-offset-[3px]">
              Клеєна деревина kvh с24
            </nuxt-link>
          </li>
          <li>
            <nuxt-link to="/material-3" class="text-[#464B57] leading-[22px] text-[14px] lato-m hover:text-[#419B44] hover:underline underline-offset-[3px]">
              Клеєна деревина Glulam GL24h
            </nuxt-link>
          </li>
        </ul>
      </div>

      <div class="lg:w-auto w-[270px]">
        <h1 class="text-[#464B57] text-[16px] lato-e mb-[12px] leading-[19px]">Контакти</h1>

        <ul>
          <li class="mb-[9px]">
            <a href="/" class="text-[#419B44] text-[14px] lato-m hover:text-[#419B44] hover:underline underline-offset-[3px]">
              +380 50 373 0203
            </a>
          </li>
          <li>
            <a href="/" class="text-[#464B57] leading-[22px] text-[14px] lato-m hover:text-[#419B44] hover:underline underline-offset-[3px]">
              Мілвуд ТОВ
            </a>
          </li>
          <li>
            <a href="/" class="text-[#464B57] leading-[22px] text-[14px] lato-m hover:text-[#419B44] hover:underline underline-offset-[3px]">
              Заводська 4, смт. Вигода, Україна, 77552
            </a>
          </li>
        </ul>
      </div>
    </div>
    <div class="text-center bg-white h-[44px] flex items-center justify-center text-[#61656F] lato-s">
      © 2024 - Millwood LLC
    </div>
  </div>
</template>
