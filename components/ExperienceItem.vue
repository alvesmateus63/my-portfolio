<template>
  <div class="my-4 text-textSeconday border-l-2 border-l-secondary pl-2">
    <p class="font-bold">{{ company }}</p>
    <p>{{ dateStart }} - {{ dateEnd }}</p>
    <p class="font-medium">Tecnologias: <span class="font-light" v-for="item in tech" key="item">{{ item }}</span></p>
  </div>
</template>

<script>
  export default {
    props: {
      company: {
        type: String,
        required: true
      },
      dateStart: {
        type: String,
        required: true
      },
      dateEnd: {
        type: String,
        required: true
      },
      tech: {
        type: Array,
        required: true
      }
    }
  }
</script>
