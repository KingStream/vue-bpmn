<template>
  <div id="app">
    <bpmn/>
  </div>
</template>

<script>
import bpmn from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    bpmn
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
