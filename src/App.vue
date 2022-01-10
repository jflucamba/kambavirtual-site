<template>
  <div id="app">
    <div>
      <menu-principal/>
    </div>

    <div>
      <router-view path="$router.key"/>
    </div>
    
  </div>
</template>

<script>
import './css/global.css'
//import HelloWorld from './components/HelloWorld';
import menuPrincipal from '@/components/MenuSite/menuPrincipal.vue'

export default {
  name: 'App',

  components: {
    //HelloWorld,
    menuPrincipal,
  },

  data: () => ({
    //
  }),
};
</script>


<style scoped>

#app{
    display: flex;
    flex-direction: column;
}

</style>