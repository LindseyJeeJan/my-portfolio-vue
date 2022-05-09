<template>
    <page-about />
    <page-contact />
    <page-portfolio />
    <page-resume />
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
}
</script>

<style>

</style>