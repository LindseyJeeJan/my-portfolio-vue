<template>
  <div id="content" class="container">
    <section>
      <div class="resume-header">
        <p class="eyebrow">Experience &amp; Skills</p>
        <h1>Résumé</h1>
      </div>

      <div class="resume-section">
        <h2>Summary</h2>
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
      </div>

      <div class="resume-section">
        <h2>Skills</h2>
        <div class="skills-grid">
          <div class="skill-group">
            <span class="skill-category">Core</span>
            <div class="skill-tags">
              <span class="tag">TypeScript</span>
              <span class="tag">React</span>
              <span class="tag">Vue.js</span>
              <span class="tag">HTML</span>
              <span class="tag">CSS / SCSS</span>
            </div>
          </div>
          <div class="skill-group">
            <span class="skill-category">Architecture</span>
            <div class="skill-tags">
              <span class="tag">Web Components</span>
              <span class="tag">REST APIs</span>
              <span class="tag">SSE</span>
            </div>
          </div>
          <div class="skill-group">
            <span class="skill-category">State</span>
            <div class="skill-tags">
              <span class="tag">Zustand</span>
              <span class="tag">Pinia</span>
            </div>
          </div>
          <div class="skill-group">
            <span class="skill-category">Testing</span>
            <div class="skill-tags">
              <span class="tag">Vitest</span>
              <span class="tag">React Testing Library</span>
              <span class="tag">Cypress</span>
            </div>
          </div>
          <div class="skill-group">
            <span class="skill-category">Tooling</span>
            <div class="skill-tags">
              <span class="tag">Vite</span>
              <span class="tag">Webpack</span>
              <span class="tag">Node.js</span>
              <span class="tag">Yarn</span>
            </div>
          </div>
          <div class="skill-group">
            <span class="skill-category">Accessibility</span>
            <div class="skill-tags">
              <span class="tag">WCAG</span>
              <span class="tag">ARIA</span>
              <span class="tag">Screen Readers</span>
              <span class="tag">Keyboard Navigation</span>
            </div>
          </div>
          <div class="skill-group">
            <span class="skill-category">AI</span>
            <div class="skill-tags">
              <span class="tag">Claude Code</span>
              <span class="tag">GitHub Copilot</span>
            </div>
          </div>
        </div>
      </div>

      <div class="resume-section">
        <h2>Experience</h2>

        <div class="exp-item">
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
        </div>

        <div class="exp-item">
          <h3>Senior Interaction Designer / Developer</h3>
          <ul>
            <li>Developed reusable components and responsive layouts with vanilla HTML, CSS, and JavaScript, maintaining a shared CSS library for consistency over Java backend with Postgres db.</li>
            <li>Built interactive rapid prototypes to validate product requirements and technical feasibility. Designed wireframes and prototypes in Sketch, driving product and technical strategy.</li>
            <li>Often acted as liaison between product managers and design teams to translate requirements into scalable frontend solutions.</li>
            <li>Established accessibility standards, translating WCAG guidelines into actionable engineering tasks.</li>
          </ul>
        </div>

        <div class="exp-item">
          <h3>Web Developer</h3>
          <ul>
            <li>Converted design assets from Photoshop/InDesign into interactive web experiences with HTML, CSS, and JavaScript.</li>
            <li>Created dynamic UI components and media-rich interfaces using Adobe Flash and ActionScript.</li>
            <li>Managed timelines and cross-functional collaboration with strong organizational skills.</li>
          </ul>
        </div>
      </div>

      <div class="resume-section">
        <h2>Education &amp; Certifications</h2>

        <div class="edu-item">
          <h3>UCI Division of Continuing Education</h3>
          <p>Irvine, CA — Certificate in Full Stack Development</p>
        </div>

        <div class="edu-item">
          <h3>Department of Homeland Security</h3>
          <p>Office of Accessible Systems &amp; Technology — Trusted Tester Certification (Section 508 Accessibility Requirements)</p>
        </div>

        <div class="edu-item">
          <h3>California Polytechnic State University</h3>
          <p>San Luis Obispo, CA — B.S. in Business Administration, Concentration in Management Information Systems</p>
        </div>

        <a
          class="download-btn"
          href="/assets/lindseylauria-resume.pdf"
          rel="noreferrer"
          target="_blank"
        >↓ Download Resume (PDF)</a>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
</script>

<style scoped>
.eyebrow {
  font-family: 'Manrope', sans-serif;
  font-size: 0.75rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.14em;
  color: var(--accent);
  margin-bottom: 0.75rem;
}

.resume-header {
  margin-bottom: 2.5rem;
}

.resume-section {
  margin-bottom: 2.5rem;
}

h2 {
  padding-bottom: 0.5rem;
  border-bottom: 1.5px solid var(--border);
  margin-bottom: 1rem;
  margin-top: 0;
}

h3 {
  font-family: 'Manrope', sans-serif;
  font-size: 0.95rem;
  font-weight: 700;
  color: var(--text);
  margin-top: 1rem;
  margin-bottom: 0.4rem;
}

.exp-item {
  margin-bottom: 1.5rem;
}

.edu-item {
  margin-bottom: 1rem;
}

.edu-item p {
  font-size: 0.88rem;
  margin: 0;
}

/* Skills */
.skills-grid {
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
  margin: 0.75rem 0 0;
}

.skill-group {
  display: flex;
  align-items: flex-start;
  gap: 0.75rem;
}

.skill-category {
  min-width: 90px;
  font-size: 0.75rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.07em;
  color: var(--text-muted);
  padding-top: 0.35rem;
  flex-shrink: 0;
}

.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
}

.tag {
  background-color: var(--surface);
  color: var(--text);
  border: 1px solid var(--border);
  border-radius: 20px;
  padding: 0.2rem 0.75rem;
  font-size: 0.85rem;
  font-weight: 500;
}

/* Download button */
.download-btn {
  display: inline-block;
  margin-top: 1.5rem;
  background: var(--accent);
  color: #fff;
  font-family: 'Manrope', sans-serif;
  font-size: 0.88rem;
  font-weight: 700;
  padding: 0.6rem 1.4rem;
  border-radius: 100px;
  text-decoration: none;
  transition: background 0.2s;
}

.download-btn:hover {
  background: var(--accent-hover);
  color: #fff;
  text-decoration: none;
}
</style>
