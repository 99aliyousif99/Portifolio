<script setup>
import FaceCard from "./components/FaceCard.vue";
import Tech from "./components/Tech.vue"
import Skills from "./components/Skills.vue"
import Projects from "./components/Projects.vue";
import Work from "./components/Work.vue";
import Contact from "./components/Contact.vue";

</script>

<template>
  <div class="flex flex-col lg:flex-row justify-center p-4 sm:p-8 lg:p-30 gap-4 sm:gap-8 lg:gap-30 min-h-screen">
    <div class="w-full lg:w-auto flex justify-center lg:block">
      <FaceCard/>
    </div>

    <div class="w-full lg:flex-1 max-w-4xl">
      <h1 class="text-[#fdfffc] text-4xl sm:text-5xl md:text-6xl lg:text-7xl font-bold text-center lg:text-left">SOFTWARE</h1>
      <h1 class="text-gray-400 text-4xl sm:text-5xl md:text-6xl lg:text-7xl font-bold text-center lg:text-left">DEVELOPER</h1>
      <p class="text-gray-400 font-bold pt-4 sm:pt-6 lg:pt-10 text-sm sm:text-base lg:text-lg text-center lg:text-left px-4 lg:px-0">I'm a full-stack developer with a passion for building responsive, user-friendly web applications. I work mainly with React, JavaScript, and Express.js</p>

      <Tech/>
      <Skills/>
      <Projects/>
      <Work/>
      <Contact/>
    </div>
  </div>
</template>