<template>
  <div id="app">
    <HelloWorldComponent msg="getting start with vue"/>
  </div>
</template>

<script>
import HelloWorldComponent from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorldComponent
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
