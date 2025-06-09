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
  <div class="mt-20">
    <h1 class="text-[#ff0022] text-7xl font-bold mb-10">TOOLS</h1>
    <div class="grid grid-cols-3 gap-4">
      <div class="flex flex-row w-35 h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DeFigmaOriginal class="w-8 h-8" />
        <p class="text-2xl font-bold text-white">FIGMA</p>
      </div>
      
      <div class="flex flex-row w-35 h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DeReactOriginal class="w-8 h-8" />
        <p class="text-2xl font-bold text-white">REACT</p>
      </div>
      
      <div class="flex flex-row w-35 h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DeJavascriptOriginal class="w-8 h-8" />
        <p class="text-2xl font-bold text-white">JS</p>
      </div>
      
      <div class="flex flex-row w-35 h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DeHtml5Original class="w-8 h-8" />
        <p class="text-2xl font-bold text-white">HTML</p>
      </div>
      
      <div class="flex flex-row w-35 h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DeCss3Original class="w-8 h-8" />
        <p class="text-2xl font-bold text-white">CSS</p>
      </div>
      
      <div class="flex flex-row w-35 h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <FaBandsPhp class="w-8 h-8 text-white" />
        <p class="text-2xl font-bold text-white">php</p>
      </div>
      
      <div class="flex flex-row w-35 h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DePostgresqlPlainWordmark class="w-8 h-8" />
        <p class="text-2xl font-bold text-white">PGADMIN </p>
      </div>
      
      <div class="flex flex-row w-35 h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DeVuejsOriginal class="w-8 h-8" />
        <p class="text-2xl font-bold text-white">VUE</p>
      </div>
      
      <div class="flex flex-row w-35 h-14 items-center justify-between rounded-md hover:bg-[#08263d] transition-colors duration-300 cursor-pointer">
        <DeLaravelOriginal class="w-8 h-8"/>
        <p class="text-2xl font-bold text-white">LARAVEL</p>
      </div>
    </div>
  </div>
</template>