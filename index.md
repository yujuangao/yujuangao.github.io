---
layout: page
title: About Me
permalink: /
---

<style>
:root {
  --primary-color: #2c3e50;
  --accent-color: #3498db;
  --text-color: #2c3e50;
  --muted-color: #7f8c8d;
  --border-color: #ecf0f1;
  --hover-color: #f8f9fa;
}

.about-container {
  max-width: 900px;
  margin: 0 auto;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  line-height: 1.6;
  color: var(--text-color);
}

.profile-section {
  display: grid;
  grid-template-columns: 220px 1fr;
  gap: 2.5rem;
  margin: 2rem 0 3rem;
  align-items: start;
}

.profile-image {
  width: 220px;
  height: 220px;
  border-radius: 12px;
  object-fit: cover;
  box-shadow: 0 4px 6px rgba(0,0,0,0.07);
  border: 1px solid var(--border-color);
  transition: all 0.3s ease;
}

.profile-image:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.1);
}

.intro-content h1 {
  font-size: 2.2rem;
  font-weight: 600;
  color: var(--primary-color);
  margin: 0 0 0.5rem;
}

.subtitle {
  color: var(--accent-color);
  font-size: 1.1rem;
  font-weight: 500;
  margin-bottom: 1.5rem;
}

.bio p {
  margin-bottom: 1.2rem;
  font-size: 1.05rem;
}

.section-header {
  display: flex;
  align-items: center;
  margin: 3rem 0 1.5rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid var(--accent-color);
}

.section-header h2 {
  font-size: 1.5rem;
  margin: 0;
  font-weight: 600;
  color: var(--primary-color);
}

.section-header .icon {
  font-size: 1.3rem;
  margin-right: 0.5rem;
  color: var(--accent-color);
}

.links-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.link-card {
  background: white;
  padding: 1.5rem;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.07);
  border: 1px solid var(--border-color);
  transition: all 0.3s ease;
}

.link-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.1);
}

.link-card h3 {
  margin: 0 0 1rem;
  font-size: 1.2rem;
  font-weight: 600;
  color: var(--primary-color);
  display: flex;
  align-items: center;
}

.link-card h3 .emoji {
  margin-right: 0.5rem;
  font-size: 1.1rem;
}

.link-item {
  display: flex;
  align-items: center;
  margin: 0.8rem 0;
  padding: 0.5rem;
  border-radius: 6px;
  transition: all 0.2s ease;
}

.link-item:hover {
  background: var(--hover-color);
}

.link-item .emoji {
  margin-right: 0.8rem;
  font-size: 1rem;
}

.link-item a {
  color: var(--accent-color);
  text-decoration: none;
  font-weight: 500;
  transition: color 0.2s ease;
}

.link-item a:hover {
  color: #2980b9;
  text-decoration: underline;
}

.download-buttons {
  display: flex;
  gap: 1rem;
  margin-top: 1rem;
  flex-wrap: wrap;
}

.btn {
  display: inline-block;
  padding: 0.6rem 1.2rem;
  background: var(--accent-color);
  color: white;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 500;
  transition: all 0.2s ease;
  cursor: pointer;
  border: none;
}

.btn:hover {
  background: #2980b9;
  transform: translateY(-1px);
  color: white;
  text-decoration: none;
}

.btn-outline {
  background: transparent;
  color: var(--accent-color);
  border: 1px solid var(--accent-color);
}

.btn-outline:hover {
  background: var(--accent-color);
  color: white;
}

/* --- NEW STYLES FOR CV WINDOW --- */
.pdf-window {
  width: 100%;
  height: 800px; /* Adjust height as needed */
  margin-top: 1.5rem;
  border: 1px solid #ddd;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.05);
}

/* Simple details/summary toggle for clean UI */
details.cv-preview-toggle {
  width: 100%;
  margin-top: 1rem;
}

details.cv-preview-toggle summary {
  list-style: none; /* Hides default triangle */
}

/* Responsive design */
@media (max-width: 768px) {
  .profile-section {
    grid-template-columns: 1fr;
    gap: 1.5rem;
    text-align: center;
  }
  
  .profile-image {
    width: 180px;
    height: 180px;
    margin: 0 auto;
  }
  
  .intro-content h1 {
    font-size: 1.8rem;
  }
  
  .links-grid {
    grid-template-columns: 1fr;
  }
  
  .download-buttons {
    flex-direction: column;
  }
  
  .about-container {
    padding: 0 1rem;
  }

  /* On mobile, make the window shorter */
  .pdf-window {
    height: 500px;
  }
}
</style>

<div class="about-container">
  <div class="profile-section">
    <img src="yujuangao.jpg" alt="Yujuan Gao" class="profile-image">
    <div class="intro-content">
      <h1>Yujuan Gao</h1>
      <p class="subtitle">Ph.D. Candidate in Applied Economics</p>
      
      <div class="bio">
        <p>I am a Ph.D. candidate in the Food and Resource Economics Department at the University of Florida. My research focuses on development economics, health economics, and the economics of education, with an emphasis on causal inference, impact evaluation, and applied econometrics.</p>
        
        <p>My work leverages field experiments, administrative data, and social network analysis to examine how digital technology, information interventions, and education policies influence development outcomes across the life cycle.</p>
        
        <p>I also serve as a Research Assistant at <a href="https://profiles.stanford.edu/yujuan-gao?releaseVersion=11.5.1">the Freeman Spogli Institute for International Studies, Stanford University</a>.</p>

        <p><strong>I'm on the Job Market for 2025-2026</strong></p>
        
      </div>
    </div>
  </div>

  <div class="section-header">
    <span class="icon">📄</span>
    <h2>Documents</h2>
  </div>
  
  <div class="download-buttons">
    <a href="https://github.com/yujuangao/CV-for-JM-Econ/raw/main/Yujuan_Gao_CV.pdf" target="_blank" class="btn">⬇️ Download CV</a>
    <a href="https://github.com/yujuangao/CV_App-usage/raw/main/Yujuan_Gao_Resume.pdf" target="_blank" class="btn btn-outline">⬇️ Download Resume</a>
  </div>

  <details class="cv-preview-toggle" open>
    <summary class="btn btn-outline" style="margin-top: 10px; text-align:center; display:none;">
      </summary>
    
    <iframe 
      class="pdf-window" 
      src="https://docs.google.com/gview?url=https://github.com/yujuangao/CV-for-JM-Econ/raw/main/Yujuan_Gao_CV.pdf&embedded=true" 
      frameborder="0">
    </iframe>
  </details>

  <div class="section-header">
    <span class="icon">🔗</span>
    <h2>Connect & Contact</h2>
  </div>

  <div class="links-grid">
    <div class="link-card">
      <h3><span class="emoji">🌐</span>Professional</h3>
      <div class="link-item">
        <span class="emoji">💼</span>
        <a href="https://www.linkedin.com/in/yujuangao/">LinkedIn Profile</a>
      </div>
      <div class="link-item">
        <span class="emoji">📚</span>
        <a href="https://scholar.google.com/citations?user=YOURREALID">Google Scholar</a>
      </div>
    </div>

    <div class="link-card">
      <h3><span class="emoji">💻</span>Code & Projects</h3>
      <div class="link-item">
        <span class="emoji">⚡</span>
        <a href="https://github.com/yujuangao?tab=repositories">GitHub Repositories</a>
      </div>
      <div class="link-item">
        <span class="emoji">🔬</span>
        <a href="/research/">Research Portfolio</a>
      </div>
    </div>

    <div class="link-card">
      <h3><span class="emoji">📧</span>Get in Touch</h3>
      <div class="link-item">
        <span class="emoji">✉️</span>
        <a href="mailto:yujuan.gao@ufl.edu">yujuan.gao@ufl.edu</a>
      </div>
      <p style="margin-top: 1rem; color: var(--muted-color); font-size: 0.95rem; padding-left: 0.5rem;">
        🏢 G125 McCarty Hall B<br>
        PO Box 110240<br>
        Gainesville, FL 32611-0240
      </p>
    </div>
  </div>
</div>
