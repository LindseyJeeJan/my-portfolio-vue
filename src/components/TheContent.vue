<template>
    <div id="content" class="container">
      <div v-if="currentPage === 'About'">
        <page-about />
      </div>
      <div v-else-if="currentPage=== 'Contact'">
        <page-contact />
      </div>
      <div v-else-if="currentPage=== 'Portfolio'">
        <page-portfolio />
        </div>
        <div v-else-if="currentPage=== 'Resume'">
        <page-resume />
        </div>
    </div>
</template>

<script>
import PageAbout from '@/components/pages/PageAbout.vue'
import PageContact from '@/components/pages/PageContact.vue'
import PagePortfolio from '@/components/pages/PagePortfolio.vue'
import PageResume from '@/components/pages/PageResume.vue'

export default {
name: 'TheContent',
  components: {
    'page-about': PageAbout,  
    'page-contact': PageContact,  
    'page-portfolio': PagePortfolio,  
    'page-resume': PageResume,  
  },
  props: {
    currentPage: String,
  },
}
</script>

<style scoped>
#content {
    flex-grow: 2;
    overflow: auto;
    padding: 1rem!important;
}
</style>