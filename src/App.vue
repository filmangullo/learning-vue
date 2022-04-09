<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <LogoComponent />
</template>

<script>
import LogoComponent from './components/LogoComponent.vue';

export default {
  name: 'App',
  components: {
    LogoComponent
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
