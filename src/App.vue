<script setup>
  // This starter template is using Vue 3 <script setup> SFCs
  // Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
  import Headline from './components/Headline.vue'
  import BuyButton from './components/BuyButton.vue'

</script>

<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Headline msg="headline" />
  <BuyButton/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
