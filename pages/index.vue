<template>
  <div class="bg-primary  ">
    <div class="py-16 px-2.5 grid-cols-1 sm:w-full sm:h-full md:gap-6 md:px-10 md:w-screen md:h-screen md:grid md:grid-cols-2 md:grid-rows-3 xl:max-w-6xl xl:mx-auto">
      <!--Header-->
      <Header />
      <!--About-->
      <About />
      <!--Experience-->
      <Experience />

      <!--Knowledge-->
      <Knowledge :langs="['React', 'Vue', 'Typescript', 'Laravel', 'Symfony']" />

      <!--Languages + Education-->
      <div class=" md:md:self-center md:col-start-2 md:col-end-3 md:row-start-1 md:row-end-2">
        <Languages :langs="['🇧🇷 Português - Nativo', '🇺🇲 Inglês - Avançado']" />

        <Education />
      </div>
      <!--Social Media + Contact-->
      <SocialMedia />
    </div>
  </div>
</template>
<script setup lang="ts">
import Experience from "~/components/Experience.vue";
import SocialMedia from "~/components/SocialMedia.vue";
</script>