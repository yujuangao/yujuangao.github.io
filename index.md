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

.subtitle-blue {
  color: var(--accent-color);
  font-size: 1.1rem;
  font-weight: 500;
  margin-bottom: 1.5rem;
}

.bio p {
  margin-bottom: 1.2rem;
  font-size: 1.05rem;
}

.institution-link {
  color: var(--accent-color);
  text-decoration: none;
  font-weight: 500;
}

.institution-link:hover {
  color: #2980b9;
  text-decoration: underline;
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
}

.link-item a:hover {
  color: #2980b9;
  text-decoration: underline;
}

.download-buttons {
  display: flex;
  gap: 1rem;
  margin-top: 1rem;
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
}
</style>

<div class="about-container">
  <div class="profile-section">
    <img src="yujuangao.jpg" alt="Yujuan Gao" class="profile-image">

    <div class="intro-content">
      <h1>Yujuan Gao</h1>

      <p class="subtitle-blue">
        Postdoctoral Researcher, 
        <a href="https://kohl.aaec.vt.edu/" target="_blank" class="institution-link">
          Kohl Centre
        </a>, 
        Virginia Tech
      </p>

      <div class="bio">
        <p>
          I am a Postdoctoral Researcher at the 
          <a href="https://kohl.aaec.vt.edu/" target="_blank" class="institution-link">
            Kohl Centre
          </a>
          at Virginia Tech. I received my Ph.D. in the Food and Resource Economics Department 
          at the University of Florida. My research focuses on development economics, health economics, 
          and the economics of education, with an emphasis on causal inference, impact evaluation, 
          and applied econometrics.
        </p>

        <p>
          My work leverages field experiments, administrative data, and social network analysis 
          to examine how digital technology, information interventions, and education policies 
          influence development outcomes across the life cycle.
        </p>
      </div>
    </div>
  </div>

  <div class="section-header">
    <span class="icon">📄</span>
    <h2>Documents</h2>
  </div>

  <div class="download-buttons">
    <a href="assets/pdf/Yujuan_Gao_CV.pdf" target="_blank" class="btn">📄 View CV</a>
    <a href="assets/pdf/Yujuan_Gao_Resume.pdf" target="_blank" class="btn btn-outline">📑 View Resume</a>
  </div>

  <div class="section-header">
    <span class="icon">🔗</span>
    <h2>Connect & Contact</h2>
  </div>

  <div class="links-grid">
    <div class="link-card">
      <h3><span class="emoji">🌐</span>Professional</h3>

      <div class="link-item">
        <span class="emoji">💼</span>
        <a href="https://www.linkedin.com/in/yujuangao/" target="_blank">LinkedIn Profile</a>
      </div>

      <div class="link-item">
        <span class="emoji">📚</span>
        <a href="https://scholar.google.com/citations?user=YOURREALID" target="_blank">Google Scholar</a>
      </div>
    </div>

    <div class="link-card">
      <h3><span class="emoji">💻</span>Code & Projects</h3>

      <div class="link-item">
        <span class="emoji">⚡</span>
        <a href="https://github.com/yujuangao?tab=repositories" target="_blank">GitHub Repositories</a>
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
        <a href="mailto:yujuangao@vt.edu">yujuangao@vt.edu</a>
      </div>

      <div class="link-item">
        <span class="emoji">📩</span>
        <a href="mailto:gyj12365@gmail.com">gyj12365@gmail.com</a>
      </div>

      <p style="margin-top: 1rem; color: var(--muted-color); font-size: 0.95rem; padding-left: 0.5rem;">
        🏢 Kohl Centre<br>
        Virginia Tech
      </p>
    </div>
  </div>
</div>
