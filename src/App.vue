<template>
  <div id="app">
    <img class="logo" alt="github-log" src="./assets/logo.png"/>
    <search-bar/>
  </div>
</template>

<script>
import SearchBar from '@/components/SearchBar'

export default {
  name: 'Github Search',
  components: {
    SearchBar
  },
}
</script>

<style>
body {
  margin: 0;
  padding: 0;

  background-color: #010409;
}

#app {
  display: flex;

  height: 100vh;

  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.logo {
  width: 150px;
}
</style>
