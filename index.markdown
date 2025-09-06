---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<main>
  <!-- HERO -->
  <section class="hero hero-split" aria-label="Intro">
    <div class="hero-body">
      <p class="eyebrow">Bonjour · Servus · Vanakkam</p>
      <h1 class="title">I’m Lalith — Postdoctoral Researcher at CAMMA, IHU Strasbourg &amp; University of Strasbourg.</h1>
      <p class="lede">My mission is to build the next generation of safe and interpretable AI systems for surgery by combining modern computer vision with real‑world surgical data.</p>
      <p class="cta only-inline">
        <a class="inline" href="mailto:reach.lalith@gmail.com">Get in touch →</a>
      </p>
    </div>
    <div class="hero-media big-right">
      <img class="avatar cover" src="/assets/lalith-potrait-circular.jpg" alt="Portrait of Lalith"/>
    </div>
  </section>

<style>
  .hero-split {
    display: grid;
    grid-template-columns: 1fr 200px; /* always text + image side by side */
    align-items: center;
    gap: 20px;
    max-width: var(--maxw);
    margin: 0 auto 32px;
  }

  .hero.hero-split .hero-media { 
    order: 2; 
    justify-self: end; 
    text-align: right; 
    margin-top: -10px;              /* nudge upward */
  }

  .hero.hero-split .avatar.cover {
    width: clamp(150px, 24vw, 260px);  /* slightly bigger + responsive */
    height: auto;
    border-radius: 50%;
    box-shadow: 0 4px 18px rgba(0,0,0,.2);
    animation: float 6s ease-in-out infinite;
  }

  @keyframes float {
    0%   { transform: translateY(0px); }
    50%  { transform: translateY(-12px); }
    100% { transform: translateY(0px); }
  }

  @media (min-width: 980px) and (max-width: 1440px) {
    .title { font-size: clamp(1.35rem, 1.0rem + 1.0vw, 1.8rem); }
    .lede  { font-size: 1.0rem; }
    .hero.hero-split .hero-media { margin-top: -18px; } /* nudge image up */
    .hero.hero-split .hero-body  { align-self: start; }
  }

  /* Responsive tweak for small screens */
  @media (max-width: 640px) {
    .hero-split {
      grid-template-columns: 1fr;   /* stack on small screens */
      text-align: center;
    }
    .hero-split .hero-media {
      text-align: center;           /* center image on small screens */
    }
  }
</style>

  <!-- WHAT I DO -->
  <section class="section" aria-labelledby="what">
    <h2 id="what" class="h2">What I do</h2>
    <p class="body">I work with large‑scale, real‑world, heterogenous surgical data to build models designed to:</p>
    <ul class="bullets" role="list">
      <li>Operate across centres, procedures, and devices.</li>
      <li>Use vision–language pretraining & foundation models tailored to surgical video semantics.</li>
      <li>Detect rare but critical intra‑operative events.</li>
      <li>Enable safe and human-in-the loop decision support.</li>
    </ul>
  </section>

  <!-- CURRENT FOCUS -->
  <section class="section" aria-labelledby="focus">
    <h2 id="focus" class="h2">Current focus</h2>
    <ul class="chips" role="list">
      <li>Rare event detection</li>
      <li>Action anticipation</li>
      <li>Temporal event localization</li>
      <li>Surgical foundation models</li>
      <li>Vision–language pretraining</li>
    </ul>
  </section>

  <!-- TRACK RECORD -->
  <section class="section" aria-labelledby="track">
    <h2 id="track" class="h2">Track record</h2>
    <ul class="stats" role="list" aria-label="Career highlights">
      <li><span class="num">15+ publications</span> in high-impact journals and conferences (IEEE JBHI, MICCAI, EJCTS, Annals of Thoracis Surgery)</li>
      <li><span class="num">Reviewer</span> CVPR · NeurIPS · MICCAI · IEEE TMI · MedIA</li>
      <li><span class="num">4×</span> poster awards</li>
      <li><span class="num">8+</span> projects mentored</li>
    </ul>
  </section>

  <!-- COMMUNICATION -->
  <section class="section" aria-labelledby="beyond">
    <h2 id="beyond" class="h2">Beyond the lab</h2>
    <p>Scientists shouldn’t be hermits. I’m a passionate <a href="/talks/" target="_blank" rel="noopener">science communicator</a> and <a href="/teaching/" target="_blank" rel="noopener">educator</a> with 100+ hours of teaching. Through science slams across Germany, I’ve shared my work with an audience of 5,000+, earning 3× best slam awards and 2× semi‑final nominations at the German Science Slam Championships.</p>
  </section>

  <!-- COMMUNICATION -->
  <section class="section" aria-labelledby="news">
  <h2 class="h2">News</h2>
  <ul class="news-list" aria-label="Latest updates">
    <li>
      <time datetime="2025-07">Jul 2025</time>
      <p>I joined the <strong>CAMMA Group, IHU Strasbourg as a Postdoctoral researcher</strong>, where I will be working on CompSURG, an ERC-funded project for large-scale multi-centric multi-pocedural surgical video analysis.</p>
    </li>
    <li>
      <time datetime="2024-10">Oct 2024</time>
      <p><span class="news-title">I successfully defended my doctoral degree (Dr. sc. hum.) and graduated from Heidelberg University. My cumulative dissertation titled <strong>Deep learning based image analysis for endoscopic minimally invasive mitral valve repair was awarded the highest grade of <i>summa cum laude</i></strong></span>.</p>
    </li>
    <li>
      <time datetime="2024-06">Jun 2024</time>
      <p><span class="news-title">I delivered two science slams: in Heidelberg (🥇 first place) and Mainz (🥇 shared first place).</span></p>
    </li>
  </ul>
  </section>
</main>

<style>
  :root {
    --bg: #ffffff;
    --text: #0a0a0a;
    --muted: #6b7280; /* gray-500 */
    --link: #0f62fe;  /* IBM blue-ish */
    --surface: #f6f7f9; /* subtle section bg */
    --maxw: 46rem; /* ~736px */
    --radius: 10px;
  }

  html { -webkit-text-size-adjust: 100%; color-scheme: light; }
  body {
    margin: 0; background: var(--bg); color: var(--text);
    font: 16px/1.6 system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
    text-rendering: optimizeLegibility; -webkit-font-smoothing: antialiased; font-feature-settings: "kern" 1, "liga" 1;
  }

  .site-header, .site-footer { padding: 16px 20px; }
  .nav { max-width: var(--maxw); margin: 0 auto; display:flex; align-items:center; justify-content:space-between; gap: 16px; }
  .brand { font-weight: 700; letter-spacing: .2px; color: inherit; text-decoration: none; }
  .nav-links { display: flex; flex-wrap: wrap; gap: 12px; }
  .nav a { color: inherit; text-decoration: none; opacity: .9; }
  .nav a:hover { opacity: 1; text-decoration: underline; text-underline-offset: 2px; }

  main { padding: 24px 20px 56px; }
  .hero { max-width: var(--maxw); margin: 0 auto 20px; text-align: left; }
  .avatar { width: 96px; height: 96px; border-radius: 50%; display:block; margin: 0 0 12px; }
  .eyebrow { color: var(--muted); font-size: 1rem; margin: 0 0 6px; }
  .title { font-size: clamp(1.4rem, 1.2rem + 1.2vw, 2rem); line-height: 1.25; margin: 0 0 10px; }
  .lede { font-size: 1.05rem; margin: 0 0 14px; }
  .cta { display:flex; flex-wrap: wrap; gap: 10px; align-items:center; }
  .cta.only-inline { gap: 0; }
  .btn { display:inline-block; padding: 8px 12px; border-radius: 8px; background: var(--text); color: var(--bg); text-decoration:none; font-weight:600; }
  .btn:hover { filter: brightness(0.95); }
  .btn.ghost { background: transparent; color: inherit; border: 1px solid currentColor; }
  .inline { text-decoration: none; color: var(--link); font-weight: 600; }
  .inline:hover { text-decoration: underline; text-underline-offset: 2px; }

  .section { max-width: var(--maxw); margin: 24px auto 0; padding: 16px; border-radius: var(--radius); background: transparent; }
   .section + .section { margin-top: 12px; }

  /* Stronger section headers for consistency */
  .h2 { 
    font-size: 1.15rem; 
    font-weight: 700;               /* make headings bolder */
    letter-spacing: .01em; 
    margin: 0 0 10px; 
  }
  .body { margin: 0 0 8px; }

  .chips { display:flex; flex-wrap:wrap; gap:8px; padding:0; margin: 8px 0 0; list-style:none; }
  .chips li { padding: 6px 10px; border: 1px solid color-mix(in oklab, var(--text) 12%, transparent); border-radius: 999px; font-size: .95rem; }

  .bullets { padding-left: 1.1rem; margin: 8px 0 0; }
  .bullets li { margin: 6px 0; }
    /* De-bold the bullet highlights */
  .bullets strong { 
    font-weight: 400;                 /* normal weight */
    color: inherit;                   /* keep same color; no shouty emphasis */
}

  .stats { display:grid; grid-template-columns: 1fr; gap: 6px; padding:0; margin: 8px 0 0; list-style:none; }
  .stats .num { font-weight: 700; margin-right: 6px; }
  @media (min-width: 720px) {

  /* Single column stats with neat baseline alignment */
  .stats { 
    display: grid; 
    grid-template-columns: 1fr; 
    gap: 8px; 
  }
  .stats li { 
    display: flex; 
    align-items: baseline; 
    gap: 8px; 
    line-height: 1.4;
  }
  .stats .num { 
    font-weight: 700; 
    white-space: nowrap; 
  }

  .site-footer { border-top: 1px solid color-mix(in oklab, var(--text) 10%, transparent); }
  .foot-links { max-width: var(--maxw); margin: 0 auto; display:flex; flex-wrap:wrap; gap: 12px; opacity:.9; }
  .foot-links a { color: inherit; text-decoration: none; }
  .foot-links a:hover { text-decoration: underline; text-underline-offset: 2px; }

  /* Responsive refinement */
  @media (min-width: 840px) {
    .avatar { grid-row: 1 / span 3; }
    .eyebrow { margin-top: 6px; }
  }

  /* Motion reduced */
  @media (prefers-reduced-motion: no-preference) {
    .hero, .section { animation: fade .35s ease both; }
    @keyframes fade { from { opacity: 0; transform: translateY(4px); } to { opacity: 1; transform: translateY(0); } }
  }

  @media (min-width: 980px) and (max-width: 1440px) {
    .title { font-size: clamp(1.35rem, 1.0rem + 1.0vw, 1.8rem); }
    .lede  { font-size: 1.0rem; }
    .hero.hero-split .hero-media { margin-top: -18px; } /* nudge image up */
    .hero.hero-split .hero-body  { align-self: start; } /* align to top line */
  }

  /* --- News = like the screenshot --- */
.news-list {
  list-style: none;
  margin: 12px 0 0;
  padding: 0;
  display: grid;
  gap: 18px;                       /* more breathing room */
}

.news-list li {
  display: grid;
  grid-template-columns: 8ch 1fr;  /* tidy date column | text */
  align-items: start;
  gap: 16px;
}

.news-list time {
  color: var(--text);
  font-weight: 400;
  letter-spacing: .01em;
  white-space: nowrap;
}

.news-list p {
  margin: 0;
  font-size: 0.9rem;
  line-height: 1.65;
}

/* auto-mute everything except the latest (first) item */
.news-list li:not(:first-child) p { color: var(--muted); }

/* keep important title bold and dark inside muted paragraphs */
.news-list .news-title {
  color: var(--text);
  font-weight: 400;
}

/* Mobile: stack date above text */
@media (max-width: 560px) {
  .news-list li { grid-template-columns: 1fr; }
  .news-list time { margin-bottom: 2px; }
}

</style>

<a href="https://www.linkedin.com/in/lalithnag/" target="_blank">
<img src="/assets/icons8-linkedin-24.png" alt="LinkedIn" style="width: 24px; height: 24px; vertical-align: middle;">
</a> 
<a href="https://x.com/onyourseat" target="_blank">
<img src="/assets/icons8-twitter-24.png" alt="Twitter" style="width: 24px; height: 24px; vertical-align: middle;">
</a>
<a href="https://github.com/lalithnag" target="_blank">
<img src="/assets/icons8-github-24.png" alt="Github" style="width: 24px; height: 24px; vertical-align: middle;">
</a>
<a href="https://scholar.google.com/citations?hl=en&user=bdLgSAgAAAAJ&scilu=&scisig=ANI4uE0AAAAAZsDJsV5LhxdZ4Nn1sc5rzTXhTyc&gmla=AC6lMd-O5fQvrmRRJkS2sKL_vLX_zEk80gZiRtiDRNE0mi2fUEYRxsLYM6K6lt8NihQg5ttVXYE_TSWYnC1D5PCAh2RuUSJP9QQ0WsDi6Ho&sciund=3223323255075413780" target="_blank">
<img src="/assets/icons8-google-scholar-24.png" alt="Google Scholar" style="width: 24px; height: 24px; vertical-align: middle;">
</a>
<a href="https://orcid.org/0000-0003-0835-042X" target="_blank">
<img src="/assets/icons8-orcid-32.png" alt="OrcID" style="width: 24px; height: 24px; vertical-align: middle;">
</a>