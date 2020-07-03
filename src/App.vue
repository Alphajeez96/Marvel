<template>
  <div id="app">
    <div id="nav">
      <navbar></navbar>
     
  
    </div>
    <router-view />
  </div>
</template>

<script>
import navbar from '@/components/partials/navbar'
// import nav2 from '@/components/partials/nav2'

export default {
  name: 'Home',
  components: {
    navbar,
    // nav2
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
html,
body {
  height: 100%;
  margin: 0;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
