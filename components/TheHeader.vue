<template>
  <div>
    <div class="absolute inset-0 shadow z-30 pointer-events-none" aria-hidden="true"></div>
    <div class="relative z-20 bg-bevagelse-blue-dark">
      <div class="max-w-7xl mx-auto flex justify-between items-center px-4 py-5 sm:px-6 sm:py-4 lg:px-8 md:justify-start md:space-x-10">
        <div>
          <NuxtLink to="/" class="flex">
            <span class="sr-only">Bevägelse</span>
            <img class="h-8 w-auto sm:h-16" src="~/assets/logo-blue-light.svg" alt="">
          </NuxtLink>
        </div>
        <div class="-mr-2 -my-2 md:hidden">
          <button @click="toggleBurger = !toggleBurger" type="button" class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500" aria-expanded="false">
            <span class="sr-only">Åbn menu</span>
            <!-- Heroicon name: outline/menu -->
            <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
            </svg>
          </button>
        </div>
        <div class="hidden md:flex-1 md:flex md:items-center md:justify-between">
          <nav class="flex space-x-10">
            <NuxtLink to="/ydelser/">Ydelser</NuxtLink>
            <NuxtLink to="/om-bevaegelse/">Om Bevägelse</NuxtLink>
            <NuxtLink to="/cases/" >Cases</NuxtLink>
            <NuxtLink to="/kontakt/">Kontakt</NuxtLink>
          </nav>
        </div>
      </div>
    </div>

    <!--
      Mobile menu, show/hide based on mobile menu state.

      Entering: "duration-200 ease-out"
        From: "opacity-0 scale-95"
        To: "opacity-100 scale-100"
      Leaving: "duration-100 ease-in"
        From: "opacity-100 scale-100"
        To: "opacity-0 scale-95"
    -->
    <div id="burgermenu" v-show="toggleBurger" class="absolute z-30 top-0 inset-x-0 p-2 transition transform origin-top-right md:hidden">
      <div class="rounded-lg shadow-lg ring-1 ring-black ring-opacity-5 bg-white divide-y-2 divide-gray-50">
        <div class="pt-5 pb-6 px-5 sm:pb-8">
          <div class="flex items-center justify-between">
            <div>
              <img class="h-8 w-auto" src="~/assets/logo.svg" alt="Bevägelse">
            </div>
            <div class="-mr-2">
              <button @click="toggleBurger = !toggleBurger" type="button" class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500">
                <span class="sr-only">Luk menu</span>
                <!-- Heroicon name: outline/x -->
                <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                </svg>
              </button>
            </div>
          </div>
          <div class="mt-6 sm:mt-8">
            <nav>
              <div class="grid gap-7 sm:grid-cols-2 sm:gap-y-8 sm:gap-x-4">
                <NuxtLink to="/" class="-m-3 flex items-center p-3 rounded-lg hover:bg-gray-50">
                  <div class="ml-4 text-xl text-bevagelse-blue-dark">
                    Hjem
                  </div>
                </NuxtLink>

                <NuxtLink to="/ydelser/" class="-m-3 flex items-center p-3 rounded-lg hover:bg-gray-50">
                  <div class="ml-4 text-xl text-bevagelse-blue-dark">
                    Ydelser
                  </div>
                </NuxtLink>

                <NuxtLink to="/om-bevaegelse/" class="-m-3 flex items-center p-3 rounded-lg hover:bg-gray-50">
                  <div class="ml-4 text-xl text-bevagelse-blue-dark">
                    Om Bevägelse
                  </div>
                </NuxtLink>

                <NuxtLink to="/cases/" class="-m-3 flex items-center p-3 rounded-lg hover:bg-gray-50">
                  <div class="ml-4 text-xl text-bevagelse-blue-dark">
                    Cases
                  </div>
                </NuxtLink>

                <NuxtLink to="/kontakt/" class="-m-3 flex items-center p-3 rounded-lg hover:bg-gray-50">
                  <div class="ml-4 text-xl text-bevagelse-blue-dark">
                    Kontakt
                  </div>
                </NuxtLink>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  export default {
    data() {
      return {
        toggleBurger: false
      }
    },
    watch: {
      '$route' () {
        this.toggleBurger = false
      }
    }
  }
</script>
