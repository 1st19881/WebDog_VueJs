<template>
   <div id="app">
    <Navbar/>
  </div>

  <router-view/>

</template>

<script>

import Navbar from './components/Navbar.vue'

export default {
name: 'App',
  components: {
    Navbar
  }
}
</script>

<style>
#app{
  margin-bottom: auto;
}
</style>