<template>
  <main class="lg:relative">
      <div class="mx-auto max-w-7xl w-full pt-16 pb-20 text-center lg:py-48 lg:text-left">
        <div class="px-4 lg:w-1/2 sm:px-8 xl:pr-16">
          <h1 class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl lg:text-5xl xl:text-6xl">
            <span class="block xl:inline text-bevagelse-blue-dark">BEVÄGELSE</span>
            <span class="block text-bevagelse-blue-light xl:inline">er slow performance coaching</span>
          </h1>
          <p class="mt-3 max-w-md mx-auto text-base text-black sm:text-xl md:mt-5 md:max-w-3xl">
            I en tid, hvor alting går stærkere, er bevägelse til, for at sætte tempoet ned.<br /><br />
            Bevägelse er hjælp til dig, så du kan leve et liv fri for smerter, stress og bekymringer. Et liv, hvor tid, fordybelse, eftertænksomhed, glæde og en dyb indre grundlæggende ro, har en naturlig plads.
          </p>
          <div class="mt-10 sm:flex sm:justify-center lg:justify-start">
            <div class="rounded-md shadow">
              <NuxtLink to="/ydelser/" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-extrabold rounded-md text-bevagelse-blue-dark bg-bevagelse-yellow no-underline uppercase hover:bg-bevagelse-blue-dark hover:text-white md:py-4 md:text-lg md:px-10">
                Læs mere om ydelser
              </NuxtLink>
            </div>
            <!-- <div class="mt-3 rounded-md shadow sm:mt-0 sm:ml-3">
              <NuxtLink to="/om-bevaegelse" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-light rounded-md text-white no-underline uppercase bg-bevagelse-blue-light hover:bg-bevagelse-blue-dark hover:text-white md:py-4 md:text-lg md:px-10">
                Læs mere
              </NuxtLink>
            </div> -->
          </div>
        </div>
      </div>
      <div class="relative w-full h-64 sm:h-72 md:h-96 lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2 lg:h-full">
        <img class="absolute inset-0 w-full h-full object-cover" src="~/assets/frontpage-hero.jpg" alt="">
      </div>
  </main>
</template>