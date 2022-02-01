<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    
    <SearchBar></SearchBar>

  </div>
</template>

<script>
import SearchBar from "./components/SearchBar.vue";
export default {
  name: 'App',
  components: {
    SearchBar
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
