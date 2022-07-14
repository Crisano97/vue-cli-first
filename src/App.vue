<template>
  <div id="app">
    <FirstTitle />
    <FirstHero />
  </div>
</template>

<script>
import FirstHero from './components/FirstHero.vue'
import FirstTitle from './components/FirstTitle.vue'

export default {
  name: 'App',
  components: {
    FirstTitle,
    FirstHero
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
  margin: -8px;
  padding: 0;
  box-sizing: border-box;
  margin-top: 50px;
  
}
</style>
