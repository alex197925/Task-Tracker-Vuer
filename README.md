<!-- @format -->

### Vue-Course-2022

## Use Vue CLI

# Getting Started

Install:

```
npm install -g @vue/cli
# OR
yarn global add @vue/cli
```

Create a project:

```
vue create my-project
# OR
vue ui
```

### ⚠️ Vue CLI is in Maintenance Mode!

For new projects, it is now recommended to use create-vue to scaffold Vite-based projects. Also refer to the Vue 3 Tooling Guide for the latest recommendations.

---

# Overview

Vue CLI is a full system for rapid Vue.js development, providing:

- Interactive project scaffolding via @vue/cli.
- A runtime dependency (@vue/cli-service) that is:

* Upgradeable;
* Built on top of webpack, with sensible defaults;
* Configurable via in-project config file;
* Extensible via plugins

- A rich collection of official plugins integrating the best tools in the frontend ecosystem.
- A full graphical user interface to create and manage Vue.js projects.
  Vue CLI aims to be the standard tooling baseline for the Vue ecosystem. It ensures the various build tools work smoothly together with sensible defaults so you can focus on writing your app instead of spending days wrangling with configurations. At the same time, it still offers the flexibility to tweak the config of each tool without the need for ejecting.

[Link for CLI Vue](https://cli.vuejs.org/)

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
