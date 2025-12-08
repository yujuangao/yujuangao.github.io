---
layout: page
title: About Me
permalink: /
---

<style>
/* --- 1. COLOR PALETTE --- */
:root {
  --primary-color: #2c3e50;  /* Dark Blue (Text & Headers) */
  --accent-color: #3498db;   /* Bright Blue (Links & Buttons) */
  --bg-subtle: #f8f9fa;      /* Very light grey for backgrounds */
  --border-light: #e9ecef;
  --spacing-unit: 1.5rem;
}

/* --- 2. LAYOUT CONTAINER --- */
.about-container {
  max-width: 900px;
  margin: 0 auto;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  color: var(--primary-color);
  line-height: 1.7;
}

/* --- 3. HERO SECTION (Photo + Key Info) --- */
.hero-section {
  display: flex;
  gap: 3rem;
  align-items: center;
  margin-bottom: 3rem;
  padding-bottom: 2rem;
  border-bottom: 1px solid var(--border-light);
}

.profile-image-container {
  flex-shrink: 0;
}

.profile-image {
  width: 200px;
  height: 200px;
  border-radius: 50%; /* Circle looks more modern */
  object-fit: cover;
  border: 4px solid white;
  box-shadow: 0 10px 25px rgba(0,0,0,0.1);
}

.hero-content h1 {
  font-size: 2.5rem;
  font-weight: 700;
  margin: 0 0 1rem 0;
  color: var(--primary-color);
  line-height: 1.2;
}

/* The List of Roles (PhD, RA) */
.role-list {
  list-style: none;
  padding: 0;
  margin: 0 0 1.5rem 0;
}

.role-list li {
  margin-bottom: 0.5rem;
  font-size: 1.1rem;
  color: var(--primary-color); /* Your requested Dark Blue */
  font-weight: 500;
  display: flex;
  align-items: flex-start;
}

.role-list li::before {
  content: "•";
  color: var(--accent-color);
  margin-right: 0.8rem;
  font-weight: bold;
}

.role-list a {
  color: var(--primary-color);
  text-decoration: underline;
  text-underline-offset: 4px;
}

.role-list a:hover {
  color: var(--accent-color);
}

/* The Job Market Badge */
.job-market-badge {
  display: inline-block;
  background-color: #e8f4f8; /* Very light blue background */
  color: var(--primary-color); /* Dark Blue Text */
  padding: 0.6rem 1.2rem;
  border-radius: 50px;
  font-weight: 600;
  font-size: 1rem;
  border: 1px solid #bee3f8;
}

/* --- 4. BIO TEXT --- */
.bio-section {
  font-size: 1.1rem;
  margin-bottom: 3rem;
  max-width: 800px;
}

.bio-section p {
  margin-bottom: 1.5rem;
}

/* --- 5. BUTTONS & SECTIONS --- */
.section-title {
  font-size: 1.4rem;
  font-weight: 700;
  margin-bottom: 1.5rem;
  display: flex;
  align-items: center;
  color: var(--primary-color);
}

.section-title span {
  margin-right: 0.8rem;
}

.btn-group {
  display: flex;
  gap: 1rem;
  margin-bottom: 4rem;
  flex-wrap: wrap;
}

.btn {
  display: inline-flex;
  align-items: center;
  padding: 0.8rem 1.5rem;
  background: var(--accent-color);
  color: white;
  text-decoration: none;
  border-radius: 8px;
  font-weight: 600;
  transition: transform 0.2s, background 0.2s;
  box-shadow: 0 4px 6px rgba(52, 152, 219, 0.2);
}

.btn:hover {
  transform: translateY(-2px);
  background: #2980b9;
  color: white;
  text-decoration: none;
}

.btn-outline {
  background: white;
  color: var(--accent-color);
  border: 2px solid var(--accent-color);
  box-shadow: none;
}

.btn-outline:hover {
  background: var(--bg-subtle);
  color: #2980b9;
}

/* --- 6. CONTACT GRID --- */
.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
}

.info-card {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  border: 1px solid var(--border-light);
  transition: transform 0.2s, box-shadow 0.2s;
}

.info-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.05);
  border-color: var(--accent-color);
}

.info-card h3 {
  font-size: 1.2rem;
  margin-top: 0;
  margin-bottom: 1.2rem;
  color: var(--primary-color);
  border-bottom: 2px solid var(--bg-subtle);
  padding-bottom: 0.8rem;
}

.link-row {
  display: flex;
  align-items: center;
  margin-bottom: 0.8rem;
  font-size: 1rem;
}

.link-row span {
  font-size: 1.2rem;
  margin-right: 1rem;
  width: 24px;
  text-align: center;
}

.link-row a {
  color: var(--primary-color);
  text-decoration: none;
  font-weight: 500;
  transition: color 0.2s;
}

.link-row a:hover {
  color: var(--accent-color);
}

/* --- MOBILE RESPONSIVE --- */
@media (max-width: 768px) {
  .hero-section {
    flex-direction: column;
    text-align: center;
    gap: 1.5rem;
  }
  
  .role-list li {
    justify-content: center;
  }
  
  .btn-group {
    justify-content: center;
  }
}
</style>

<div class="about-container">

  <div class="hero-section">
    <div class="profile-image-container">
      <img src="yujuangao.jpg" alt="Yujuan Gao" class="profile-image">
    </div>
    
    <div class="hero-content">
      <h1>Yujuan Gao</h1>
      
      <ul class="role-list">
        <li>Ph.D. Candidate in Applied Economics, University of Florida</li>
        <li>
          Research Assistant at&nbsp;
          <a href="https://profiles.stanford.edu/yujuan-gao?releaseVersion=11.5.1">
            Freeman Spogli Institute, Stanford University
          </a>
        </li>
      </ul>

      <div class="job-market-badge">
        🏛️ I'm on the Job Market for 2025-2026
      </div>
    </div>
  </div>

  <div class="bio-section">
    <p>I am a Ph.D. candidate in the Food and Resource Economics Department at the University of Florida. My research focuses on <strong>development economics, health economics, and the economics of education</strong>, with an emphasis on causal inference, impact evaluation, and applied econometrics.</p>
    
    <p>My work leverages field experiments, administrative data, and social network analysis to examine how digital technology, information interventions, and education policies influence development outcomes across the life cycle.</p>
  </div>

  <h2 class="section-title"><span>📄</span> Documents</h2>
  <div class="btn-group">
    <a href="assets/pdf/Yujuan_Gao_CV.pdf" target="_blank" class="btn">View CV</a>
    <a href="assets/pdf/Yujuan_Gao_Resume.pdf" target="_blank" class="btn btn-outline">View Resume</a>
  </div>

  <h2 class="section-title"><span>🔗</span> Connect</h2>
  <div class="grid-container">
    
    <div class="info-card">
      <h3>Professional</h3>
      <div class="link-row">
        <span>💼</span> <a href="https://www.linkedin.com/in/yujuangao/">LinkedIn</a>
      </div>
      <div class="link-row">
        <span>📚</span> <a href="https://scholar.google.com/citations?user=YOURREALID">Google Scholar</a>
      </div>
    </div>

    <div class="info-card">
      <h3>Research</h3>
      <div class="link-row">
        <span>⚡</span> <a href="https://github.com/yujuangao?tab=repositories">GitHub Repositories</a>
      </div>
      <div class="link-row">
        <span>🔬</span> <a href="/research/">Research Portfolio</a>
      </div>
    </div>

    <div class="info-card">
      <h3>Contact</h3>
      <div class="link-row">
        <span>✉️</span> <a href="mailto:yujuan.gao@ufl.edu">yujuan.gao@ufl.edu</a>
      </div>
      <div style="margin-top: 1rem; font-size: 0.9rem; color: #7f8c8d; line-height: 1.5;">
        🏢 G125 McCarty Hall B<br>
        PO Box 110240<br>
        Gainesville, FL 32611
      </div>
    </div>

  </div>
</div>
