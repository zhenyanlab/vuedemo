<template>


  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="sam"/>
  <EEAdmin />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import EEAdmin from './components/EEAdmin.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    EEAdmin
  }
}
console.log(HelloWorld);
console.log(EEAdmin);

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
