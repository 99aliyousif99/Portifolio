<script setup>
import FaceCard from "./components/FaceCard.vue";
import Tech from "./components/Tech.vue"
import Skills from "./components/Skills.vue"
</script>

<template>
  <div class="flex justify-center p-30 gap-30">
  <div>
    <FaceCard/>
  </div>

  <div>
  <h1 class="text-[#fdfffc] text-7xl font-bold">SOFTWARE</h1>
  <h1 class="text-gray-400 text-7xl font-bold">DEVELOPER</h1>
  <p class="text-gray-400  font-bold pt-10">I'm a full-stack developer with a passion for building responsive, user-friendly web applications. I work mainly with React, JavaScript, and Express.js</p>


  <Tech/>
  <skills/>
</div>
</div>
</template>
