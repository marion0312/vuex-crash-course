<template>
  <div id="app">
    <div class="container">
      <AddTodos />
      <Todos />
    </div>
  </div>
</template>

<script>
import Todos from './components/Todos';
import AddTodos from './components/AddTodos';

export default {
  name: 'App',
  components: {
    Todos,
    AddTodos
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}

.container {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
