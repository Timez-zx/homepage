---
layout: about
title: about
permalink: /
subtitle: Ph.D. Student in Computer Science, <a href='https://www.cs.utexas.edu/'>UT Austin</a> · Advised by <a href='https://daehyeok.kim'>Daehyeok Kim</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # replaced by the custom quick-links row below

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Ph.D. student in Computer Science at the University of Texas at Austin, advised by [Daehyeok Kim](https://daehyeok.kim). I work at the intersection of **networked/distributed systems** and **AI infrastructure**. My research spans datacenter networks, 5G and edge computing, and cross-layer telemetry, with a current focus on making AI workloads predictable and efficient—from the network fabric up to GPU resources. I build practical, measurement-driven systems that bridge real-world deployment with the infrastructure needs of modern AI.

<div class="quick-links">
  <a href="https://scholar.google.com/citations?user=yLJE1-kAAAAJ" target="_blank" rel="noopener noreferrer"><i class="ai ai-google-scholar"></i>Scholar</a>
  <a href="https://github.com/Timez-zx" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-github"></i>GitHub</a>
  <a href="mailto:zx123@utexas.edu"><i class="fa-solid fa-envelope"></i>Email</a>
</div>

<h2>research interests</h2>

<div class="tag-row">
  <span>Networked &amp; Distributed Systems</span>
  <span>AI Infrastructure</span>
  <span>Datacenter Networks</span>
  <span>5G &amp; Edge Computing</span>
  <span>Cross-layer Telemetry</span>
  <span>Resource Management</span>
</div>

<style>
  /* ---- Quick links (CV / Scholar / GitHub / Email) ---- */
  .quick-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin: 1.25rem 0 0.25rem;
  }
  .quick-links a {
    display: inline-flex;
    align-items: center;
    gap: 0.45rem;
    padding: 0.4rem 0.9rem;
    font-size: 0.9rem;
    font-weight: 500;
    line-height: 1;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    color: var(--global-text-color);
    transition:
      background-color 0.18s ease,
      color 0.18s ease,
      border-color 0.18s ease;
  }
  .quick-links a:hover {
    background-color: var(--global-theme-color);
    border-color: var(--global-theme-color);
    color: #fff;
    text-decoration: none;
  }

  /* ---- Unify all about-page section headings (research interests,
     news, selected publications) into one refined small-caps style ---- */
  .post h2 {
    font-size: 0.78rem;
    font-weight: 600;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--global-text-color-light);
    margin: 2rem 0 0.9rem;
  }
  .post h2 a {
    color: inherit;
  }

  /* ---- Research-interest tags ---- */
  .tag-row {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
  }
  .tag-row span {
    display: inline-block;
    padding: 0.32rem 0.8rem;
    font-size: 0.85rem;
    border-radius: 999px;
    color: var(--global-theme-color);
    border: 1px solid var(--global-theme-color);
    white-space: nowrap;
  }

  /* ---- Lift the profile photo so it aligns with the name, forming a
     cohesive hero block instead of floating below the heading ---- */
  @media (min-width: 576px) {
    .profile {
      margin-top: -5.5rem;
    }
  }
</style>
