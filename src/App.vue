<template>
  <div id="app">
    <MenuBar company_name = "Menu bar component"/>
  </div>
</template>

<script>

// adding my componenets for app
import MenuBar from './components/MenuBar.vue'
export default {
  name: 'app',
  components: {
    MenuBar
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
  margin-top: 60px;
}
</style>
