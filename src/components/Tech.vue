<script setup>
import { DeFigmaOriginal } from "@kalimahapps/vue-icons";
import { DeLaravelOriginal } from '@kalimahapps/vue-icons';
import { DeJavascriptOriginal } from '@kalimahapps/vue-icons';
import { DeReactOriginal } from '@kalimahapps/vue-icons';
import { DeHtml5Original } from '@kalimahapps/vue-icons';
import { DeCss3Original } from '@kalimahapps/vue-icons';
import { FaBandsPhp } from '@kalimahapps/vue-icons';
import { DePostgresqlPlainWordmark } from '@kalimahapps/vue-icons';
import { DeVuejsOriginal } from '@kalimahapps/vue-icons';
</script>

<template>
  <div class="mt-10 sm:mt-15 lg:mt-20 px-4 lg:px-0">
    <h1 class="text-[#ff0022] text-3xl sm:text-4xl md:text-5xl lg:text-6xl font-bold mb-6 lg:mb-10 text-center lg:text-left">TOOLS</h1>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-4">
      <div class="px-2 sm:px-0.5 flex flex-row w-full sm:w-35 h-12 sm:h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DeFigmaOriginal class="w-6 h-6 sm:w-8 sm:h-8" />
        <p class="text-lg sm:text-2xl font-bold text-white">FIGMA</p>
      </div>
      
      <div class="px-2 sm:px-0.5 flex flex-row w-full sm:w-35 h-12 sm:h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DeReactOriginal class="w-6 h-6 sm:w-8 sm:h-8" />
        <p class="text-lg sm:text-2xl font-bold text-white">REACT</p>
      </div>
      
      <div class="px-2 sm:px-0.5 flex flex-row w-full sm:w-35 h-12 sm:h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DeJavascriptOriginal class="w-6 h-6 sm:w-8 sm:h-8" />
        <p class="text-lg sm:text-2xl font-bold text-white">JS</p>
      </div>
      
      <div class="px-2 sm:px-0.5 flex flex-row w-full sm:w-35 h-12 sm:h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DeHtml5Original class="w-6 h-6 sm:w-8 sm:h-8" />
        <p class="text-lg sm:text-2xl font-bold text-white">HTML</p>
      </div>
      
      <div class="px-2 sm:px-0.5 flex flex-row w-full sm:w-35 h-12 sm:h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DeCss3Original class="w-6 h-6 sm:w-8 sm:h-8" />
        <p class="text-lg sm:text-2xl font-bold text-white">CSS</p>
      </div>
      
      <div class="px-2 sm:px-0.5 flex flex-row w-full sm:w-35 h-12 sm:h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <FaBandsPhp class="w-6 h-6 sm:w-8 sm:h-8 text-white" />
        <p class="text-lg sm:text-2xl font-bold text-white">PHP</p>
      </div>
      
      <div class="px-2 sm:px-0.5 flex flex-row w-full sm:w-35 h-12 sm:h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DePostgresqlPlainWordmark class="w-6 h-6 sm:w-8 sm:h-8" />
        <p class="text-sm sm:text-2xl font-bold text-white">PGADMIN</p>
      </div>
      
      <div class="px-2 sm:px-0.5 flex flex-row w-full sm:w-35 h-12 sm:h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DeVuejsOriginal class="w-6 h-6 sm:w-8 sm:h-8" />
        <p class="text-lg sm:text-2xl font-bold text-white">VUE</p>
      </div>
      
      <div class="px-2 sm:px-0.5 flex flex-row w-full sm:w-35 h-12 sm:h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DeLaravelOriginal class="w-6 h-6 sm:w-8 sm:h-8"/>
        <p class="text-lg sm:text-2xl font-bold text-white">LARAVEL</p>
      </div>
    </div>
  </div>
</template>