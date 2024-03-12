<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <IndexF/>
</template>

<script>
import IndexF from "../src/components/IndexF.vue"
export default {
  name: 'App',
  components: {
    IndexF
  }
}
</script>

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
