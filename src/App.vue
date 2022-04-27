<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <SearchModule />
</template>

<script>
import SearchModule from './components/SearchModule.vue'

export default {
  name: 'App',
  components: {
    SearchModule
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
