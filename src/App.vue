<template>
  <div id="app" class="container">
    <ToDoList />
  </div>  
</template>

<script>
import ToDoList from "./components/ToDoList.vue"
export default {
  name: 'app',
  components: {
    ToDoList
  },
  data() {
    return {
      
    }
  },

}
</script>

<style>
  * {
    box-sizing: border-box;
  }

  .container {
    max-width: 600px;
    margin: 0 auto;
  }
  #app {
    font-family: 'Avenir', Arial, Helvetica, sans-serif;
    -webkit-font-smoothing: antialiased;
    color: #2c3e50;
    margin-top: 60px;
    font-size: 24px;
  }
</style>
