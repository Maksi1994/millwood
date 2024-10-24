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

              <h1 class="text-[#464B57] text-[20px] lato-b leading-[125px] text-center">
                Індустріальні будівлі
              </h1>
            </nuxt-link>

            <nuxt-link to="/solution-2" class="border border-solid border-[#ECEDEE] md:w-[316px] w-full h-[305px] flex flex-col justify-between shadow">
              <div class="px-[9xp]">
                <img src="/assets/img/living.png" alt="" class="w-full mx-auto max-w-[300px] h-[180px]">
              </div>

              <h1 class="text-[#464B57] text-[20px] lato-b leading-[125px] text-center">
                Житлові будівлі
              </h1>
            </nuxt-link>

            <nuxt-link to="/solution-3" class="border border-solid border-[#ECEDEE] md:w-[316px] w-full h-[305px] flex flex-col justify-between shadow">
              <div class="px-[9xp] py-[19px]">
                <img src="/assets/img/social.png" alt="" class="w-full max-w-[168px] h-[168px] mx-auto">
              </div>

              <h1 class="text-[#464B57] text-[20px] lato-b leading-[50px] h-full text-center">
                Соціальні будівлі
              </h1>
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

              <nuxt-link to="/material-1" class="h-[42px] shrink-0 w-full bg-[#FAFAFA] border-[#ECEDEE] lg:mt-[24px] border border-solid text-[#464B57] flex items-center justify-center cursor-pointer">
                <span class="flex gap-[10px] text-[16px]">
                  Детальніше

                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px]" alt="">
                </span>
              </nuxt-link>
            </div>

            <div class="border h-[346px] border-solid border-[#ECEDEE] lg:w-[316px] w-full h-[346px] flex flex-col shadow p-[14px] gap-[10px]">
              <div>
                <img src="/assets/img/material-2.png" alt="" class="w-full lg:h-[166px] mx-auto max-w-[300px] object-[20px_-25px]">
              </div>

              <h1 class="text-[#464B57] text-[20px] lato-m leading-normal">
                <span class="break-keep">Клеєна деревина з шиповими</span>  <br> з’єднаннями (kvh с24)
              </h1>

              <nuxt-link to="/material-2" class="h-[42px] w-full bg-[#FAFAFA] border-[#ECEDEE] border lg:mt-[24px] border-solid text-[#464B57] items-center shrink-0 flex justify-center cursor-pointer">
                <span class="flex gap-[10px] text-[16px]">
                  Детальніше

                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px]" alt="">
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

              <nuxt-link to="/material-3" class="h-[42px] w-full bg-[#FAFAFA] border-[#ECEDEE] border lg:mt-[24px] border-solid text-[#464B57] items-center shrink-0  flex justify-center cursor-pointer">
                <span class="flex gap-[10px] text-[16px]">
                  Детальніше

                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px]" alt="">
                </span>
              </nuxt-link>
            </div>
          </div>


        </div>

        <div class="lg:w-[100vw] lg:mb-[38px] mb-[48px] lg:-ml-[calc((100vw-996px)/2)] bg-[#F4F9F4] py-[42px] lg:mr-0 -mx-[16px] lg:px-0 px-[16px]">
          <h1 class="text-[#419B44] text-center lg:text-[32px] text-[20px] lato-e leading-[35px] mb-[25px]">
            Наша продукція підтверджена сертифікатами
            <br class="lg:block hidden">Наша продукці
            та визнанням у галузі
          </h1>

          <p class="lg:w-[795px] w-full mx-auto text-center text-[#464B57] lg:text-[20px] text-[14px] lato-m">
            Наша мета полягає в сталому розвитку деревообробної галузі шляхом впровадження інноваційних технологій, що зменшують карбоновий слід у будівництві, а також підтримують циркулярну біоекономіку
          </p>

          <div class="flex justify-center lg:gap-[42px] gap-[14px] lg:mt-[42px] mt-[24px]">
              <div class="w-[152px] flex flex-col justify-end">
                  <img src="/assets/img/icons/sirculation.svg" class="mx-auto lg:max-w-[90px] max-w-[60px]" alt="">
                  <h1 class="text-[#464B57] lato lato-b text-center lg:text-[16px] text-[11px] mt-[5px] uppercase">
                    Циркулярність
                  </h1>
              </div>

            <div class="w-[152px] flex flex-col justify-end">
              <img src="/assets/img/icons/sertificate.svg" class="mx-auto lg:py-[19px] pb-[5px] lg:max-w-[90px] max-w-[60px]" alt="">
              <h1 class="text-[#464B57] lato lato-b text-center lg:text-[16px] text-[11px] mt-[5px] uppercase">
                Відповідність
              </h1>
            </div>

            <div class="w-[152px] flex flex-col justify-end">
              <img src="/assets/img/icons/stabilty.svg" class="mx-auto lg:py-[9px] lg:max-w-[90px] max-w-[60px]" alt="">
              <h1 class="text-[#464B57] lato lato-b text-center lg:text-[16px] text-[11px] mt-[5px] uppercase">
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
          <div class="p-[14px] border-[#ECEDEE] border border-solid shadow flex flex-col gap-[18px] lg:w-[324px] w-full">
            <img class="object-center w-full max-h-[200px] object-contain lg:max-h-auto lg:object-cover" src="/assets/img/news-1.png" alt="">

            <div>
              <h1 class="mb-[12px] text-[#464B57] lato lato-b mb-[12px]">
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

            <div>
              <p class="text-[#61656F] text-[18px] lato-s leading-[24px]">
                V době, kdy se nacházíme na křižovatce mezi ekologickým chováním a ekonomickou efektivitou
              </p>

              <nuxt-link to="/news/1" class="py-[12px] px-[24px] cursor-pointer lato-m text-[#464B57] text-center mt-[24px] lg:flex hidden items-center justify-center">
                Читати більше

                <img draggable="false" src="/assets/img/icons/caret-right.png" class="w-[20px] h-[20px] ml-[10px]" alt="">
              </nuxt-link>
            </div>

          </div>

          <div class="p-[14px] border-[#ECEDEE] border border-solid shadow flex flex-col gap-[18px] lg:w-[324px] w-full">
            <img class="object-center w-full max-h-[200px] object-contain lg:max-h-auto lg:object-cover" src="/assets/img/news-2.png" alt="">

            <div>
              <h1 class="mb-[12px] text-[#464B57] lato lato-b mb-[12px]">
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

            <div>
              <p class="text-[#61656F] text-[18px] lato-s leading-[24px]">
                V době, kdy se nacházíme na křižovatce mezi ekologickým chováním a ekonomickou efektivitou
              </p>

              <nuxt-link to="/news/1" class="py-[12px] px-[24px] cursor-pointer lato-m text-[#464B57] text-center mt-[24px] lg:flex hidden items-center justify-center">
                Читати більше

                <img draggable="false" src="/assets/img/icons/caret-right.png" class="w-[20px] h-[20px] ml-[10px]" alt="">
              </nuxt-link>
            </div>

          </div>

          <div class="p-[14px] border-[#ECEDEE] border border-solid shadow flex flex-col gap-[18px] lg:w-[324px] w-full">
            <img class="object-center w-full max-h-[200px] object-contain lg:max-h-auto lg:object-cover" src="/assets/img/news-3.png" alt="">

            <div>
              <h1 class="mb-[12px] text-[#464B57] lato lato-b mb-[12px]">
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

            <div>
              <p class="text-[#61656F] text-[18px] lato-s leading-[24px]">
                V době, kdy se nacházíme na křižovatce mezi ekologickým chováním a ekonomickou efektivitou
              </p>

              <nuxt-link to="/news/1" class="py-[12px] px-[24px] cursor-pointer lato-m text-[#464B57] text-center mt-[24px] lg:flex hidden items-center justify-center">
                Читати більше

                <img draggable="false" src="/assets/img/icons/caret-right.png" class="w-[20px] h-[20px] ml-[10px]" alt="">
              </nuxt-link>
            </div>

          </div>
        </div>

        <nuxt-link href="/news" class="table mx-auto text-[#1F1C25] text-[16px] lato-m leading-[26px] underline underline-offset-[4px]">
          Усі новини
        </nuxt-link>
      </div>
    </div>
</template>

<script>

</script>

<style scoped>

</style>

