<script setup>
import MenuBar from './components/MenuBar.vue'
import InformationBar from './components/InformationBar.vue'
import FullCalendar from './components/FullCalendar.vue'
import LoginName from './components/LoginName.vue'

</script>

<template>

  <MenuBar />
  <main role="main" class="container">
    <LoginName username="takumi"/>
    <InformationBar />
    <FullCalendar/>
  </main>
</template>

<style>
main{
  margin-top:100px;
}
</style>
