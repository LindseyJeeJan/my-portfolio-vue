<template>
  <the-nav />
  <the-content />
  <the-footer />
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
}
</script>

<style scoped>
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
