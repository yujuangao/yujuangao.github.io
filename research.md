---
layout: page
title: Research
permalink: /research/
---

<!-- ===== Simple, clean, responsive styling ===== -->
<style>
:root{
  --bg:#ffffff;
  --ink:#111827;
  --muted:#6b7280;
  --line:#e5e7eb;
  --card:#ffffff;
  --accent:#2563eb;
}
@media (prefers-color-scheme: dark){
  :root{
    --bg:#0b0f19;
    --ink:#e5e7eb;
    --muted:#9ca3af;
    --line:#1f2937;
    --card:#0f1629;
    --accent:#60a5fa;
  }
}
.page-wrap { color: var(--ink); }
.lead { color: var(--muted); margin-top: .25rem; margin-bottom: 1.25rem; }
.kicker { letter-spacing: .08em; text-transform: uppercase; font-weight: 600; color: var(--muted); }

.grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1.25rem;
}
@media (min-width: 900px) {
  .grid { grid-template-columns: 1fr 1fr; }
}
.card {
  background: var(--card);
  border: 1px solid var(--line);
  border-radius: 14px;
  padding: 16px;
  box-shadow: 0 6px 16px rgba(0,0,0,.06);
}
.card h3 { margin: .4rem 0 .25rem; }
.meta { color: var(--muted); font-size: .95rem; margin-bottom: .35rem; }
.badge {
  display: inline-block; font-size: .75rem; padding: .15rem .5rem;
  border:1px solid var(--line); border-radius: 999px; color: var(--muted); margin-right:.35rem;
}
.img {
  width: 100%; border-radius: 10px; border: 1px solid var(--line); margin-bottom: .6rem;
}
.actions a {
  display:inline-block; margin: .35rem .5rem .1rem 0; padding: .45rem .7rem;
  border:1px solid var(--line); border-radius: 8px; text-decoration:none; color: var(--ink);
}
.actions a:hover { background: rgba(0,0,0,.04); }
details summary { cursor: pointer; font-weight: 600; margin-top: .35rem; }
hr.section { border: 0; border-top: 1px solid var(--line); margin: 1.75rem 0 1rem; }

/* publication list */
.publist p { margin: 0 0 1rem; }
.publist em { color: var(--muted); }

/* subtle anchor links for sections */
h2 { position: relative; }
h2 a.anchor {
  position: absolute; left: -1.25rem; opacity: 0; text-decoration: none; color: var(--muted);
}
h2:hover a.anchor { opacity: .8; }
</style>

<div class="page-wrap">

# Research
<div class="lead">Selected work on development economics, education, and digital infrastructure.</div>

---

## <a class="anchor" href="#highlighted-papers">#</a>Highlighted Papers

<div class="grid">

  <!-- DHS Working Paper (FIRST image: 3g_coverage.png) -->
  <div class="card" id="dhs-paper">
    <span class="kicker">Working Paper</span>
    <img class="img" src="/images/3g_coverage.png" alt="3G Coverage Map for Nigeria (NDHS)">
    <h3>3G Network Expansion and Fertility Decisions in Nigeria</h3>
    <div class="meta">with Conner Mullally, Xinde Ji, Jared Gars · Presented: AAEA 2025; AEA 2026 (Scheduled)</div>
    <span class="badge">Staggered DiD</span>
    <span class="badge">Demography</span>
    <span class="badge">Digital Infrastructure</span>
    <div class="actions">
      <a href="https://www.dropbox.com/scl/fi/qji2by7iz
