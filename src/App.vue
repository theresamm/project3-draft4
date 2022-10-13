<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
   <div>
   <div class="container-fluid">
     <ul class="nav nav-tabs">
       <li class="nav-item">
         <button class="nav-link active" aria-current="page">Recipes</button>
       </li>
       <li class="nav-item">
         <button class="nav-link">Add New</button>
       </li>
     </ul>
   </div>
 </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
