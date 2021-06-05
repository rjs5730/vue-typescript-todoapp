<template>
  <header>
    <h1>{{ headerText }}</h1>
  </header>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  data() {
    return {
      headerText: "Vue-Typescript-TodoApp",
    };
  },
});
</script>

<style scoped></style>
