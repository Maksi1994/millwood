<template>
    <!--
    <navigation-board/>
    -->

    <div class="mt-[10px] w-full lato">
        <div class="lg:h-[450px] h-[320px] w-full bg-[url(/assets/img/bg.png)] bg-no-repeat bg-center relative lg:mb-[110px] mb-[14px] bg-cover">
          <div class="absolute lg:table hidden left-0 top-0 bottom-0 m-auto table p-[24px] bg-white w-[540px]">
            <h1 class="text-[#419B44] uppercase text-[30px] font-extrabold mb-[14px]">
              Зелене будівництво — вибір <br> для відновлення України
            </h1>

            <p class="text-[#464B57] text-[16px] font-semibold leading-[24px]">
              Наша місія полягає в наданні ефективних, надійних та екологічно сталих рішень для будівництва.
            </p>
          </div>
        </div>

      <div class="lg:hidden block w-full mb-[62px]">
        <h1 class="text-[#419B44] uppercase text-[22px] font-extrabold mb-[14px] text-[22px]">
          Зелене будівництво — вибір для відновлення України
        </h1>

        <p class="text-[#464B57] text-[16px] font-semibold leading-[24px]">
          Наша місія полягає в наданні ефективних, надійних та екологічно сталих рішень для будівництва.
        </p>
      </div>

        <div class="mb-[62px]">
          <h1 class="lg:text-[30px] text-[22px] text-[#464B57] font-extrabold mb-[24px]">
            Будівельні концепції
          </h1>

          <div class="flex gap-[24px] md:flex-nowrap flex-wrap">
            <div class="border border-solid border-[#ECEDEE] md:w-[316px] w-full h-[305px] flex flex-col justify-between shadow">
              <div class="px-[9xp] py-[19px]">
                <img src="/assets/img/industrial.png" alt="" class="w-full mx-auto max-w-[300px]">
              </div>

              <h1 class="text-[#464B57] text-[20px] font-bold leading-[87px] text-center">
                Індустріальні будівлі
              </h1>
            </div>

            <div class="border border-solid border-[#ECEDEE] md:w-[316px] w-full h-[305px] flex flex-col justify-between shadow">
              <div class="px-[9xp] py-[19px]">
                <img src="/assets/img/living.png" alt="" class="w-full mx-auto max-w-[300px]">
              </div>

              <h1 class="text-[#464B57] text-[20px] font-bold leading-[87px] text-center">
                Житлові будівлі
              </h1>
            </div>

            <div class="border border-solid border-[#ECEDEE] md:w-[316px] w-full h-[305px] flex flex-col justify-between shadow">
              <div class="px-[9xp] py-[19px]">
                <img src="/assets/img/social.png" alt="" class="w-full max-w-[168px] h-[168px] mx-auto">
              </div>

              <h1 class="text-[#464B57] text-[20px] font-bold leading-[87px] text-center">
                Соціальні будівлі
              </h1>
            </div>
          </div>
        </div>

        <div class="mb-[110px]">
          <h1 class="lg:text-[30px] text-[22px] text-[#464B57] font-extrabold mb-[24px]">
            Будівельні матеріали
          </h1>

          <div class="flex gap-[24px] md:flex-nowrap flex-wrap">
            <div class="border h-[346px] border-solid border-[#ECEDEE] lg:w-[316px] w-full h-[346px] p-[14px] flex flex-col gap-[24px] shadow">
              <div>
                <img src="/assets/img/material-1.png" alt="" class="w-full lg:h-[166px] mx-auto max-w-[300px]">
              </div>

              <h1 class="text-[#464B57] text-[20px] font-medium leading-normal">
                Конструкційна
                <br>
                деревина C24
              </h1>
              
              <div class="h-[42px] shrink-0 w-full bg-[#FAFAFA] border-[#ECEDEE] border border-solid text-[#464B57] flex items-center justify-center cursor-pointer">
                <span class="flex gap-[10px] text-[16px]">
                  Детальніше
                  
                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px]" alt="">
                </span>
              </div>
            </div>

            <div class="border h-[346px] border-solid border-[#ECEDEE] lg:w-[316px] w-full h-[346px] flex flex-col shadow p-[14px] gap-[24px]">
              <div>
                <img src="/assets/img/material-2.png" alt="" class="w-full lg:h-[166px] mx-auto max-w-[300px]">
              </div>

              <h1 class="text-[#464B57] text-[20px] font-medium leading-normal">
               <span class="break-keep">Клеєна деревина з шиповими</span>  <br> з’єднаннями (kvh с24)
              </h1>

              <div class="h-[42px] w-full bg-[#FAFAFA] border-[#ECEDEE] border border-solid text-[#464B57] items-center shrink-0 flex justify-center cursor-pointer">
                <span class="flex gap-[10px] text-[16px]">
                  Детальніше

                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px]" alt="">
                </span>
              </div>
            </div>

            <div class="border h-[346px] border-solid border-[#ECEDEE] lg:w-[316px] w-full h-[346px] flex flex-col shadow p-[14px] gap-[24px]">
              <div>
                <img src="/assets/img/material-3.png" alt="" class="w-full lg:h-[166px] mx-auto max-w-[300px]">
              </div>

              <h1 class="text-[#464B57] text-[20px] font-medium leading-normal">
                Клеєна багатошарова <br> деревина (GLT/Glulam)
              </h1>

              <div class="h-[42px] w-full bg-[#FAFAFA] border-[#ECEDEE] border border-solid text-[#464B57] items-center shrink-0  flex justify-center cursor-pointer">
                <span class="flex gap-[10px] text-[16px]">
                  Детальніше

                  <img src="/assets/img/icons/button-arrow.png" draggable="false" class="w-[20px] h-[20px]" alt="">
                </span>
              </div>
            </div>
          </div>

        </div>

        <div class="lg:w-[100vw] mb-[110px] lg:-ml-[calc((100vw-996px)/2)] bg-[#F4F9F4] py-[42px]">
          <h1 class="text-[#419B44] text-center lg:text-[32px] text-[20px] font-extrabold leading-[35px] mb-[25px]">
            Наша продукція підтверджена сертифікатами
            <br>
            та визнанням у галузі
          </h1>

          <p class="lg:w-[795px] w-full mx-auto text-center text-[#464B57] lg:text-[20px] text-[14px] font-medium">
            Наша мета полягає в сталому розвитку деревообробної галузі шляхом впровадження інноваційних технологій, що зменшують карбоновий слід у будівництві, а також підтримують циркулярну біоекономіку
          </p>

          <div class="flex justify-center lg:gap-[42px] gap-[14px] lg:mt-[42px] mt-[24px]">
              <div class="w-[152px] flex flex-col justify-end">
                  <img src="/assets/img/icons/sirculation.svg" class="mx-auto lg:max-w-[90px] max-w-[60px]" alt="">
                  <h1 class="text-[#464B57] lato font-bold text-center lg:text-[16px] text-[11px] mt-[14px]">
                    Циркулярність
                  </h1>
              </div>

            <div class="w-[152px] flex flex-col justify-end">
              <img src="/assets/img/icons/sertificate.svg" class="mx-auto lg:py-[19px] pb-[5px] lg:max-w-[90px] max-w-[60px]" alt="">
              <h1 class="text-[#464B57] lato font-bold text-center lg:text-[16px] text-[11px] mt-[14px]">
                Відповідність
              </h1>
            </div>

            <div class="w-[152px] flex flex-col justify-end">
              <img src="/assets/img/icons/stabilty.svg" class="mx-auto lg:py-[9px] lg:max-w-[90px] max-w-[60px]" alt="">
              <h1 class="text-[#464B57] lato font-bold text-center lg:text-[16px] text-[11px] mt-[14px]">
                Сталість
              </h1>
            </div>
          </div>
        </div>

      <div class="mb-[120px]">
        <h1 class="lg:text-[30px] text-[22px] text-[#000] font-extrabold mb-[24px]">
          Новини
        </h1>

        <div class="flex gap-[12px] mb-[48px] md:flex-nowrap flex-wrap">
          <div class="p-[14px] border-[#ECEDEE] border border-solid shadow flex flex-col gap-[18px] lg:w-[324px] w-full">
            <img class="object-center w-full max-h-[200px] object-contain lg:max-h-auto lg:object-cover" src="/assets/img/news-1.png" alt="">

            <div>
              <h1 class="mb-[12px] text-[#464B57] lato font-bold mb-[12px]">
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
              <p class="text-[#61656F] text-[18px] font-semibold leading-[24px]">
                V době, kdy se nacházíme na křižovatce mezi ekologickým chováním a ekonomickou efektivitou
              </p>

              <div class="py-[12px] px-[24px] cursor-pointer font-medium text-[#464B57] text-center mt-[24px] flex items-center justify-center">
                Читати більше

                <img draggable="false" src="/assets/img/icons/caret-right.png" class="w-[20px] h-[20px] ml-[10px]" alt="">
              </div>
            </div>

          </div>

          <div class="p-[14px] border-[#ECEDEE] border border-solid shadow flex flex-col gap-[18px] lg:w-[324px] w-full">
            <img class="object-center w-full max-h-[200px] object-contain lg:max-h-auto lg:object-cover" src="/assets/img/news-2.png" alt="">

            <div>
              <h1 class="mb-[12px] text-[#464B57] lato font-bold mb-[12px]">
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
              <p class="text-[#61656F] text-[18px] font-semibold leading-[24px]">
                V době, kdy se nacházíme na křižovatce mezi ekologickým chováním a ekonomickou efektivitou
              </p>

              <div class="py-[12px] px-[24px] cursor-pointer font-medium text-[#464B57] text-center mt-[24px] flex items-center justify-center">
                Читати більше

                <img draggable="false" src="/assets/img/icons/caret-right.png" class="w-[20px] h-[20px] ml-[10px]" alt="">
              </div>
            </div>

          </div>

          <div class="p-[14px] border-[#ECEDEE] border border-solid shadow flex flex-col gap-[18px] lg:w-[324px] w-full">
            <img class="object-center w-full max-h-[200px] object-contain lg:max-h-auto lg:object-cover" src="/assets/img/news-3.png" alt="">

            <div>
              <h1 class="mb-[12px] text-[#464B57] lato font-bold mb-[12px]">
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
              <p class="text-[#61656F] text-[18px] font-semibold leading-[24px]">
                V době, kdy se nacházíme na křižovatce mezi ekologickým chováním a ekonomickou efektivitou
              </p>

              <div class="py-[12px] px-[24px] cursor-pointer font-medium text-[#464B57] text-center mt-[24px] flex items-center justify-center">
                Читати більше

                <img draggable="false" src="/assets/img/icons/caret-right.png" class="w-[20px] h-[20px] ml-[10px]" alt="">
              </div>
            </div>

          </div>
        </div>

        <a href="/" class="table mx-auto text-[#1F1C25] text-[16px] font-medium leading-[26px] underline underline-offset-[4px]">
          Усі новини
        </a>
      </div>
    </div>
</template>

<script>

</script>

<style scoped>
.shadow {
  box-shadow: 0px 54px 15px 0px rgba(0, 0, 0, 0.00), 0px 35px 14px 0px rgba(0, 0, 0, 0.00), 0px 19px 12px 0px rgba(0, 0, 0, 0.01), 0px 9px 9px 0px rgba(0, 0, 0, 0.02), 0px 2px 5px 0px rgba(0, 0, 0, 0.02);
}
</style>

