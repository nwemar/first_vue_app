<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <HelloWorld msg="Hello Wrold"/>
    <first msg="My first component project" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import first from './components/first.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    first
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
