<template>
  <header>
    <h1>{{ title }}</h1>
    <button class="btn">Create Task</button>
  </header>
</template>

<script>
export default {
  name: "HeaderTask",
  props: {
    title: {
      type: String,
      default: "Hello world",
      required: false,
    },
  },
};
</script>

<style scoped>
header {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
