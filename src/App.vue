<template>
<div class="container-app">
    <div class="content">
    <img
      alt="Vue logo"
      src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/768px-Vue.js_Logo_2.svg.png"
      width="200"
    >
</div>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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

.content {
  margin-top: 75px;
}

.container-app {
  margin: 5px 15px;
}
</style>
