<template>
  <section class="md:col-start-2 md:col-end-3 md:row-start-2 md:row-end-3">
    <TitleH3 :title="'Conhecimento:'" />
    <ul class="text-textSeconday flex flex-col gap-2 list-disc ml-6">
      <li v-for="lang in langs">{{ lang }}</li>
    </ul>

  </section>
</template>

<script>
  export default {
    props: {
      langs: {
        type: Array,
        required: true,
      }
    }
  }
</script>