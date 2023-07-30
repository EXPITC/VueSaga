<template>
  <layout id="layout">
    <HeaderTask title="Task Manager" />
  </layout>
</template>

<script>
import HeaderTask from "./components/HeaderTask.vue";

export default {
  name: "App",
  components: {
    HeaderTask,
  },
};
</script>

<style>
#layout {
  max-width: 800px;
  width: 100%;
  border: 1px solid blue;
  position: absolute;
}
#app {
  font-family: fantasy;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100%;
  display: flex;
  justify-content: center;
  margin-top: 60px;
}
</style>
