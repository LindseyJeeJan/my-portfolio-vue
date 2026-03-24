<template>
  <div id="content" class="main container p-3">
    <section>
      <h1>Resume</h1>

      <h2 class="mt-3">Summary</h2>
      <p>
        Software Engineer with experience specializing in architecting and
        delivering complex, scalable frontend applications, with deep experience
        in user experience, technical planning, system design, and design to
        deployment implementation. I specialize in modern frameworks, component
        based architecture, and building accessible, responsive user
        experiences. I possess superior skills in collaboration, aligning
        closely with product owners, designers, backend engineers, and QA
        through excellent communication, always establishing a rapport of
        understanding and respect for responsibilities and concerns across the
        lifecycle.
      </p>

      <h2 class="mt-3">Skills</h2>
      <div class="skills-grid">
        <div>
          <h3>Core Skills</h3>
          <ul>
            <li>TypeScript</li>
            <li>React</li>
            <li>Vue.js</li>
            <li>HTML</li>
            <li>CSS / SCSS</li>
          </ul>
        </div>
        <div>
          <h3>Frontend Architecture</h3>
          <ul>
            <li>Web Components</li>
            <li>REST APIs</li>
            <li>Server-Sent Events (SSE)</li>
          </ul>
        </div>
        <div>
          <h3>State Management</h3>
          <ul>
            <li>Zustand</li>
            <li>Pinia</li>
          </ul>
        </div>
        <div>
          <h3>Testing</h3>
          <ul>
            <li>Vitest</li>
            <li>React Testing Library</li>
            <li>Cypress</li>
          </ul>
        </div>
        <div>
          <h3>Tooling</h3>
          <ul>
            <li>Vite</li>
            <li>Webpack</li>
            <li>Node.js</li>
            <li>Yarn</li>
          </ul>
        </div>
        <div>
          <h3>Accessibility</h3>
          <ul>
            <li>WCAG</li>
            <li>ARIA</li>
            <li>Screen Readers</li>
            <li>Keyboard Navigation</li>
          </ul>
        </div>
        <div>
          <h3>AI</h3>
          <ul>
            <li>Claude Code</li>
            <li>GitHub Copilot</li>
          </ul>
        </div>
      </div>

      <h2 class="mt-3">Experience</h2>

      <h3>Senior Software Engineer</h3>
      <ul>
        <li>Architected and delivered two large-scale SPA platforms (React, Vue.js), defining frontend architecture, state management (Zustand, Pinia), and scalable integration patterns with Go backend and PostgreSQL, enabling reliable delivery of critical business workflows.</li>
        <li>Led frontend development of an LLM-powered chatbot platform, implementing real-time streaming via Server-Sent Events (SSE) to support agentic workflows.</li>
        <li>Leveraged extensive UX experience to work with designers to ensure Figma designs are achievable, responsive and accessible.</li>
        <li>Played a key role in sprint planning and roadmap execution, partnering closely with product, backend, and design to ensure shared alignment, reduce delivery risk, and maintain predictable development velocity.</li>
        <li>Translated complex product and technical requirements into clear, actionable implementation plans, decomposing large initiatives and complex data flows into well-scoped tasks that enabled efficient execution across engineers of varying experience levels.</li>
        <li>Improved team productivity and delivery confidence by identifying technical risks early, proposing scalable solutions, and driving implementation strategies that balanced immediate business needs with long-term architectural health.</li>
        <li>Mentored and supported engineers through technical guidance, code reviews, and knowledge sharing, helping elevate overall code quality, consistency, and team effectiveness.</li>
      </ul>

      <h3>Senior Interaction Designer / Developer</h3>
      <ul>
        <li>Developed reusable components and responsive layouts with vanilla HTML, CSS, and JavaScript, maintaining a shared CSS library for consistency over Java backend with Postgres db.</li>
        <li>Built interactive rapid prototypes to validate product requirements and technical feasibility. Designed wireframes and prototypes in Sketch, driving product and technical strategy.</li>
        <li>Often acted as liaison between product managers and design teams to translate requirements into scalable frontend solutions.</li>
        <li>Established accessibility standards, translating WCAG guidelines into actionable engineering tasks.</li>
      </ul>

      <h3>Web Developer</h3>
      <ul>
        <li>Converted design assets from Photoshop/InDesign into interactive web experiences with HTML, CSS, and JavaScript.</li>
        <li>Created dynamic UI components and media-rich interfaces using Adobe Flash and ActionScript.</li>
        <li>Managed timelines and cross-functional collaboration with strong organizational skills.</li>
      </ul>

      <h2 class="mt-3">Education &amp; Certifications</h2>

      <h3>UCI Division of Continuing Education</h3>
      <p>Irvine, CA — Certificate in Full Stack Development</p>

      <h3>Department of Homeland Security</h3>
      <p>Office of Accessible Systems &amp; Technology — Trusted Tester Certification (Section 508 Accessibility Requirements)</p>

      <h3>California Polytechnic State University</h3>
      <p>San Luis Obispo, CA — B.S. in Business Administration, Concentration in Management Information Systems</p>

      <div class="top-margin">
        <a
          href="/assets/lindseylauria-resume.pdf"
          rel="noreferrer"
          target="_blank"
          >Download my resume (PDF)</a
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
h3,
ul {
  margin-left: 0.5rem;
}

h3 {
  margin-top: 1rem;
}

li {
  line-height: 1.5;
}

.skills-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  margin-left: 0.5rem;
}

.skills-grid > div {
  min-width: 160px;
}

.top-margin {
  margin-top: 1.5rem;
}
</style>
