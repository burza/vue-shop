<script>
  export default {
    props: {
      msg: String,
    },
    data() {
      return {
        msg: 'LogRocket'
      };
    },
  }
</script>

<template>
  <h1>{{ msg }}</h1>
</template>

<style scoped>
</style>
