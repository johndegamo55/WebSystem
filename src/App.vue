<template>
  <WebPort msg="My Portfolio"/>
</template>

<script>
import WebPort from './components/WebPort.vue'

export default {
  name: 'App',
  components: {
    WebPort
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
}

</style>
