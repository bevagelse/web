<script>
export default {
  head: {
    title: 'Kontakt - Bevägelse',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Uanset om din henvendelse skyldes, du har tabt træningsmotivationen eller fundet et hul i kalenderen til en workshop med kollegaerne. Om bikini-sæsonen truer, eller skulderen driller. Skriv endelig! Så vender jeg tilbage hurtigst muligt.'
      }
    ]
  }
}
</script>
<template>
  <div class="bg-white overflow-hidden">

  <PageHero>
    <template v-slot:headline>Jeg glæder mig til at høre fra dig</template>
    <template v-slot:teaser>Uanset om din henvendelse skyldes, du har tabt træningsmotivationen eller fundet et hul i kalenderen til en workshop med kollegaerne. Om bikini-sæsonen truer, eller skulderen driller. Skriv endelig! Så vender jeg tilbage hurtigst muligt.</template>
  </PageHero>

    
    <div class="relative max-w-6xl mx-auto py-8 px-4 sm:px-6 lg:px-8">
      <form action="https://app.99inbound.com/api/e/oNNqCv1X" method="POST" class="space-y-8 divide-y divide-gray-200">
        <div class="space-y-8 divide-y divide-gray-200 sm:space-y-5">
          <div>
            <div>
              <h2>Kontakt</h2>
            </div>

            <div class="space-y-6 sm:space-y-5">
              <div class="sm:grid sm:grid-cols-3 sm:gap-4 sm:items-start sm:border-t sm:border-gray-200 sm:pt-5">
                <label for="first-name" class="block text-sm font-medium text-gray-700 sm:mt-px sm:pt-2">Navn</label>
                <div class="mt-1 sm:mt-0 sm:col-span-2">
                  <input type="text" name="name" id="first-name" autocomplete="given-name" class="max-w-lg block w-full shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:max-w-xs sm:text-sm border-gray-300 rounded-md">
                </div>
              </div>

              <div class="sm:grid sm:grid-cols-3 sm:gap-4 sm:items-start sm:border-t sm:border-gray-200 sm:pt-5">
                <label for="first-name" class="block text-sm font-medium text-gray-700 sm:mt-px sm:pt-2">Telefon</label>
                <div class="mt-1 sm:mt-0 sm:col-span-2">
                  <input type="text" name="phone" id="first-name" autocomplete="given-name" class="max-w-lg block w-full shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:max-w-xs sm:text-sm border-gray-300 rounded-md">
                </div>
              </div>

              <div class="sm:grid sm:grid-cols-3 sm:gap-4 sm:items-start sm:border-t sm:border-gray-200 sm:pt-5">
                <label for="first-name" class="block text-sm font-medium text-gray-700 sm:mt-px sm:pt-2">E-mail</label>
                <div class="mt-1 sm:mt-0 sm:col-span-2">
                  <input type="text" name="email" id="first-name" autocomplete="given-name" class="max-w-lg block w-full shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:max-w-xs sm:text-sm border-gray-300 rounded-md">
                </div>
              </div>

              <div class="sm:grid sm:grid-cols-3 sm:gap-4 sm:items-start sm:border-t sm:border-gray-200 sm:pt-5">
                <label for="about" class="block text-sm font-medium text-gray-700 sm:mt-px sm:pt-2">Besked</label>
                <div class="mt-1 sm:mt-0 sm:col-span-2">
                  <textarea id="about" name="message" rows="3" class="max-w-lg shadow-sm block w-full focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm border border-gray-300 rounded-md"></textarea>
                  <p class="mt-2 text-sm text-gray-500">Skriv en besked til mig.</p>
                </div>
              </div>
            </div>

          </div>
        </div>

        <div class="pt-5">
          <div class="flex justify-end">
            <div class="rounded-md shadow">
              <button type="submit" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-extrabold rounded-md text-bevagelse-blue-dark bg-bevagelse-yellow no-underline uppercase hover:bg-bevagelse-blue-dark hover:text-white md:py-4 md:text-lg md:px-10">Send</button>
            </div>
          </div>
        </div>
      </form>
    </div>
    <div class="mb-16">&nbsp;</div>
  </div>

  
 
</template>