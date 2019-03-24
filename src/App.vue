<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
import Home from './views/Home.vue';

export default {
  name: 'home',
  components: {
    'app-home': Home,
  },
};
</script>

<style>
ul, li {
  margin: 0;
  padding: 0;
  list-style: none;
}
#app {
  font-family: 'Open Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #777777;
}
</style>
