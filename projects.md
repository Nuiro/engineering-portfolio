---
layout: page
title: Projects
permalink: /projects/
---

# Projects

<div class="projects-grid">

  <div class="project-card">
    <a href="/home-subwoofer/" class="project-link">
      <div class="project-image-wrap">
        <img src="/assets/images/subwoofer/2025_07_16_19_07_IMG_0205.JPG" class="project-image">
      </div>
      <h3>Home Subwoofer Setup</h3>
    </a>
    <p>Built a custom at-home subwoofer setup, including wiring, power supply integration, and grounding to eliminate noise.</p>
  </div>

  <div class="project-card">
    <a href="/arduino-circuits/" class="project-link">
      <div class="project-image-wrap">
        <img src="/assets/images/arduino/2025_08_01_20_59_IMG_0350.JPG" class="project-image">
      </div>
      <h3>Arduino Circuits</h3>
    </a>
    <p>Worked on Arduino-based circuits, designing and testing voltage and current behaviour using resistors and measurement tools.</p>
  </div>

  <div class="project-card">
    <a href="/ewb-water-filter/" class="project-link">
      <div class="project-image-wrap">
        <img src="/assets/images/ewb/2025_05_20_01_28_IMG_9849.JPG" class="project-image">
      </div>
      <h3>EWB Water Filter Project</h3>
    </a>
    <p>Designed a cost-efficient water filtration system for rural Timor-Leste, leading team coordination and SolidWorks design.</p>
  </div>

  <div class="project-card">
    <a href="/catapult-design/" class="project-link">
      <div class="project-image-wrap">
        <img src="/assets/images/catapult/IMG_3295.JPG" class="project-image">
      </div>
      <h3>Catapult Design Project</h3>
    </a>
    <p>Developed a mechanical launch system with adjustable radius and energy storage concepts.</p>
  </div>

  <div class="project-card">
    <a href="/solidworks-practice/" class="project-link">
      <div class="project-image-wrap">
        <img src="/assets/images/solidworks/Screenshot 2026-03-30 182949.png" class="project-image">
      </div>
      <h3>SolidWorks Practice</h3>
    </a>
    <p>Ongoing SolidWorks practice using CSWA and CSWP problems to improve modelling accuracy and drawing interpretation.</p>
  </div>

  <div class="project-card">
    <a href="/engineering-drawings/" class="project-link">
      <div class="project-image-wrap">
        <img src="/assets/images/drawings/Isometric.JPG" class="project-image">
      </div>
      <h3>Engineering Drawings</h3>
    </a>
    <p>Created engineering drawings from CAD models, focusing on accurate dimensioning and clear technical communication.</p>
  </div>

</div>

<style>
/* make page wider */
.wrapper {
  max-width: 1200px;
}

/* grid */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 32px;
}

/* cards */
.project-card {
  box-sizing: border-box;
  background: #ffffff;
  padding: 18px;
  border-radius: 16px;
  box-shadow: 0 12px 30px rgba(0,0,0,0.22);
  transition: transform 0.25s ease, box-shadow 0.25s ease, background 0.25s ease, color 0.25s ease;
}

.project-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 20px 50px rgba(0,0,0,0.32);
}

.project-link {
  text-decoration: none;
  color: inherit;
}

.project-image-wrap {
  overflow: hidden;
  border-radius: 12px;
  border: 3px solid #cfcfcf;
}

.project-image {
  width: 100%;
  display: block;
  transition: transform 0.35s ease;
}

.project-card:hover .project-image {
  transform: scale(1.06);
}

.project-card h3 {
  margin-top: 14px;
  margin-bottom: 10px;
}

/* dark mode */
body.dark-mode {
  background: #0f1115;
  color: #e6e6e6;
}

body.dark-mode .site-header,
body.dark-mode .site-footer,
body.dark-mode .page-content {
  background: #0f1115;
  color: #e6e6e6;
}

body.dark-mode .site-header {
  border-bottom-color: #222;
}

body.dark-mode .site-footer {
  border-top-color: #222;
}

body.dark-mode a {
  color: #8ab4ff;
}

body.dark-mode h1,
body.dark-mode h2,
body.dark-mode h3 {
  color: #ffffff;
}

body.dark-mode .project-card {
  background: #1a1d24;
  color: #e6e6e6;
  box-shadow: 0 14px 36px rgba(0,0,0,0.60);
}

body.dark-mode .project-card:hover {
  box-shadow: 0 22px 56px rgba(0,0,0,0.82);
}

body.dark-mode .project-image-wrap {
  border-color: #3a3f4b;
}

body.dark-mode button {
  background: #1a1d24;
  color: #ffffff;
}

body.dark-mode .wrapper {
  background: transparent;
}

/* header fix */
body.dark-mode .site-title {
  color: #ffffff !important;
}

body.dark-mode .site-nav a {
  color: #ffffff !important;
}

body.dark-mode p {
  color: #cccccc;
}

body.dark-mode .site-nav a:hover {
  color: #8ab4ff !important;
}

/* mobile */
@media (max-width: 800px) {
  .projects-grid {
    grid-template-columns: 1fr;
  }
}
</style>