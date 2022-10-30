<script setup>
import HelloWorld from './components/HelloWorld.vue'
import MenuBar from './components/MenuBar.vue'
import InformationBar from './components/InformationBar.vue'
</script>

<template>
  <MenuBar/>
  <InformationBar/>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="shiftmanagementapp"/>
  <button class="btn btn-primary">bootstrap-btn</button>

</template>

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
