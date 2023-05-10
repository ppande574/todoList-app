<template>
  <h1 id="appTitle">To-Do Tracker</h1>
  <img id="mainLogo" alt="Todo App Logo" src="./assets/todo-app-logo.png">
  <TaskItem msg="Welcome to your todo-list"/>
</template>

<script>
import TaskItem from './components/TaskItem.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    TaskItem
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
  /* display: flex; 
  justify-content: center;
  height: 100vh;  */
}

#appTitle {
  text-align: center;
}

#mainLogo {
  position: center; 
  width: 25%; 
  height: auto; 
}

</style>
