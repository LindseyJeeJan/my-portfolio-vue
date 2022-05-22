<template>
  <div id="content" class="main container p-3">
    <section>
      <h1>Resume</h1>

      <h2 class="mt-3">Front-end Skills</h2>
      <ul>
        <li>HTML5</li>
        <li>CSS3</li>
        <li>SASS</li>
        <li>JavaScript</li>
        <li>TypeScript</li>
        <li>Vue.js</li>
        <li>React</li>
        <li>Accessibility</li>
        <li>Responsive Design</li>
      </ul>
      <h2 class="mt-3">Back-end Skills</h2>
      <ul>
        <li>APIs</li>
        <li>Node</li>
        <li>REST</li>
        <li>GraphQL</li>
        <li>NPM</li>
        <li>Express</li>
        <li>MySQL, Sequelize</li>
        <li>MongoDB, Mongoose</li>
      </ul>

      <div class="top-margin">
        <a
          href="@/assets/lindseylauria-resume.pdf"
          rel="noreferrer"
          target="_blank"
          >Download my resume &ndash; PDF</a
        >
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "PageResume",
};
</script>

<style scoped>
h2,
ul {
  margin-left: 0.5rem;
}

li {
  line-height: 1.5;
}
</style>
