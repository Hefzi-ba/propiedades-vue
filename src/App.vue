<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <MiPrimerComponente></MiPrimerComponente>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

import MiPrimerComponente from './components/MiPrimerComponente.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    
    MiPrimerComponente
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
