<template>
  <img alt="Emoji de joia" src="./assets/joinha.png">
  <HelloWorld msg="Hello 🌎!"/>
  <h1></h1>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  
}
</script>

<style>
#app {
  font-family: 'Lobster', cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #023d79;
  margin-top: 60px;
  font-size: 350%;
  
}
</style>
