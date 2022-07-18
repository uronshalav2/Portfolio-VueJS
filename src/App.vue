<template>
  <Navbar/>
  <Landing/>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Landing from './components/Landing.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Landing
  }
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
