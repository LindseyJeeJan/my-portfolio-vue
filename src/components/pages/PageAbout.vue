<template>
  <div id="content" class="main container p-3">
    <section>
      <h1>About Me</h1>
      <article class="about-content">
        <div class="article-content">
          <div>
            <h2 class="w-100">Software Developer &amp; Designer</h2>
            <p>
              Hi, I'm Lindsey. I am a developer with a strong background in
              both design and development of responsive and accessible user
              interfaces for web applications. My goal is always to provide the
              best experience to the largest possible number of users.
            </p>
            <p>
              I enjoy creating accessible interfaces that are inclusively
              designed to provide an equal experience for all users. I have been
              developing with accessibility in mind for over a decade and I
              enjoy learning as much as possible about supporting various
              assistive technologies. I consider myself both a designer and
              engineer.
            </p>
          </div>
          <img
            class="image-self"
            src="@/assets/images/lindsey-resized.png"
            alt="lindsey lauria headshot"
          />
        </div>
      </article>
    </section>
  </div>
</template>

<script>
export default {
  name: "PageAbout",
};
</script>

<style scoped>
.about-content img {
  margin: 0 0 30px 30px;
  width: 30%;
  height: 50%;
  border-radius: 2px;
  box-shadow: 0 10px 12px 2px rgb(51 102 102 / 50%);
}

.image-self {
  height: 100%;
}
</style>
