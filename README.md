<!-- @format -->

### Vue-Course-2022

## Use Vue CLI

- Create first component

```
<template>
  <header>
    <h1>Task Tracker</h1>
  </header>
</template>

<script lang="ts">
export default {
  name: "Header",
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
```
