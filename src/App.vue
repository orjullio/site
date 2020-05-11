<template>
  <div id="app">
    <barra-nav></barra-nav>
    
  </div>
</template>

<script>
import Nav from './components/nav/Nav.vue';

export default {
  name: 'App',
  components: {
    'barra-nav': Nav
  },
  data: function(){
    return{
      title:"Rodrigo" 
    }
  }
  
}
</script>

<style>
#app {
  
  
}
</style>
