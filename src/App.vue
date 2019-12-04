<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png">-->
    <!--<HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <CRegister msg="Welcome to Mitrais"/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import CRegister from './components/C_Register'

export default {
  name: 'app',
  components: {
    // HelloWorld
    CRegister
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;

@import'~bootstrap/dist/css/bootstrap.css'
}
</style>
