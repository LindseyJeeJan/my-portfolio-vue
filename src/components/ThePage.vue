<template>
<main class="wrapper">
  <the-nav :currentPage="currentPage" @update-page="updatePage" />
  <the-content :currentPage="currentPage" />
  <the-footer />
  </main>
</template>

<script>
import Nav from '@/components/TheNav.vue'
import Content from '@/components/TheContent.vue'
import Footer from '@/components/TheFooter.vue'

export default {
  name: 'ThePage',
  components: {
    'the-footer': Footer,
    'the-content': Content,
    'the-nav': Nav,   
  },
  data() {
      return {
        currentPage: 'About'
      }
   },
  methods: {
    updatePage(page){
       this.$data.currentPage = page;
    },
}
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
