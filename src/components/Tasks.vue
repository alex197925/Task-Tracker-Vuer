<!-- @format -->

<!-- What I want to do here is, take prop of tasks, take an array and loop them and output single task component for each one. -->

<template>
  <!-- Looping through tasks and displaying them -->
  <div v-for="task in tasks" :key="task.id">
    <Task :task="task" />
  </div>
</template>

<script>
import Task from "./Task";

export default {
  name: "Tasks",
  props: {
    tasks: Array,
  },
  components: {
    Task,
  },
};
</script>
