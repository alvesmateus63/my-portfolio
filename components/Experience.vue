<template>
  <section>
    <TitleH3 :title="'Minha Experiência:'" />
    <ExperienceItem :company="'Code empresa junior de computação'" :date-start="'Janeiro/2022'" :date-end="'Julho/2022'" :tech="['React, ', 'Laravel']" />
    <ExperienceItem :company="'Select Sistemas'" :date-start="'Abril/2023'" :date-end="'Atual'" :tech="['Vue, ', 'React, ', 'Symfony, ', 'Laravel']" />
  </section>
</template>
<script setup lang="ts">
</script>