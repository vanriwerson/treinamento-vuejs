<template>
  <div id="app">
    <Contador />
  </div>
</template>

<script>
import Contador from './components/Contador.vue'
/*import NovoComponente from './components/NovoComponente.vue'
import TesteIf from './components/TesteIf.vue'
import TesteFor from './components/TesteFor.vue'
import TesteEvento from './components/TesteEvento.vue'
import SitesFavoritos from './components/SitesFavoritos.vue'*/

export default {
  name: 'App',
  components: {
    Contador
    /*NovoComponente,
    TesteIf,
    TesteFor,
    TesteEvento,
    SitesFavoritos*/
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
