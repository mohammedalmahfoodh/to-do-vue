<template>
  <div id="app">
    <NavToDo title="Welcome to Your to do" />
     <ToDos title="Welcome to Your to do" />
  </div>
</template>

<script>
import NavToDo from "./components/NavToDo.vue";
import ToDos from "./components/ToDos";
export default {
  name: "App",
  components: {
    NavToDo,
    ToDos
  },
  data() {
    return {
      todosArray: [
        {
          id: 1,
          title: "Todo One",
          completed: false,
        },
        {
          id: 2,
          title: "Todo Two",
          completed: true,
        },
        {
          id: 3,
          title: "Todo Three",
          completed: false,
        },
      ],
    };
  },
};
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
