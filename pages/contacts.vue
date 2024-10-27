<template>
  <breadcrumbs page="Звʼязатися"/>

  <div class="lg:px-[48px] px-0 lg:mt-[20px] mt-[28px]">
    <div class="flex lg:flex-row flex-col lg:gap-[127px] gap-[28px] lg:items-end items-center mb-[48px]">
      <div class="lg:w-[386px] w-full">
        <img draggable="false" class="mx-auto" src="/assets/img/founder.png" alt="">
        <div class="text-[#1F1C25] text-[16px] flex items-center justify-center h-[48px] lato-m border border-solid border-[#ECEDEE] bg-[#FAFAFA]">
          <img draggable="false" class="w-[20px] h-[20px] mr-[8px]" src="/assets/img/icons/mail.svg"> i.bukhanevych@millwood.com.ua
        </div>
      </div>


      <form class="lg:w-[387px] w-full">
        <h1 class="text-[#1F1C25] lg:text-[28px] leading-[33px] text-[22px] lato-b lg:text-left text-center">
          У вас є запитання?
        </h1>
        <p class="text-[#61656F] lg:text-[20px] text-[16px] lato-m mb-[25px] lg:text-left text-center">
          Ми з радістю проконсультуємо!
        </p>


        <div class="flex flex-col gap-[7px] mb-[24px]">
          <input class="p-[10px] border-b border-solid border-[#D9D9D9] lg:text-[18px] text-[16px] text-[#1F1C25] border-b-2	outline-0	focus:border-[#419B44]" placeholder="Ваше Імʼя" type="text"/>

          <input class="p-[10px] border-b border-solid border-[#D9D9D9] lg:text-[18px] text-[16px] text-[#1F1C25] border-b-2	outline-0	focus:border-[#419B44]" placeholder="E-mail" type="email"/>

          <input class="p-[10px] border-b border-solid border-[#D9D9D9] lg:text-[18px] text-[16px] text-[#1F1C25] border-b-2	outline-0	focus:border-[#419B44]" placeholder="Номер телефону" type="email"/>

          <textarea class="p-[10px] border-b border-solid border-[#D9D9D9] resize-none lg:min-h-[100px] min-h-[80px] lg:text-[18px] text-[16px] text-[#1F1C25] border-b-2 outline-0 focus:border-[#419B44]" placeholder="Ваше повідомлення" type="email"></textarea>
        </div>

        <div class="flex items-center gap-[12px] text-[#61656F] text-[14px] lato-m mb-[35px]">

          <label class="custom-checkbox">
            <input type="checkbox" />
            <span class="checkmark"></span>
          </label>

          <div>
            Я згоден на обробку персональних даних
          </div>

        </div>

        <button class="bg-[#D9EBDA] h-[48px] w-full flex justify-center items-center text-white lato-s">
          Відправити
        </button>
      </form>
    </div>

    <div class="mb-[64px] w-full">

    </div>
  </div>
</template>

<style scoped>
/* Hide the default checkbox */
.custom-checkbox input[type="checkbox"] {
  display: none;
}

/* Style the custom checkbox */
.custom-checkbox {
  position: relative;
  display: inline-block;
  width: 25px;
  height: 25px;
  background-color: #fff;
  border-radius: 4px;
  cursor: pointer;
  background-image: url('/assets/img/icons/checkbox-wrap.svg'); /* Custom image */
  background-size: cover;
}

/* Create the checkmark box */
.custom-checkbox .checkmark {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: url('/assets/img/icons/checkbox-fill.svg'); /* Custom image */
  background-size: cover;
  display: none;
}

/* Show the checkmark when the checkbox is checked */
.custom-checkbox input[type="checkbox"]:checked + .checkmark {
  display: block;
}

</style>
