---
layout: page
title: Teaching
permalink: /teaching/
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

.teaching-container {
  max-width: 900px;
  margin: 0 auto;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  line-height: 1.6;
  color: var(--text-color);
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

.courses-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.course-card {
  background: white;
  padding: 1.5rem;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.07);
  border: 1px solid var(--border-color);
  border-left: 4px solid var(--accent-color);
  transition: all 0.3s ease;
}

.course-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.1);
}

.course-title {
  font-size: 1.2rem;
  font-weight: 600;
  color: var(--primary-color);
  margin: 0 0 0.5rem;
}

.course-meta {
  color: var(--muted-color);
  font-size: 0.95rem;
  margin-bottom: 0.5rem;
}

.course-year {
  color: var(--accent-color);
  font-weight: 500;
}

.guest-lecture {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 2rem;
  border-radius: 12px;
  margin: 2rem 0;
  text-align: center;
}

.guest-lecture h3 {
  margin: 0 0 1rem;
  font-size: 1.4rem;
  font-weight: 600;
}

.guest-lecture p {
  margin: 0 0 1.5rem;
  opacity: 0.95;
}

.btn {
  display: inline-block;
  padding: 0.6rem 1.2rem;
  background: rgba(255,255,255,0.2);
  color: white;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 500;
  transition: all 0.2s ease;
  border: 1px solid rgba(255,255,255,0.3);
}

.btn:hover {
  background: rgba(255,255,255,0.3);
  transform: translateY(-1px);
  color: white;
  text-decoration: none;
}

.evaluation-section {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.07);
  border: 1px solid var(--border-color);
  margin: 2rem 0;
}

.evaluation-table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 1rem;
}

.evaluation-table th,
.evaluation-table td {
  padding: 0.8rem;
  text-align: left;
  border-bottom: 1px solid var(--border-color);
}

.evaluation-table th {
  background: var(--hover-color);
  font-weight: 600;
  color: var(--primary-color);
}

.evaluation-table tr:hover {
  background: var(--hover-color);
}

.note {
  color: var(--muted-color);
  font-size: 0.9rem;
  margin-top: 1rem;
  font-style: italic;
}

/* Responsive design */
@media (max-width: 768px) {
  .courses-grid {
    grid-template-columns: 1fr;
  }
  
  .teaching-container {
    padding: 0 1rem;
  }
  
  .evaluation-table {
    font-size: 0.9rem;
  }
  
  .evaluation-table th,
  .evaluation-table td {
    padding: 0.6rem 0.4rem;
  }
}
</style>

<div class="teaching-container">
  <div class="section-header">
    <span class="icon">🎯</span>
    <h2>Teaching Statement</h2>
  </div>

  <div class="evaluation-section">
    <p><strong>Teaching Interests:</strong> Microeconomics, Econometrics, Applied Statistics, Economics of Education, Development Economics, Health Economics</p>
    
    <p>My teaching philosophy centers on making complex economic concepts accessible through clear explanations, real-world applications, and interactive learning approaches. I believe in connecting theoretical frameworks to practical policy applications and helping students understand how economic principles apply to contemporary challenges.</p>
    
    <p>As an educator, I strive to create an engaging classroom environment that encourages critical thinking and active participation. My experience as a teaching assistant across multiple economics courses has reinforced my commitment to supporting student learning through personalized guidance and responsive instruction.</p>
  </div>

  <div class="section-header">
    <span class="icon">🎓</span>
    <h2>Teaching Assistant Experience</h2>
  </div>

  <div class="courses-grid">
    <div class="course-card">
      <h3 class="course-title">AEB 3103 - Principles of Food & Resource Economics</h3>
      <p class="course-meta">Teaching Assistant for Prof. Xinde "James" Ji</p>
      <p class="course-year">2025</p>
    </div>

    <div class="course-card">
      <h3 class="course-title">AEB 3341 - Selling Strategically</h3>
      <p class="course-meta">Teaching Assistant for Prof. John Lai</p>
      <p class="course-year">2024</p>
    </div>

    <div class="course-card">
      <h3 class="course-title">AEB 3133 - Principles of Agribusiness Management</h3>
      <p class="course-meta">Teaching Assistant for Prof. Xumin Zhang</p>
      <p class="course-year">2023</p>
    </div>

    <div class="course-card">
      <h3 class="course-title">AEB 3671 - Comparative World Agriculture</h3>
      <p class="course-meta">Teaching Assistant for Prof. Jared Gars</p>
      <p class="course-year">2023</p>
    </div>

    <div class="course-card">
      <h3 class="course-title">AEB 4138 - Advanced Agribusiness Management</h3>
      <p class="course-meta">Teaching Assistant for Prof. Jaclyn Kropp</p>
      <p class="course-year">2022</p>
    </div>

    <div class="course-card">
      <h3 class="course-title">AEB 4673 - International Agricultural Trade</h3>
      <p class="course-meta">Teaching Assistant for Prof. Conner Mullally</p>
      <p class="course-year">2022</p>
    </div>

    <div class="course-card">
      <h3 class="course-title">AEB 4283 - International Development Policy</h3>
      <p class="course-meta">Teaching Assistant for Prof. Conner Mullally</p>
      <p class="course-year">2021</p>
    </div>
  </div>

  <div class="guest-lecture">
    <h3>Guest Lecture</h3>
    <p><strong>IDS 2935-22961 - How Do We End Poverty?</strong> (2023)</p>
    <a href="Slides.pdf" class="btn">📊 View Lecture Slides</a>
  </div>

  <div class="section-header">
    <span class="icon">📊</span>
    <h2>Teaching Evaluations</h2>
  </div>

  <div class="evaluation-section">
    <p>Student feedback from my guest lecture on poverty reduction strategies:</p>
    
    <table class="evaluation-table">
      <thead>
        <tr>
          <th>Evaluation Criteria</th>
          <th>Score</th>
          <th>Selected Comments</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Did the instructor show enthusiasm/interest in the subject?</td>
          <td>8.84</td>
          <td>Demonstrated high enthusiasm and passion for teaching.</td>
        </tr>
        <tr>
          <td>Did the instructor organize content in a way that was easy to follow?</td>
          <td>9.14</td>
          <td>Well-structured lectures with clear progression of topics.</td>
        </tr>
        <tr>
          <td>Did the instructor explain concepts clearly?</td>
          <td>8.89</td>
          <td>Made complex topics accessible through clear explanations.</td>
        </tr>
        <tr>
          <td>Did the instructor engage your understanding?</td>
          <td>8.86</td>
          <td>Regularly checked comprehension and adjusted pace accordingly.</td>
        </tr>
        <tr>
          <td>Did the materials provided help clarify the material?</td>
          <td>8.78</td>
          <td>Supporting materials enhanced learning experience.</td>
        </tr>
        <tr>
          <td>Were the course aids and materials clear and helpful?</td>
          <td>8.77</td>
          <td>Visual aids and handouts effectively supported lectures.</td>
        </tr>
        <tr>
          <td>How well did the instructor encourage participation?</td>
          <td>8.16</td>
          <td>Created interactive environment for student engagement.</td>
        </tr>
        <tr>
          <td>How well did the instructor demonstrate knowledge?</td>
          <td>8.77</td>
          <td>Showed expertise through relevant examples and explanations.</td>
        </tr>
        <tr>
          <td>Were real-world applications and examples provided?</td>
          <td>8.92</td>
          <td>Effectively linked theory to practical applications.</td>
        </tr>
        <tr>
          <td>Was the instructor responsive to student questions?</td>
          <td>9.01</td>
          <td>Addressed questions thoroughly and clearly.</td>
        </tr>
      </tbody>
    </table>
    
    <p class="note">
      <strong>Note:</strong> 27 students evaluated the lecture. Scores based on 10-point scale. 
      Detailed teaching evaluation data is available in the 
      <a href="https://github.com/yujuangao/teaching-evaluation" style="color: var(--accent-color);">teaching-evaluation repository</a> 
      on GitHub.
    </p>
  </div>

  <div class="section-header">
    <span class="icon">🏆</span>
    <h2>Professional Development</h2>
  </div>

  <div class="course-card">
    <h3 class="course-title">Preparing Future Faculty Program</h3>
    <p class="course-meta">Center for Teaching Excellence, University of Florida</p>
    <p class="course-year">Fall 2024</p>
    <p>Comprehensive training program focused on pedagogical methods, curriculum development, and effective teaching strategies in higher education.</p>
  </div>
</div>
