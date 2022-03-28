<template>
    <div class="relative bg-bevagelse-blue-light mb-12">
      <div class="max-w-7xl mx-auto py-8 px-4 sm:px-6">
        <h3 class="mt-2 text-4xl mx-auto leading-8 font-poppins font-extrabold tracking-tight text-white uppercase lg:text-8xl"><slot name="headline"></slot></h3>
        <p class="relative w-1/1 text-xl lg:w-1/2 text-white font-light pt-6 px-4 sm:px-6 lg:px-16">
            <slot name="teaser"></slot>
        </p>
        
      </div>
    </div>

</template>