---
layout: page
title: Research
permalink: /research/
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

.research-container { 
  max-width: 900px; 
  margin: 0 auto; 
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  line-height: 1.6;
  color: var(--text-color);
}

.hero-section {
  text-align: center;
  padding: 2rem 0 3rem;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  margin: -2rem -2rem 3rem;
  border-radius: 0 0 20px 20px;
}

.hero-section h1 { 
  font-size: 2.5rem; 
  margin-bottom: 0.5rem; 
  font-weight: 700;
}

.hero-section .subtitle { 
  font-size: 1.2rem; 
  opacity: 0.9;
  font-weight: 300;
}

.section-header {
  display: flex;
  align-items: center;
  margin: 3rem 0 1.5rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid var(--accent-color);
}

.section-header h2 {
  font-size: 1.8rem;
  margin: 0;
  font-weight: 600;
  color: var(--primary-color);
}

.section-header .icon {
  font-size: 1.5rem;
  margin-right: 0.5rem;
  color: var(--accent-color);
}

/* Featured papers with enhanced design */
.featured-paper {
  display: grid;
  grid-template-columns: 240px 1fr;
  gap: 1.5rem;
  padding: 1.5rem;
  margin-bottom: 2rem;
  background: white;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.07);
  border: 1px solid var(--border-color);
  transition: all 0.3s ease;
}

.featured-paper:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.1);
}

.featured-paper img {
  width: 100%;
  max-width: 240px;
  height: 160px;
  object-fit: cover;
  border-radius: 8px;
  border: none;
}

.paper-content h3 {
  margin: 0 0 0.5rem;
  font-size: 1.3rem;
  font-weight: 600;
  color: var(--primary-color);
  line-height: 1.3;
}

.paper-meta {
  color: var(--muted-color);
  font-size: 0.95rem;
  margin: 0.3rem 0 1rem;
  font-style: italic;
}

.paper-actions {
  margin: 1rem 0;
}

.btn {
  display: inline-block;
  padding: 0.5rem 1rem;
  margin-right: 0.5rem;
  margin-bottom: 0.5rem;
  background: var(--accent-color);
  color: white;
  text-decoration: none;
  border-radius: 6px;
  font-size: 0.9rem;
  font-weight: 500;
  transition: all 0.2s ease;
}

.btn:hover {
  background: #2980b9;
  transform: translateY(-1px);
  text-decoration: none;
  color: white;
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

/* Abstract toggle */
details {
  margin-top: 1rem;
}

details summary {
  cursor: pointer;
  font-weight: 600;
  color: var(--accent-color);
  padding: 0.5rem 0;
  border-radius: 4px;
  transition: color 0.2s ease;
}

details summary:hover {
  color: #2980b9;
}

details p {
  margin-top: 1rem;
  padding: 1rem;
  background: var(--hover-color);
  border-radius: 6px;
  border-left: 4px solid var(--accent-color);
}

/* Publications list */
.publication-list {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  margin-bottom: 2rem;
}

.publication-item {
  padding: 1rem 0;
  border-bottom: 1px solid var(--border-color);
  transition: background 0.2s ease;
}

.publication-item:last-child {
  border-bottom: none;
}

.publication-item:hover {
  background: var(--hover-color);
  padding-left: 1rem;
  margin-left: -1rem;
  border-radius: 6px;
}

.publication-item strong {
  color: var(--primary-color);
}

.publication-item em {
  color: var(--accent-color);
  font-weight: 500;
}

.publication-item a {
  color: var(--accent-color);
  text-decoration: none;
  font-weight: 500;
}

.publication-item a:hover {
  text-decoration: underline;
}

/* Working papers section */
.working-paper {
  padding: 1.5rem;
  margin-bottom: 1rem;
  background: white;
  border-radius: 8px;
  border-left: 4px solid var(--accent-color);
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

.working-paper h4 {
  margin: 0 0 0.5rem;
  font-size: 1.1rem;
  color: var(--primary-color);
}

.working-paper .authors {
  color: var(--muted-color);
  font-size: 0.9rem;
  margin-bottom: 0.5rem;
}

.tag {
  display: inline-block;
  background: #e8f4f8;
  color: var(--accent-color);
  padding: 0.2rem 0.6rem;
  border-radius: 12px;
  font-size: 0.8rem;
  font-weight: 500;
  margin-right: 0.5rem;
  margin-top: 0.5rem;
}

/* Responsive design */
@media (max-width: 768px) {
  .featured-paper {
    grid-template-columns: 1fr;
    gap: 1rem;
  }
  
  .featured-paper img {
    width: 100%;
    max-width: 100%;
    height: 220px;
  }
  
  .hero-section {
    margin: -1rem -1rem 2rem;
    padding: 1.5rem 1rem;
  }
  
  .research-container {
    padding: 0 1rem;
  }
}

@media (max-width: 1024px) {
  .featured-paper {
    grid-template-columns: 240px 1fr;
  }
  
  .featured-paper img {
    width: 240px;
    max-width: 240px;
    height: 160px;
  }
}
</style>

<div class="research-container">
  <div class="hero-section">
    <h1>Research Portfolio</h1>
    <p class="subtitle">Development Economics • Education • Digital Infrastructure</p>
  </div>

  <div class="section-header">
    <span class="icon">⭐</span>
    <h2>Featured Research</h2>
  </div>

  <div class="featured-paper">
    <img src="{{ '/3G-coverage.png' | relative_url }}" alt="3G coverage expansion in Nigeria">
    <div class="paper-content">
      <h3>The Impact of 3G Network Coverage on Fertility Decisions and Infant Mortality in Nigeria</h3>
      <p class="paper-meta">with Conner Mullally, Xinde Ji, Jared Gars</p>
      <div class="paper-actions">
        <a href="https://www.dropbox.com/scl/fi/qji2by7izuma4aoylhh61/Broadband_and_Fertility_in_Nigeria-compressed.pdf?rlkey=flzoxw0uckk4h22sux8fs3hb7&dl=0" class="btn">📄 Full Draft</a>
        <span class="tag">AAEA 2025</span>
        <span class="tag">AEA 2026</span>
      </div>
      <details>
        <summary>📋 Abstract</summary>
        <p>Using Nigerian DHS data (2013–2018) linked to 3G rollout across 725 local government areas, we find that a one standard deviation increase in coverage reduces birth probability among women aged 12–20 by 1.4–18 percentage points. Effects operate through delayed cohabitation and childbearing rather than contraceptive uptake, alongside increased skilled employment and stronger household bargaining power.</p>
      </details>
    </div>
  </div>

  <div class="featured-paper">
    <img src="{{ '/network-diagram.png' | relative_url }}" alt="Peer network spillover effects">
    <div class="paper-content">
      <h3>Unintended Consequences of Best Intentions: Examining Spillover Effects in Targeted Supplementary Education Interventions</h3>
      <p class="paper-meta">Job Market Paper</p>
      <div class="paper-actions">
        <a href="https://www.dropbox.com/scl/fi/z1hparrh8ltcy1te3n7w1/Spillover_Effect.pdf?rlkey=5bcw0rvf4bmk1zjem7mh81mzd&st=1i97r34e&dl=0" class="btn">📄 Full Draft</a>
        <span class="tag">ASSA 2025</span>
        <span class="tag">AAEA 2025</span>
        <span class="tag">APPAM 2024</span>
      </div>
      <details>
        <summary>📋 Abstract</summary>
        <p>Field experiment across 130 rural Chinese boarding schools comparing computer-assisted learning and workbook interventions. Results reveal significant negative spillovers from workbook treatments on non-targeted students, particularly those with close peer connections. The mechanism appears motivational: observing peers receive extra resources reduces confidence in academic effort. Computer-assisted learning conducted outside classrooms shows no such spillovers.</p>
      </details>
    </div>
  </div>

  <div class="section-header">
    <span class="icon">📚</span>
    <h2>Publications</h2>
  </div>

  <div class="publication-list">
    <div class="publication-item">
      Chen, Xuqi, Lisa House, Zhifeng Gao, <strong>Yujuan Gao</strong> (2024). "Do Color-Coded Nutrition Facts Panels Nudge the Use of Nutrition Information on Food Packaging?" <em>Food Policy</em>. <a href="https://doi.org/10.1016/j.foodpol.2024.102730">📖 Read Online</a>
    </div>
    
    <div class="publication-item">
      Ma, Yue, Xinwu Zhang, Lucy Pappas, Andrew Rule, <strong>Yujuan Gao</strong>, Sarah-Eve Dill, Tianli Feng, et al. (2023). "Associations between Urbanization and the Home Language Environment: Evidence from a LENA Study in Rural and Peri-urban China." <em>Child Development</em>. <a href="https://doi.org/10.1111/cdev.14034">📖 Read Online</a>
    </div>
    
    <div class="publication-item">
      <strong>Yujuan Gao</strong>, Derek Hu, Even Peng, et al. (2020). "Depressive Symptoms and the Link with Academic Performance among Rural Taiwanese Children." <em>International Journal of Environmental Research and Public Health</em>. <a href="https://doi.org/10.3390/ijerph17082778">📖 Read Online</a>
    </div>
    
    <div class="publication-item">
      Ma, Yue, <strong>Yujuan Gao</strong>, Jason Li, et al. (2020). "Maternal Health Behaviors during Pregnancy in Rural Northwestern China." <em>BMC Pregnancy and Childbirth</em>. <a href="https://doi.org/10.1186/s12884-020-03444-3">📖 Read Online</a>
    </div>
    
    <div class="publication-item">
      Ma, Yue, <strong>Yujuan Gao</strong>, Wang, Yue, et al. (2018). "Impact of a Local Vision Care Center on Glasses Ownership and Wearing Behavior in Northwestern Rural China: A Cluster-Randomized Controlled Trial." <em>International Journal of Environmental Research and Public Health</em>. <a href="https://doi.org/10.3390/ijerph15122783">📖 Read Online</a>
    </div>
  </div>

  <div class="section-header">
    <span class="icon">🔬</span>
    <h2>Working Papers</h2>
  </div>

  <div class="working-paper">
    <h4>Friendship Formation and Peer Effect: Using Seat Distribution as an Instrument</h4>
    <p class="authors">with Yu Bai and Scott Rozelle</p>
    <a href="https://dx.doi.org/10.2139/ssrn.4828554" class="btn btn-outline">📄 SSRN Draft</a>
    <span class="tag">NEUDC 2023</span>
    <span class="tag">PacDev 2024</span>
    <span class="tag">AAEA 2024</span>
  </div>

  <div class="working-paper">
    <h4>Using Text Messages to Improve Parenting Knowledge and Early Childhood Development in Rural China</h4>
    <p class="authors">with Yue Ma and Susanna Loeb</p>
    <a href="https://ssrn.com/abstract=4969618" class="btn btn-outline">📄 SSRN Draft</a>
    <span class="tag">AAEA 2022</span>
    <span class="tag">China Education Finance 2023</span>
  </div>

  <div class="section-header">
    <span class="icon">⚡</span>
    <h2>Works in Progress</h2>
  </div>

  <div class="working-paper">
    <h4>Maternal Migration and Early Child Development in Rural China</h4>
    <p class="authors">with Yue Ma & Conner Mullally</p>
    <span class="tag">SAEA 2023</span>
    <span class="tag">AAEA 2022</span>
    <span class="tag">WEAI 2022</span>
  </div>

  <div style="text-align: center; margin-top: 3rem; padding: 2rem; background: var(--hover-color); border-radius: 12px;">
    <p style="margin: 0; color: var(--muted-color); font-size: 1rem;">
      <strong style="color: var(--primary-color);">Yujuan Gao</strong><br>
      Contact: <a href="mailto:yujuan.gao@ufl.edu" style="color: var(--accent-color); font-weight: 500;">yujuan.gao@ufl.edu</a>
    </p>
  </div>
</div>
