<template id="contacts">
  <div class="md:w-[50%]">
    <h2 class="text-center font-poppins uppercase font-black text-black text-[40px] md:text-[50px]">
      Gommista
    </h2>
    <div class="m-auto mt-20 w-fit text-center relative items-center flex">
      <img src="../assets/images/fotoprofilo.webp"
        class="w-[85%] z-10 m-auto my-auto md:w-[25vw] md:min-w-[400px] md:min-h-[400px]"
        alt="Foto del gommista Luigi Di Maio" id="profile" />
      <p
        class="bg-red-700 font-inter italic font-[600] px-14 py-5 w-fit z-10 bottom-[20px] right-[15px] absolute text-white text-[15px]">
        Luigi Di Maio
      </p>
    </div>
  </div>

  <div
    class="md:w-[50%] md:text-center text-left text-black relative md:mt-0 mt-20 font-inter flex-col flex justify-center items-center">
    <div class="w-[85%] md:w-1/2">
      <div class="w-full">
        <h2
          class="md:text-left text-center mb-5 font-poppins uppercase font-black text-black text-[40px] md:text-[50px]">
          Contatti
        </h2>
      </div>
      <div class="w-full md:flex block md:flex-col flex-row gap-10">
        <div class="md:text-left text-center w-full md:w-auto md:mb-0 gap-2 mb-6 flex flex-col md:gap-3">
          <p class="font-[600] underline-offset-2 underline">Indirizzo</p>
          <p>
            <font-awesome-icon :icon="['fas', 'location-dot']" aria-hidden="true" />
            Via del Biancospino,
            <span class="inline"> 04023 Formia (LT) </span>
          </p>
        </div>
        <div class="flex mt-10 md:mt-0 md:gap-20">
          <div class="w-1/2 md:w-auto gap-2 md:text-left text-center flex flex-col md:justify-start md:gap-3">
            <p class="font-[600] underline-offset-2 underline">Telefono</p>
            <p>
              <font-awesome-icon :icon="['fas', 'phone']" aria-hidden="true" />
              <a href="tel:0771736786"> 0771 736786</a>
            </p>
          </div>
          <div class="w-1/2 md:w-auto gap-2 md:text-left text-center flex flex-col md:justify-start md:gap-3">
            <p class="font-[600] underline-offset-2 underline">Orario</p>
            <div class="flex gap-2 justify-center">
              <div class="padding-top-3">
                <font-awesome-icon :icon="['fas', 'clock']" aria-hidden="true" />
              </div>

              <div class="text-center">
                <p>
                  7:45 - 12:45
                  <span class="block">14:30 - 18:45</span>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
