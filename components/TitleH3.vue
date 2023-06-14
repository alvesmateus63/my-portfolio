<template>
  <h3 class="text-textPrimary text-lg tex-bold my-4">{{ title }}</h3>
</template>

<script>
  export default {
    props: {
      title: {
        type: String,
        required: true
      }
    }
  }
</script>
