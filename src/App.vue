<template>
  <div class="container">
    <TodosItem />
  </div>
</template>

<script>
import TodosItem from "./components/TodosItem.vue";

export default {
  name: "App",
  components: {
    TodosItem,
  },
};
</script>

<style>
body {
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}
.container {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
