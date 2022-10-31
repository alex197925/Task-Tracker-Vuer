<!-- @format -->

<template>
  <!-- Add style to button by passing props -->
  <!-- Add eventlistener onClick() method -->
  <button @click="onClick()" :style="{ background: color }" class="btn">
    {{ text }}
  </button>
</template>

<script lang="ts">
export default {
  name: "Button",
  props: {
    text: String,
    color: String,
  },
  //   Defind Methods here
  methods: {
    onClick() {
      console.log("Yes Working");
    },
  },
};
</script>
