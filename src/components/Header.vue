<!-- @format -->

<template>
  <header>
    <!-- Pass props  -->
    <h1>{{ title }}</h1>
    <Button text="Add Task" color="green" />
  </header>
</template>

<script lang="ts">
// Importing Button
import Button from "./Button.vue";

export default {
  name: "Header",

  //   Defining props
  props: {
    title: String,
  },
  //   Register components
  components: {
    Button,
  },
};
</script>

<!-- Scoped - style only for this componenet -->
<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>
