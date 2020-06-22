
<template>
  <div id="app">
    <navbar/>
  </div>
</template>

<script>

import navbar from './components/navbar.vue'
//import navbar2 from './components/navbar-2.vue'
export default {
  name: 'App',
  components: {
    navbar
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
  margin-top: 0;
}



</style>

