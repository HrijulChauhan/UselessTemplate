<template>
  <section class="w-[80%] xl:w-[50%] rounded-md mx-auto lg:mt-48 mt-16">
    <div class="font-[SerifSemibold] text-[3em] flex items-center">A new template to feel smarter</div>
    <div class="w-full xl:w-3/4 font-[SansLight] text-[1.25rem]">
      <p>&nbsp;</p>
      <p>
        Just making a new template starter repo because I got tired of having to setup vue-router over and over again.
        Equipped with router, tailwind along with headless ui and heroicons already setup. VictorSerif + LabilGrotesk
        font provided by <a href="https://www.kometa.xyz/buy/victor-serif/" class="text-orange-700">Kometa.</a>
      </p>
    </div>
  </section>
</template>

<style>
@font-face {
  font-family: SerifMedium;
  src: url(../../assets/VictorSerifTrial-50Medium.woff2);
}
@font-face {
  font-family: SerifSemibold;
  src: url(../../assets/VictorSerifTrial-60Semibold.woff2);
}
@font-face {
  font-family: SansLight;
  src: url(../../assets/LabilGroteskTrial-Light.woff2);
}
@font-face {
  font-family: SansMed;
  src: url(../../assets/LabilGroteskTrial-Medium.w);
}

:root {
  --heading_display: 3rem;
}

.heading__text {
  font-family: "SerifMedium";
}

.scale {
  height: var(--heading_display);
  width: var(--heading_display);
}

div img {
  height: 4rem;
  width: auto;
}
</style>
