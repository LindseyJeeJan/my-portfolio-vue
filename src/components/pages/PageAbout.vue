<template>
      <div id="content" class="main container p-3">
        <section>
          <h1>About Me</h1>
          <article class="about-content">
           
            <div class="article-content">
              <div>
                <h2 class="w-100">Front End Designer &amp; Developer</h2>
                <p>Hi, I'm Lindsey. I am a Web Developer and a UI Designer. Designing user interfaces and building clean, accessible front end solutions is something I love to do. I enjoy creative activities, problem solving and learning new things.</p>
              </div>
              <img class="image-self" src="@/assets/images/lindsey-resized.png" alt="lindsey lauria headshot" />
            </div>
          </article>
      </section>
    </div>
</template>

<script>
export default {
     name: 'PageAbout',
}
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
</style>>
