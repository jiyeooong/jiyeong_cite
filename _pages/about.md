---
layout: about
title: about
permalink: /
subtitle: Integrated M.S./Ph.D. Student, <a href='http://cvl.ewha.ac.kr/'>Computer Vision Lab</a>, Ewha Womans University.

selected_papers: false # publications are shown directly on the homepage below
social: false # bottom social row disabled; social links live in the hero card below

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  /* Hide al-folio's default page header and right-aligned profile;
     we render a custom hero card instead. */
  .post .post-header { display: none; }
  .profile.float-right { display: none; }

  .hero {
    position: relative;
    display: grid;
    grid-template-columns: auto 1fr;
    gap: 1.5rem 2.25rem;
    align-items: stretch;
    background: var(--global-card-bg-color);
    border: 1px solid var(--global-divider-color);
    border-radius: 26px;
    padding: 2.25rem 2.5rem;
    box-shadow: 0 18px 45px rgba(0, 0, 0, 0.09);
    margin: 0.5rem 0 2.75rem;
    overflow: hidden;
  }
  .hero::before {
    content: "";
    position: absolute;
    top: -70px;
    right: -70px;
    width: 240px;
    height: 240px;
    background: radial-gradient(circle, rgba(96, 178, 168, 0.18), transparent 70%);
    pointer-events: none;
  }

  .hero-left {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
    gap: 1.1rem;
    position: relative;
    z-index: 1;
  }
  .hero-photo {
    width: 155px;
    height: 155px;
    object-fit: cover;
    border-radius: 22px;
    box-shadow: 0 8px 22px rgba(0, 0, 0, 0.14);
    display: block;
  }
  .hero-name {
    font-size: 2.05rem;
    font-weight: 800;
    line-height: 1.1;
    margin: 0;
    color: var(--global-text-color);
  }

  .hero-right {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    gap: 1.4rem;
    min-width: 0;
    position: relative;
    z-index: 1;
  }
  .hero-bio {
    font-size: 1.05rem;
    line-height: 1.65;
    margin: 0;
    color: var(--global-text-color);
  }
  .hero-socials {
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem;
    align-items: center;
  }
  .hero-socials a {
    display: inline-flex;
    align-items: center;
    gap: 0.45rem;
    color: var(--global-text-color);
    font-weight: 600;
    text-decoration: none;
    transition: color 0.15s ease;
  }
  .hero-socials a:hover { color: var(--global-theme-color); }
  .hero-socials i { font-size: 1.15rem; }

  @media (max-width: 640px) {
    .hero {
      grid-template-columns: 1fr;
      text-align: center;
      padding: 1.9rem 1.5rem;
    }
    .hero-left { align-items: center; }
    .hero-socials { justify-content: center; }
  }
</style>

<div class="hero">
  <div class="hero-left">
    <img class="hero-photo" src="{{ '/assets/img/jiyeong_profile.jpg' | relative_url }}?v=2" alt="Jiyeong Kim">
    <h1 class="hero-name">Jiyeong Kim</h1>
  </div>
  <div class="hero-right">
    <p class="hero-bio">
      Hi! I am an Integrated M.S./Ph.D. student at the <a href="http://cvl.ewha.ac.kr/">Computer Vision Lab</a>, Ewha Womans University, advised by Prof. Dongbo Min. My research interests include unified multimodal models, generative models, video understanding, and model efficiency. Currently, I am working on unified multimodal models that both understand and generate, with a focus on personalizing them to individual concepts.
    </p>
    <div class="hero-socials">
      <a href="mailto:wldud8946@gmail.com" title="Email"><i class="fa-solid fa-envelope"></i> Email</a>
      <a href="https://scholar.google.com/citations?user=qoJn8AcAAAAJ" target="_blank" rel="noopener" title="Google Scholar"><i class="ai ai-google-scholar"></i> Scholar</a>
      <a href="https://github.com/jiyeooong" target="_blank" rel="noopener" title="GitHub"><i class="fa-brands fa-github"></i> GitHub</a>
      <a href="https://www.linkedin.com/in/jiyeong-kim-a93b48378/" target="_blank" rel="noopener" title="LinkedIn"><i class="fa-brands fa-linkedin-in"></i> LinkedIn</a>
    </div>
  </div>
</div>

<div class="clearfix"></div>

<div class="publications">

<h2 class="bibliography">Conference &amp; Preprint</h2>
{% bibliography --query @*[category=conference] %}

<h2 class="bibliography">Journal</h2>
{% bibliography --query @*[category=journal] %}

</div>
