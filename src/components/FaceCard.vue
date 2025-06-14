<script setup>
import { AnFilledFacebook } from "@kalimahapps/vue-icons";
import { AkLinkedinBoxFill } from "@kalimahapps/vue-icons";
import { BxInstagramAlt } from "@kalimahapps/vue-icons";
import { FaBandsSquareXTwitter } from "@kalimahapps/vue-icons";
import { TiSocialInstagram } from '@kalimahapps/vue-icons';
</script>

<template>
  <div
    class="bg-white w-full max-w-xs sm:max-w-sm md:w-80 h-auto md:h-95 p-4 md:p-6 rounded-md flex flex-col items-center justify-center gap-4 md:gap-6 sticky top-4 md:top-30 mx-auto"
  >
    <div>
      <img src="" alt="Profile" class="w-28 h-28 sm:w-28 sm:h-28 md:w-45 md:h-45 bg-gray-200 rounded-md" />
    </div>
    <div class="flex flex-col items-center justify-center gap-2 md:gap-3">
      <h1 class="text-black text-lg sm:text-xl md:text-2xl font-semibold">My name is Ali</h1>
      <p class="text-xs sm:text-sm md:text-normal text-black font-bold text-center w-full max-w-xs sm:max-w-sm md:w-50 px-2">
        software developer from Iraq passionate about building software that
        help people around the world
      </p>
      <div class="flex flex-row gap-2 md:gap-1 items-center justify-center mb-15 ">
        <AnFilledFacebook class="w-7 h-7 sm:w-8 sm:h-8 md:w-9 md:h-9 text-black hover:text-blue-600 transition-colors cursor-pointer" />
        <AkLinkedinBoxFill class="w-6 h-6 sm:w-7 sm:h-7 md:w-8 md:h-8 text-black hover:text-blue-700 transition-colors cursor-pointer" />
        <FaBandsSquareXTwitter class="w-6 h-6 sm:w-7 sm:h-7 md:w-8 md:h-8 text-black hover:text-gray-600 transition-colors cursor-pointer" />
        <TiSocialInstagram class="w-7 h-7 sm:w-8 sm:h-8 md:w-9 md:h-9 text-black hover:text-pink-600 transition-colors cursor-pointer" />
      </div>
    </div>
  </div>
</template>