<template>
  <header>
    <a id="skip-nav" class="screenreader-text" href="#content">Skip Navigation</a>
    <div class="brand">Lindsey Lauria</div>
    <nav aria-label="Main navigation">
      <ul class="nav-links">
        <li>
          <a
            href="#about"
            @click.prevent="handlePageChange('About')"
            :class="{ active: currentPage === 'About' }"
          >About Me</a>
        </li>
        <li>
          <a
            href="#resume"
            @click.prevent="handlePageChange('Resume')"
            :class="{ active: currentPage === 'Resume' }"
          >Resume</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script setup lang="ts">
defineProps<{ currentPage: string }>();
const emit = defineEmits<{ "update-page": [page: string] }>();

function handlePageChange(page: string) {
  emit("update-page", page);
}
</script>

<style scoped>
</style>
