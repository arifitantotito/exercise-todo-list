<template>
  
  <HelloWorld msg="What You Want To Do?"/>
</template>

<script>
import HelloWorld from './components/to-do-list.vue'

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
  color: #2c3e50;
  margin-top: 60px;
}
body{
  width: 100%;
  height: 100vh;
  padding: 10px;
  background: linear-gradient(#3dcdf1 0%, #5ee6eb 25%, #49e8b3 50%, #49f06d 100%);
}
</style>
