<template>
  <section class="w-full mb-4">
    <TitleH3 :title="'Idiomas:'" />
    <p class="text-textSeconday" v-for="lang in langs">{{ lang }}</p>
  </section>
</template>

<script>
  export default {
    props: {
      langs: {
        type: Array,
        required: true
      }
    }
  }
</script>
