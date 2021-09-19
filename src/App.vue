<template>
  <div id="app">
    <h1>La mia prima app con Vue CLI!</h1>
    <img src="./assets/img_deadpool.jpg" alt="img deadpool">
    <VueCLIFirst />
  </div>
</template>

<script>
import VueCLIFirst from './components/VueCLIFirst.vue'

export default {
  name: 'App',
  components: {
    VueCLIFirst
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
