<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <RegistroAfiliados msg="Estas en registro"/>
  <HelloWorld msg2="Estas en hello"/>
   <div class="row">
    <div class="input-field col s6">
      <input value="Alvin" id="first_name2" type="text" class="validate">
      <label class="active" for="first_name2">First Name</label>
    </div>
  </div>
</template>

<script>

import HelloWorld from './components/HelloWorld.vue'
import RegistroAfiliados from './components/RegistroAfiliados.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    RegistroAfiliados
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
