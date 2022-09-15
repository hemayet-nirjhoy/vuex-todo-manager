<template>
  <div style="text-align:center">
    <h2>Todo Manager Application</h2>
  </div>
  <div class="container">
    <TodoItems />
  </div>
</template>

<script>
import TodoItems from './components/Todos.vue'

export default {
  name: 'App',
  components: {
    TodoItems,
}
}
</script>

<style>
body{
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}
.container{
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
