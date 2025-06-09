<script setup>
import { AnFilledFacebook } from "@kalimahapps/vue-icons";
import { AkLinkedinBoxFill } from '@kalimahapps/vue-icons';
import { BxInstagramAlt } from '@kalimahapps/vue-icons';
import { FaBandsSquareXTwitter } from '@kalimahapps/vue-icons';
</script>

<template>
  <div
    class="bg-white w-70 h-85 rounded-md flex flex-col items-center justify-center gap-6 sticky top-30"
  >
    <div>
      <img src="" alt="" class="w-35 h-35 bg-greyrounded-md" />
    </div>

    <p class="text-xs font-bold text-center w-50">
      software developer from Iraq passionate about building software that help
      people around the world
    </p>
    <div class=" flex felx-row gap-1 items-center justify-center">
    <AnFilledFacebook class="w-8 h-8" />
    <AkLinkedinBoxFill class="w-8 h-8"/>
    <BxInstagramAlt class="w-10 h-10"/>
    <FaBandsSquareXTwitter class="w-8 h-8"/>
</div>
  </div>
 
</template>
