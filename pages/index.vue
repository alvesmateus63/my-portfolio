<template>
  <div class="bg-primary py-16 px-2.5 grid-cols-1 sm:w-full sm:h-full md:w-screen md:h-screen">
    <!--Header-->
    <Header />
    <!--About-->
    <About />
    <!--Experience-->
    <Experience />
    <!--Languages-->
    <Languages :langs="['🇧🇷 Português - Nativo', '🇺🇲 Inglês - Avançado']" />
    <!--Education-->
    <Education />
    <!--Social Media + Contact-->
    <SocialMedia />
    <!--Knowledge-->
<!--    <div>-->
<!--      <h3>Conhecimento</h3>-->
<!--      <p>React</p>-->
<!--      <p>Vue</p>-->
<!--      <p>Javascript</p>-->
<!--      <p>Typescript</p>-->
<!--      <p>Laravel</p>-->
<!--      <p>Symfony</p>-->
<!--    </div>-->
  </div>
</template>
<script setup lang="ts">
import Experience from "~/components/Experience.vue";
import SocialMedia from "~/components/SocialMedia.vue";
</script>