<template>
  <div>大家都會用到的功能，但還沒有要上版</div>
  <h1>Feature 1</h1>
  <h1>Feature 2</h1>
  <h2>Feature 2.2</h2>
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <h3>f3</h3>
  <div>f5</div>
  <div>f5-2</div>
  <div>f7</div>
  <div>f8</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
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
