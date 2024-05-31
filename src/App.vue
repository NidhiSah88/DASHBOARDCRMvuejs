<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <crmDashboard/>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import crmDashboard from './components/crmDashboard';


export default {
  name: 'App',
  components: {
    // HelloWorld,
    crmDashboard
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
