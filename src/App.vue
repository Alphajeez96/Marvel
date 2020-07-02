<template>
  <div id="app">
    <div id="nav">
 <navbar> </navbar>
//  <nav2> </nav2>
    </div>
    <router-view/>
       
  </div>
</template>

<script>
import navbar from '@/components/partials/navbar'
// import nav2 from '@/components/partials/nav2'


export default {
  name: 'Home',
  components: {
  navbar
  // nav2
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

}



#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
