<script>
export default {
  methods: {
    handleClick() {
      const contactsSection = document.getElementById("info");
      if (contactsSection) {
        contactsSection.scrollIntoView({
          behavior: "smooth",
        });
      }
    },
  },
};
</script>

<template>
  <header class="text-white bg-white">
    <nav class="py-2 md:py-3 font-racing fixed top-0 w-full z-20 bg-black">
      <h1 class="text-center text-white text-[30px]">DML</h1>
      <span aria-hidden="true"
        class="bg-gradient-to-r from-black via-gray-400 to-black h-[1px] w-full absolute bottom-0"></span>
    </nav>
    <div
      class="hero-bg md:relative h-screen bg-[url('/hero-mobile.webp')] md:bg-fixed md:bg-no-repeat bg-cover md:bg-[url('/hero-desktop.webp')] pt-[0vh] md:pt-[10vh] md:h-[100vh] bg-bottom md:bg-center p-10 flex flex-col text-left md:justify-center">
      <div class="md:w-[88%] m-auto">
        <h2 class="md:text-[4vw] w-[80%] md:w-[500px] block uppercase leading-tight">
          Il Tuo Partner per Gomme a
          <span class="text-stroke-trick text-transparent">Formia!</span>
        </h2>
        <h3 class="w-[80%] md:text-[20px] font-inter text-[16px] md:w-[500px] mt-5">
          Servizi completi per pneumatici auto, camion, moto e altro ancora...
        </h3>

        <button class="mt-7 bg-red-600 py-1 px-6 rounded-full md:text-[1.4vw] text-[20px] font-racing w-fit md:mx-auto"
          @click="handleClick">
          CONTATTI
        </button>
      </div>
    </div>
  </header>
</template>

<style scoped>
.text-stroke-trick {
  color: black;
  -webkit-text-fill-color: transparent;
  -webkit-text-stroke: 2px white;
}
</style>
