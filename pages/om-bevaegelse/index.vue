<script>
export default {
  head: {
    title: 'Om Bevägelse - Bevägelse',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Bag Bevägelse står jeg, Kenneth Petersen. Jeg er uddannet fysioterapeut, kostvejleder og personlig træner. Jeg har over 15 års professionel erfaring i at hjælpe mennesker med problematikker så som smerter, skader, stress og depression.'
      }
    ]
  }
}
</script>
<template>
  <div class="bg-white overflow-hidden">

  <PageHero>
    <template v-slot:headline>Om Bevägelse</template>
    <template v-slot:teaser>Bag Bevägelse står jeg, Kenneth Petersen. Jeg er uddannet fysioterapeut, kostvejleder og personlig træner. Jeg har over 15 års professionel erfaring i at hjælpe mennesker med problematikker så som smerter, skader, stress og depression.</template>
  </PageHero>


  <div class="relative max-w-6xl mx-auto py-8 px-4 sm:px-6 lg:px-8">
    <div class="mt-8 lg:grid lg:grid-cols-2 lg:gap-8">
      <div class="relative lg:row-start-1 lg:col-start-2">
        <div class="relative text-base mx-auto max-w-prose lg:max-w-none">
          <figure>
            <div class="aspect-w-12 aspect-h-7 lg:aspect-none">
              <img class="rounded-lg shadow-lg object-cover object-center" src="~/assets/om-bevagelse.jpg" alt="Kenneth Petersen" width="1184" height="1376">
            </div>
            <figcaption class="mt-3 flex text-sm text-gray-500">
              <!-- Heroicon name: solid/camera -->
              <svg class="flex-none w-5 h-5 text-bevagelse-blue-light" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                <path fill-rule="evenodd" d="M4 5a2 2 0 00-2 2v8a2 2 0 002 2h12a2 2 0 002-2V7a2 2 0 00-2-2h-1.586a1 1 0 01-.707-.293l-1.121-1.121A2 2 0 0011.172 3H8.828a2 2 0 00-1.414.586L6.293 4.707A1 1 0 015.586 5H4zm6 9a3 3 0 100-6 3 3 0 000 6z" clip-rule="evenodd" />
              </svg>
              <span class="ml-2 text-bevagelse-blue-light font-poppins font-semibold">Foto fra Instragram @bevagelse</span>
            </figcaption>
          </figure>
        </div>
      </div>
      <div class="mt-8 lg:mt-0">
        <div class="mt-5 font-poppins text-black mx-auto lg:max-w-none lg:row-start-1 lg:col-start-1">
          <p>Jeg arbejder altid med det hele menneske i centrum. Det betyder, jeg ser på sundhed som menneskelig trivsel <i>både</i> fysisk og mentalt. Jeg arbejder i dag som Synskonsulent i Haderslev Kommune. Sideløbende driver jeg konsulentvirksomheden Bevägelse, der laver foredrag, workshops samt individuelle forløb og konsultationer. </p>
          <h2>Kvalificerede skub, der virker!</h2>
          <p>Min grundindstilling er, at det er fedt at være i live. Vi er i live, når vi kan mærke os selv. Når vi kan grine, græde, blive frustrerede, forundrede, begejstrede og bekymrede. Vi rummer det hele, og vi skal kunne trives i det hele. Det kan i perioder kræve en indsats at bevare en sund balance i livet og stå stærkt. 
Min mission er at hjælpe dig med det, når du har brug for det. Gennem træning, samtale, mentale øvelser og kropslig leg. Alt afhængig af, hvad dit behov er og hvordan vi bedst muligt motiverer netop dig.</p>
          <h2>Lyder jeg som en lalleglad hippie?</h2>
          <p>Tag ikke fejl. Jeg er uddannet fysioterapeut og har en forkærlighed for funktionel neurologi. Jeg har specialiseret mig i den menneskelige hjerne, vores nervesystem og i hvordan vi interagerer med verden gennem vores sanseapparat. Det er hverken gætteri eller kætteri. Det er nyeste viden og velafprøvede værktøjer. Jeg præsenterer det bare på en måde, så du ikke mister interessen.</p>
        </div>
      </div>
    </div>
  </div>

    <div class="mb-16">&nbsp;</div>
  </div>

  
 
</template>