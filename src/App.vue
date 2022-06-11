<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <alexComponent name="Alex" customMessage="I am text entered in a prop!" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import alexComponent from "@/components/alex-component";

export default {
  name: 'App',
  components: {
    HelloWorld,
    alexComponent
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
