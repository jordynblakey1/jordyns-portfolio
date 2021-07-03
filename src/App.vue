<template>
  <div id="app">
    <NavBar/>
    <Lander/>
  </div>
</template>

<script>
import Lander from './components/Lander.vue'
import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    Lander, 
    NavBar
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
body,html {
background-color: #DADED4;
}

</style>
