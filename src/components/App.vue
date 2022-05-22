<template>
  <the-page />
</template>

<script>
import Page from "@/components/ThePage.vue";

export default {
  name: "App",
  components: {
    "the-page": Page,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
