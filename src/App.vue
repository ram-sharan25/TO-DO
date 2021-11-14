<template>
  <div id="app">
    <Todos v-bind:todos="todos"/>
  </div>
</template>

<script>
import Todos from "./components/Todos"

export default {
  name: 'app',
  components:{
    Todos
  },
  data(){
    return{
      todos: [
        {
          id: 1,
          title:"Go Workout",
          completed: false

        },
        {
          id:2 ,
          title:"Do Laundry",
          completed: false

        },
        {
          id: 3,
          title:"Cook Food",
          completed: false

        },
        {
          id: 4,
          title:"Clean Up Room",
          completed: false

        },
        {
          id:5 ,
          title:"Finish Work",
          completed: false

        }
      ],
    }
  },
}
</script>

<style>

</style>
