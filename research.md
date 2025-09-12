---
layout: page
title: Research
permalink: /research/
---

<!-- ===== Clean, responsive styling (works with GitHub Pages) ===== -->
<style>
:root{
  --bg:#ffffff;
  --ink:#111827;
  --muted:#6b7280;
  --line:#e5e7eb;
  --card:#ffffff;
}
@media (prefers-color-scheme: dark){
  :root{
    --bg:#0b0f19;
    --ink:#e5e7eb;
    --muted:#9ca3af;
    --line:#1f2937;
    --card:#0f1629;
  }
}
.page-wrap { color: var(--ink); }
.lead { color: var(--muted); margin-top:.25rem; margin-bottom:1.25rem; }
.kicker { letter-spacing:.08em; text-transform:uppercase; font-weight:600; color:var(--muted); }

.grid { display:grid; grid-template-columns:1fr; gap:1.25rem; }
@media (min-width: 900px){ .grid { grid-template-columns:1fr 1fr; } }

.card{
  background:var(--card);
  border:1px solid var(--line);
  border-radius:14px;
  padding:16px;
  box-shadow:0 6px 16px rgba(0,0,0,.06);
}
.card h3{ margin:.4rem 0 .25rem; }
.meta{ color:var(--muted); font-size:.95rem; margin-bottom:.35rem; }
.badge{
  display:inline-block; font-size:.75rem; padding:.15rem .5rem;
  border:1px solid var(--line); border-radius:999px; color:var(--muted); margin-right:.35rem;
}

/* Image wrapper gives consistent thumbnails and prevents odd aspect ratios */
.imgwrap{
  width:100%;
  aspect-ratio:16 / 9;
  overflow:hidden;
  border-radius:10px;
  border:1px solid var(--line);
  margin-bottom:.6rem;
}
.imgwrap img{
  width:100%;
  height:100%;
  object-fit:cover;
  display:block;
}

.actions a{
  display:inline-block; margin:.35rem .5rem .1rem 0; padding:.45rem .7rem;
  border:1px solid var(--line); border-radius:8px; text-decoration:none; color:var(--ink);
}
.actions a:hover{ background:rgba(0,0,0,.04); }
details summary{ cursor:pointer; font-weight:600; margin-top:.35rem; }
hr.section{ border:0; border-top:1px solid var(--line); margin:1.75rem 0 1rem; }

/* publication list */
.publist p{ margin:0 0 1rem; }
.publist em{ color:var(--muted); }

/* anchor link affordance */
h2{ position:relative; }
h2 a.anchor{ position:absolute; left:-1.25rem; opacity:0; text-decoration:none; color:var(--muted); }
h2:hover a.anchor{ opacity:.8; }
</style>

<div class="page-wrap">

# Research
<div class="lead">Selected work on development economics, education, and digital infrastructure.</div>

---

## <a class="anchor" href="#highlighted-papers">#</a>Highlighted Papers

<div class="grid">

  <!-- DHS Working Paper -->
  <div class="card" id="dhs-paper">
    <span class="kicker">Working Paper</span>
    <div class="imgwrap">
      <img src="{{ '/3G-coverage.png' | relative_url }}" alt="3G coverage map (Nigeria)" loading="lazy">
    </div>
    <h3>3G Network Expansion and Fertility Decisions in Nigeria</h3>
    <div class="meta">with Conner Mullally, Xinde Ji, Jared Gars · Presented: AAEA 2025; AEA 2026 (Scheduled)</div>
    <span class="badge">Staggered DiD</span>
    <span class="badge">Demography</span>
    <span class="badge">Digital Infrastructure</span>
    <div class="actions">
      <a href="https://www.dropbox.com/scl/fi/qji2by7izuma4aoylhh61/Broadband_and_Fertility_in_Nigeria-compressed.pdf?rlkey=flzoxw0uckk4h22sux8fs3hb7&dl=0">Full Draft (PDF)</a>
    </div>
    <details>
      <summary>Abstract</summary>
      <p>
      Using NDHS (2013–2018) matched to 3G coverage across 725 LGAs in a staggered rollout, a one-SD increase in coverage reduces birth probability among women aged 12–20 by 1.4–18 p.p. Effects differ by reproductive history: access delays first births but can increase subsequent fertility among young mothers. Mechanisms: delayed cohabitation/childbearing (not contraceptive uptake), higher high-skill employment, and stronger household bargaining power.
      </p>
    </details>
  </div>

  <!-- JMP -->
  <div class="card" id="jmp">
    <span class="kicker">Job Market Paper</span>
    <div class="imgwrap">
      <img src="{{ '/network-diagram.png' | relative_url }}" alt="Peer network diagram (boarders vs non-boarders)" loading="lazy">
    </div>
    <h3>Unintended Consequences of Best Intentions: Spillovers in Targeted Supplementary Education</h3>
    <div class="meta">with Conner Mullally and Yue Ma · Presented: AFE 2025 (Sched.), ASSA 2025, AAEA 2025, SEEDEC 2025, APPAM 2024</div>
    <span class="badge">Field Experiment</span>
    <span class="badge">Peer Effects</span>
    <span class="badge">Education</span>
    <div class="actions">
      <a href="https://www.dropbox.com/scl/fi/z1hparrh8ltcy1te3n7w1/Spillover_Effect.pdf?rlkey=5bcw0rvf4bmk1zjem7mh81mzd&st=1i97r34e&dl=0">Full Draft (PDF)</a>
    </div>
    <details>
      <summary>Abstract</summary>
      <p>
      Field experiment in 130 rural Chinese boarding schools compares CAL vs. workbook interventions. Workbook treatment generates negative spillovers on non-targeted peers—strongest along close peer ties—via motivational crowd-out from observing classmates receive extra resources. CAL (outside class) shows no such spillovers. Design matters in competitive, resource-limited settings.
      </p>
    </details>
  </div>

</div>

<hr class="section" />

## <a class="anchor" href="#publications">#</a>Publications

<div class="publist">

**Chen, Xuqi**, **Lisa House**, **Zhifeng Gao**, **Yujuan Gao** (2024).  
“Do Color-Coded Nutrition Facts Panels Nudge the Use of Nutrition Information on Food Packaging?” *Food Policy*  
[Full Draft](https://doi.org/10.1016/j.foodpol.2024.102730)

**Ma, Yue**, **Xinwu Zhang**, **Lucy Pappas**, **Andrew Rule**, **Yujuan Gao**, **Sarah-Eve Dill**, **Tianli Feng**, et al. (2023).  
“Associations between Urbanization and the Home Language Environment: Evidence from a LENA Study in Rural and Peri-urban China.” *Child Development*  
[Full Draft](https://doi.org/10.1111/cdev.14034)

**Yujuan Gao**, **Derek Hu**, **Even Peng**, et al. (2020).  
“Depressive Symptoms and the Link with Academic Performance among Rural Taiwanese Children.” *International Journal of Environmental Research and Public Health*  
[Full Draft](https://doi.org/10.3390/ijerph17082778)

**Ma, Yue**, **Yujuan Gao**, **Jason Li**, et al. (2020).  
“Maternal Health Behaviors during Pregnancy in Rural Northwestern China.” *BMC Pregnancy and Childbirth*  
[Full Draft](https://doi.org/10.1186/s12884-020-03444-3)

**Yujuan Gao**, **Yu Bai**, **Yue Ma**, et al. (2018).  
“Arrival Order for Positive and Negative Effects of Parental Migration on the Academic Performance of Left-behind Children in Rural China.” *Studies in Labor Economics* (in Chinese)

**Ma, Yue**, **Yujuan Gao**, **Wang, Yue**, et al. (2018).  
“Impact of a Local Vision Care Center on Glasses Ownership and Wearing Behavior in Northwestern Rural China: A Cluster-Randomized Controlled Trial.” *International Journal of Environmental Research and Public Health*  
[Full Draft](https://doi.org/10.3390/ijerph15122783)

</div>

<hr class="section" />

## <a class="anchor" href="#working-papers">#</a>Working Papers

**Friendship Formation and Peer Effect: Using Seat Distribution as an Instrument**  
with Yu Bai and Scott Rozelle  
[Full Draft](https://dx.doi.org/10.2139/ssrn.4828554)  
<em>Presented at: NEUDC 2023, PacDev 2024, AAEA 2024</em>

<details>
  <summary>Abstract</summary>
  <p>
  Using data on 2,956 primary students in rural China and an IV strategy based on seat assignment, study groups raise achievement by 0.11 SD—especially for males, lower performers, and cohesive groups. Intrinsic motivation mediates effects; optimizing spatial proximity is a cost-effective lever.
  </p>
</details>

**Overcoming Parenting Barriers in Under-Resourced Communities with “Tips-by-Text”**  
with Yue Ma  
[Full Draft](https://ssrn.com/abstract=4969618)  
<em>Presented at: AAEA 2022, China Education Finance Research Forum 2023</em>

<details>
  <summary>Abstract</summary>
  <p>
  RCT among 1,096 low-income mothers: large gains in parenting knowledge (ITT = 0.222 SD, p &lt; 0.01) and some stimulating practices; heterogeneous effects align with information gaps, inattention, and motivated cognition.
  </p>
</details>

<hr class="section" />

## <a class="anchor" href="#wip">#</a>Works in Progress

**Maternal Migration and Early Child Development in Rural China**  
with Yue Ma and Conner Mullally  
<em>Presented at: SAEA 2023, AAEA 2022, WEAI 2022</em>

<hr class="section" />

## <a class="anchor" href="#policy">#</a>Policy & Outreach

**Save the Children Yunnan Ludian Early Childhood Development Project (2019–2020) Evaluation Report**  
with Yu Bai

<hr class="section" />

## <a class="anchor" href="#ml">#</a>Machine Learning Project

**Traffic Sign Classification using Convolutional Neural Networks**  
with Thiago de Andrade, Rui Guo, Cody Haby  
[Full Draft](https://github.com/yujuangao/Traffic-Sign-Classification/blob/42f00a4368b9c8c077e67da9d23cdf4ce0ee18e0/ProjectReport_TRYC.pdf)

</div>
