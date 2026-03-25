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
  min-height: 100vh;
}
</style>
