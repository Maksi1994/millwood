<template>
    <div class="mt-[15px] w-full">
      <div class="lg:h-[400px] h-[320px] w-full bg-[url(/assets/img/bg.png)] bg-no-repeat bg-center relative lg:mb-[110px] mb-[14px] bg-cover">
          <div class="absolute lg:table hidden left-0 top-0 bottom-0 m-auto table p-[24px] bg-white w-[540px]">
            <h1 class="text-[#419B44] uppercase text-[30px] lato-e mb-[14px]">
              Зелене будівництво — вибір <br> для відновлення України
            </h1>

            <p class="text-[#464B57] text-[16px] lato-s leading-[24px]">
              Наша місія полягає в наданні ефективних, надійних та <br> екологічно сталих рішень для будівництва.
            </p>
          </div>
        </div>

      <div class="lg:hidden block w-full mb-[62px]">
        <h1 class="text-[#419B44] uppercase text-[22px] lato-e mb-[14px] text-[22px]">
          Зелене будівництво — вибір для відновлення України
        </h1>

        <p class="text-[#464B57] text-[16px] lato-s leading-[24px]">
          Наша місія полягає в наданні ефективних, надійних та екологічно сталих рішень для будівництва.
        </p>
      </div>

        <div class="mb-[50px]">
          <h1 class="lg:text-[30px] text-[22px] text-[#464B57] lato-e mb-[24px]">
            Будівельні концепції
          </h1>

          <div class="flex gap-[24px] md:flex-nowrap flex-wrap">
            <nuxt-link to="/solution-1" class="border border-solid border-[#ECEDEE] md:w-[316px] w-full h-[305px] flex flex-col justify-between shadow">
              <div class="px-[9xp] py-[19px] pt0">
                <img src="/assets/img/industrial.png" alt="" class="w-full mx-auto max-w-[300px]">
              </div>

              <div to="/solution-1" class="h-[42px] my-[20px] mb-[34px] mx-[14px] shrink-0 bg-[#FAFAFA] hover:bg-[#F4F9F4] group border-[#ECEDEE] lg:mt-[24px] border border-solid text-[#464B57] hover:text-[#419B44] flex items-center justify-center cursor-pointer">
                <span class="flex lato-b gap-[10px] text-[20px] items-center">
                   Індустріальні будівлі

                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px] group-hover:hidden block" alt="">
                  <img src="/assets/img/icons/caret-right-active.svg" draggable="false" class="w-[20px] h-[20px] group-hover:block hidden" alt="">
                </span>
              </div>
            </nuxt-link>

            <nuxt-link to="/solution-2" class="border border-solid border-[#ECEDEE] md:w-[316px] w-full h-[305px] flex flex-col justify-between shadow">
              <div class="px-[9xp]">
                <img src="/assets/img/living.png" alt="" class="w-full mx-auto max-w-[300px] h-[180px]">
              </div>

              <div class="h-[42px] my-[20px] mb-[34px] mx-[14px] shrink-0 bg-[#FAFAFA] hover:bg-[#F4F9F4] group border-[#ECEDEE] lg:mt-[24px] border border-solid text-[#464B57] hover:text-[#419B44] flex items-center justify-center cursor-pointer">
                <span class="flex lato-b gap-[10px] text-[20px] items-center">
                   Житлові будівлі

                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px] group-hover:hidden block" alt="">
                  <img src="/assets/img/icons/caret-right-active.svg" draggable="false" class="w-[20px] h-[20px] group-hover:block hidden" alt="">
                </span>
              </div>
            </nuxt-link>

            <nuxt-link to="/solution-3" class="border border-solid border-[#ECEDEE] md:w-[316px] w-full h-[305px] flex flex-col justify-between shadow">
              <div class="px-[9xp] py-[19px]">
                <img src="/assets/img/social.png" alt="" class="w-full max-w-[168px] h-[168px] mx-auto">
              </div>

              <div to="/solution-3" class="h-[42px] my-[20px] mb-[34px] mx-[14px] shrink-0 bg-[#FAFAFA] hover:bg-[#F4F9F4] group border-[#ECEDEE] lg:mt-[24px] border border-solid text-[#464B57] hover:text-[#419B44] flex items-center justify-center cursor-pointer">
                <span class="flex lato-b gap-[10px] text-[20px] items-center">
                  Соціальні будівлі

                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px] group-hover:hidden block" alt="">
                  <img src="/assets/img/icons/caret-right-active.svg" draggable="false" class="w-[20px] h-[20px] group-hover:block hidden" alt="">
                </span>
              </div>
            </nuxt-link>
          </div>

        </div>

        <div class="mb-[110px]">
          <h1 class="lg:text-[30px] text-[22px] text-[#464B57] lato-e mb-[24px]">
            Будівельні матеріали
          </h1>

          <div class="flex gap-[24px] md:flex-nowrap flex-wrap">
            <div class="border h-[346px] border-solid border-[#ECEDEE] lg:w-[316px] w-full h-[346px] p-[14px] flex flex-col gap-[10px] shadow">
              <div>
                <img src="/assets/img/material-1.png" alt="" class="w-full lg:h-[166px] mx-auto max-w-[300px] object-[20px]">
              </div>

              <h1 class="text-[#464B57] text-[20px] lato-m leading-normal">
                Конструкційна
                <br>
                деревина C24
              </h1>

              <nuxt-link to="/material-1" class="h-[42px] shrink-0 w-full bg-[#FAFAFA] hover:bg-[#F4F9F4] group border-[#ECEDEE] lg:mt-[24px] border border-solid text-[#464B57] hover:text-[#419B44] flex items-center justify-center cursor-pointer">
                <span class="flex lato-b gap-[10px] text-[16px] items-center">
                  Детальніше

                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px] group-hover:hidden block" alt="">
                  <img src="/assets/img/icons/caret-right-active.svg" draggable="false" class="w-[20px] h-[20px] group-hover:block hidden" alt="">
                </span>
              </nuxt-link>
            </div>

            <div class="border h-[346px] border-solid border-[#ECEDEE] lg:w-[316px] w-full h-[346px] flex flex-col shadow p-[14px] gap-[10px]">
              <div>
                <img src="/assets/img/material-2.png" alt="" class="w-full lg:h-[166px] mx-auto max-w-[300px] object-[20px_-25px]">
              </div>

              <h1 class="text-[#464B57] text-[20px] lato-m leading-normal">
                <span class="break-keep">Клеєна деревина з шиповими</span>  <br> з’єднаннями (KVH C24)
              </h1>

              <nuxt-link to="/material-2" class="h-[42px] shrink-0 w-full bg-[#FAFAFA] hover:bg-[#F4F9F4] group border-[#ECEDEE] lg:mt-[24px] border border-solid text-[#464B57] hover:text-[#419B44] flex items-center justify-center cursor-pointer">
                <span class="flex lato-b gap-[10px] text-[16px] items-center">
                  Детальніше

                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px] group-hover:hidden block" alt="">
                  <img src="/assets/img/icons/caret-right-active.svg" draggable="false" class="w-[20px] h-[20px] group-hover:block hidden" alt="">
                </span>
              </nuxt-link>
            </div>

            <div class="border h-[346px] border-solid border-[#ECEDEE] lg:w-[316px] w-full h-[346px] flex flex-col shadow p-[14px] gap-[10px]">
              <div>
                <img src="/assets/img/material-3.png" alt="" class="w-full lg:h-[166px] mx-auto max-w-[300px] object-[40px_-10px]">
              </div>

              <h1 class="text-[#464B57] text-[20px] lato-m leading-normal">
                Клеєна багатошарова <br> деревина (GLT/Glulam)
              </h1>

              <nuxt-link to="/material-3" class="h-[42px] shrink-0 w-full bg-[#FAFAFA] hover:bg-[#F4F9F4] group border-[#ECEDEE] lg:mt-[24px] border border-solid text-[#464B57] hover:text-[#419B44] flex items-center justify-center cursor-pointer">
                <span class="flex lato-b gap-[10px] text-[16px] items-center">
                  Детальніше

                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px] group-hover:hidden block" alt="">
                  <img src="/assets/img/icons/caret-right-active.svg" draggable="false" class="w-[20px] h-[20px] group-hover:block hidden" alt="">
                </span>
              </nuxt-link>
            </div>
          </div>


        </div>

        <div class="lg:w-[100vw] lg:mb-[38px] mb-[48px] lg:-ml-[calc((100vw-996px)/2)] bg-[#F4F9F4] py-[42px] lg:mr-0 -mx-[16px] lg:px-0 px-[16px]">
          <h1 class="text-[#419B44] text-center lg:text-[32px] text-[20px] lato-e leading-[35px] mb-[25px]">
            Наша продукція підтверджена сертифікатами
            <br class="lg:block hidden">
            та визнанням у галузі
          </h1>

          <p class="lg:w-[795px] w-full mx-auto text-center text-[#464B57] lg:text-[20px] text-[14px] lato-m">
            Наша мета полягає в сталому розвитку деревообробної галузі шляхом впровадження інноваційних технологій, що зменшують карбоновий слід у будівництві, а також підтримують циркулярну біоекономіку
          </p>

          <div class="flex justify-center lg:gap-[42px] gap-[14px] lg:mt-[35px] mt-[24px]">
              <div class="w-[152px] flex flex-col justify-end">
                  <img src="/assets/img/icons/sirculation.svg" class="mx-auto lg:max-w-[90px] max-w-[60px]" alt="">
                  <h1 class="text-[#464B57] lato lato-b text-center lg:text-[16px] text-[11px]">
                    Циркулярність
                  </h1>
              </div>

            <div class="w-[152px] flex flex-col justify-end">
              <img src="/assets/img/icons/sertificate.svg" class="mx-auto  lg:max-w-[90px] max-w-[60px]" alt="">
              <h1 class="text-[#464B57] lato lato-b text-center lg:text-[16px] text-[11px]">
                Відповідність
              </h1>
            </div>

            <div class="w-[152px] flex flex-col justify-end">
              <img src="/assets/img/icons/stabilty.svg" class="mx-auto lg:max-w-[90px] max-w-[60px]" alt="">
              <h1 class="text-[#464B57] lato lato-b text-center lg:text-[16px] text-[11px]">
                Сталість
              </h1>
            </div>
          </div>
        </div>

      <div class="mb-[120px]">
        <h1 class="lg:text-[30px] text-[22px] text-[#000] lato-e mb-[24px]">
          Новини
        </h1>

        <div class="flex gap-[12px] mb-[48px] md:flex-nowrap flex-wrap">
          <div class="p-[14px] border-[#ECEDEE] h-[452px] lg:mb-[12px] border border-solid shadow flex flex-col gap-[18px] lg:w-[324px] w-full">
            <img class="object-center w-full max-h-[200px] object-contain lg:max-h-auto lg:object-cover" src="/assets/img/news-1.png" alt="">

            <div>
              <h1 class="mb-[12px] text-[#464B57] lato lato-b mb-[12px] text-[20px] leading-[25px]">
                Výběr kvalitních materiálů pro konstrukce dřevostavby
              </h1>

              <div class="flex items-center">
                <div class="px-[12px] text-[12px] h-[24] leading-[24px] bg-[#F6F6F6]">
                  Житлові будівлі
                </div>

                <div class="ml-[12px] text-[#8F9297] text-[12px] lato">
                  October 30, 2017
                </div>
              </div>
            </div>

            <div class="-my-[10px]">
              <p class="text-[#61656F] text-[18px] lato-s leading-[24px]">
                V době, kdy se nacházíme na křižovatce mezi ekologickým chováním a ekonomickou efektivitou
              </p>

              <nuxt-link to="/news/2" class="h-[42px] shrink-0 w-full bg-[#FAFAFA] hover:bg-[#F4F9F4] group border-[#ECEDEE] mt-[24px] border border-solid text-[#464B57] hover:text-[#419B44] flex items-center justify-center cursor-pointer">
                <span class="flex lato-s gap-[10px] text-[16px] items-center">
                   Читати більше

                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px] group-hover:hidden block" alt="">
                  <img src="/assets/img/icons/caret-right-active.svg" draggable="false" class="w-[20px] h-[20px] group-hover:block hidden" alt="">
                </span>
              </nuxt-link>
            </div>

          </div>

          <div class="p-[14px] border-[#ECEDEE] h-[452px] lg:mb-[12px] border border-solid shadow flex flex-col gap-[18px] lg:w-[324px] w-full">
            <img class="object-center w-full max-h-[200px] object-contain lg:max-h-auto lg:object-cover" src="/assets/img/news-1.png" alt="">

            <div>
              <h1 class="mb-[12px] text-[#464B57] lato lato-b mb-[12px] text-[20px] leading-[25px]">
                Výběr kvalitních materiálů pro konstrukce dřevostavby
              </h1>

              <div class="flex items-center">
                <div class="px-[12px] text-[12px] h-[24] leading-[24px] bg-[#F6F6F6]">
                  Житлові будівлі
                </div>

                <div class="ml-[12px] text-[#8F9297] text-[12px] lato">
                  October 30, 2017
                </div>
              </div>
            </div>

            <div class="-my-[10px]">
              <p class="text-[#61656F] text-[18px] lato-s leading-[24px]">
                V době, kdy se nacházíme na křižovatce mezi ekologickým chováním a ekonomickou efektivitou
              </p>

              <nuxt-link to="/news/2" class="h-[42px] shrink-0 w-full bg-[#FAFAFA] hover:bg-[#F4F9F4] group border-[#ECEDEE] mt-[24px] border border-solid text-[#464B57] hover:text-[#419B44] flex items-center justify-center cursor-pointer">
                <span class="flex lato-s gap-[10px] text-[16px] items-center">
                   Читати більше

                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px] group-hover:hidden block" alt="">
                  <img src="/assets/img/icons/caret-right-active.svg" draggable="false" class="w-[20px] h-[20px] group-hover:block hidden" alt="">
                </span>
              </nuxt-link>
            </div>

          </div>

          <div class="p-[14px] border-[#ECEDEE] h-[452px] lg:mb-[12px] border border-solid shadow flex flex-col gap-[18px] lg:w-[324px] w-full">
            <img class="object-center w-full max-h-[200px] object-contain lg:max-h-auto lg:object-cover" src="/assets/img/news-1.png" alt="">

            <div>
              <h1 class="mb-[12px] text-[#464B57] lato lato-b mb-[12px] text-[20px] leading-[25px]">
                Výběr kvalitních materiálů pro konstrukce dřevostavby
              </h1>

              <div class="flex items-center">
                <div class="px-[12px] text-[12px] h-[24] leading-[24px] bg-[#F6F6F6]">
                  Житлові будівлі
                </div>

                <div class="ml-[12px] text-[#8F9297] text-[12px] lato">
                  October 30, 2017
                </div>
              </div>
            </div>

            <div class="-my-[10px]">
              <p class="text-[#61656F] text-[18px] lato-s leading-[24px]">
                V době, kdy se nacházíme na křižovatce mezi ekologickým chováním a ekonomickou efektivitou
              </p>

              <nuxt-link to="/news/2" class="h-[42px] shrink-0 w-full bg-[#FAFAFA] hover:bg-[#F4F9F4] group border-[#ECEDEE] mt-[24px] border border-solid text-[#464B57] hover:text-[#419B44] flex items-center justify-center cursor-pointer">
                <span class="flex lato-s gap-[10px] text-[16px] items-center">
                   Читати більше

                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px] group-hover:hidden block" alt="">
                  <img src="/assets/img/icons/caret-right-active.svg" draggable="false" class="w-[20px] h-[20px] group-hover:block hidden" alt="">
                </span>
              </nuxt-link>
            </div>

          </div>

        </div>

        <nuxt-link href="/news" class="table mx-auto text-[#1F1C25] text-[16px] lato-m leading-[26px] underline underline-offset-[4px] hover:text-[#419B44] hover:underline">
          Усі новини
        </nuxt-link>
      </div>
    </div>
</template>

<script>

</script>

<style scoped>

</style>

