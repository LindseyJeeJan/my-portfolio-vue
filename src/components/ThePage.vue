<template>
  <main class="wrapper">
    <the-nav :currentPage="currentPage" @update-page="updatePage" />
    <the-content :currentPage="currentPage" />
    <the-footer />
  </main>
</template>

<script setup lang="ts">
import { ref } from "vue";
import TheNav from "@/components/TheNav.vue";
import TheContent from "@/components/TheContent.vue";
import TheFooter from "@/components/TheFooter.vue";

const currentPage = ref<string>("About");

function updatePage(page: string) {
  currentPage.value = page;
}
</script>

<style scoped>
.wrapper {
  display: flex;
  flex-direction: column;
  justify-content: stretch;
  position: fixed;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
}

h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
