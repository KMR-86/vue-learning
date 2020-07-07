
<template>
  <div id="app">
    <navbar />
    <meme/>
  </div>
</template>

<script>
//import navbar from "../components/navbar.vue";
//import navbar2 from '../components/navbar-2.vue'
import meme from "../components/meme.vue";

export default {
  name: "Home",
  components: {
    
    meme
  }
};
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

