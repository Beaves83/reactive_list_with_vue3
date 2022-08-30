<template>
  <div id="app">
    <input />
    <button>Añadir</button>
    <List elements="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import List from './components/List.vue';

export default {
  name: 'App',
  components: {
    List,
  },
};
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;

  .lista_elementos {
    background-color: red;
  }
}
</style>
