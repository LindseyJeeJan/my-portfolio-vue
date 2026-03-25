<template>
  <div id="content" class="container">
    <section>
      <div class="about-hero">
        <p class="eyebrow">Senior Frontend Engineer &amp; Designer</p>
        <h1>Software<br>Developer<br>&amp; <em>Designer.</em></h1>
      </div>
      <div class="about-body">
        <div class="about-text">
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
        <div class="stat-cards">
          <div class="stat-card stat-card--accent">
            <div class="stat-number">10+</div>
            <div class="stat-label">Years<br>Experience</div>
          </div>
          <div class="stat-card">
            <div class="stat-badge">A11Y</div>
            <div class="stat-label">WCAG<br>Certified</div>
          </div>
          <div class="stat-card">
            <div class="stat-badge stat-badge--sm">Design<br>+<br>Code</div>
            <div class="stat-label">Full Stack UI</div>
          </div>
        </div>
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

.about-hero {
  margin-bottom: 2.5rem;
}

h1 em {
  font-style: italic;
  color: var(--accent);
}

.about-body {
  display: flex;
  gap: 3rem;
  align-items: flex-start;
}

.about-text {
  flex: 1;
}

.about-text p {
  margin-bottom: 1rem;
}

/* Stat cards */
.stat-cards {
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
  flex-shrink: 0;
  width: 148px;
}

.stat-card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 10px;
  padding: 1rem;
  text-align: center;
}

.stat-card--accent {
  background: var(--accent-light);
  border-color: var(--accent-border);
}

.stat-number {
  font-family: 'Playfair Display', serif;
  font-size: 2rem;
  font-weight: 800;
  color: var(--accent);
  line-height: 1;
  margin-bottom: 0.25rem;
}

.stat-badge {
  font-family: 'Manrope', sans-serif;
  font-size: 0.9rem;
  font-weight: 800;
  color: var(--accent);
  line-height: 1.2;
  margin-bottom: 0.25rem;
}

.stat-badge--sm {
  font-size: 0.78rem;
}

.stat-label {
  font-size: 0.7rem;
  font-weight: 600;
  color: var(--text-muted);
  text-transform: uppercase;
  letter-spacing: 0.08em;
  line-height: 1.3;
}

/* Responsive */
@media (max-width: 600px) {
  .about-body {
    flex-direction: column;
  }

  .stat-cards {
    flex-direction: row;
    flex-wrap: wrap;
    width: 100%;
  }

  .stat-card {
    flex: 1;
    min-width: 100px;
  }
}
</style>
