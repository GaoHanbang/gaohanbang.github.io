---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.about-page { max-width: 820px; }

@keyframes aboutFade { from { opacity: 0; transform: translateY(14px); } to { opacity: 1; transform: none; } }
.about-hero, .about-stats, .about-links { animation: aboutFade 0.8s ease both; }
.about-stats { animation-delay: 0.15s; }
.about-links { animation-delay: 0.3s; }
@media (prefers-reduced-motion: reduce) {
  .about-hero, .about-stats, .about-links { animation: none; }
}

/* Hero */
.about-hero {
  border-left: 4px solid #2f6db5;
  padding: 4px 0 4px 16px;
  margin: 0.2em 0 1.2em;
}
.about-hero .lead {
  font-size: 1.45em;
  font-weight: 700;
  line-height: 1.25;
  color: #222;
}
.about-hero .sub {
  display: block;
  margin-top: 6px;
  font-size: 0.95em;
  color: #2f6db5;
  font-weight: 600;
}

/* Stats strip */
.about-stats {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin: 1.2em 0;
}
.about-stats .stat {
  flex: 1 1 130px;
  text-align: center;
  padding: 14px 10px;
  border: 1px solid #e6e6e6;
  border-radius: 10px;
  background: #fafafa;
}
.about-stats .stat .num {
  display: block; font-size: 1.5em; font-weight: 700; line-height: 1.1; color: #2f6db5;
}
.about-stats .stat .lab {
  display: block; font-size: 0.8em; color: #555; margin-top: 4px;
}

/* Quick links */
.about-links { display: flex; flex-wrap: wrap; gap: 10px; margin: 1em 0 1.6em; }
.about-links a {
  display: inline-block;
  padding: 9px 18px;
  border-radius: 8px;
  font-weight: 600;
  font-size: 0.92em;
  text-decoration: none;
  border: 1px solid #2f6db5;
  transition: background 0.18s, color 0.18s, transform 0.18s;
}
.about-links a.primary { background: #2f6db5; color: #fff; }
.about-links a.ghost { background: transparent; color: #2f6db5; }
.about-links a:hover { transform: translateY(-2px); }
.about-links a.primary:hover { background: #245a98; }
.about-links a.ghost:hover { background: #eef3fa; }

/* Vision highlight */
.about-vision {
  margin: 1.6em 0;
  padding: 20px 22px;
  background: #eef3fa;
  border-radius: 12px;
  border: 1px solid #d7e3f2;
}
.about-vision p { margin: 0; font-size: 1.12em; line-height: 1.5; color: #1f3d63; font-style: italic; }
.about-vision .q { font-weight: 700; font-style: normal; }
</style>

<div class="about-page" markdown="0">

<div class="about-hero">
  <span class="lead">Enabling large-scale robots to treat people as collaborators, not merely as safety concerns.</span>
  <span class="sub">Ph.D. candidate in robotics · École Centrale de Nantes · soon to be Dr. (July 2026)</span>
</div>

<div class="about-stats">
  <div class="stat"><span class="num">5</span><span class="lab">Publications &amp; preprints</span></div>
  <div class="stat"><span class="num">280 h</span><span class="lab">Teaching (FR / EN)</span></div>
  <div class="stat"><span class="num">July 2026</span><span class="lab">Thesis defense</span></div>
</div>

<div class="about-links">
  <a class="primary" href="{{ "/publications/" | relative_url }}">Research &amp; Publications</a>
  <a class="ghost" href="{{ "/teaching/" | relative_url }}">Teaching</a>
  <a class="ghost" href="{{ "/cv/" | relative_url }}">CV</a>
</div>

</div>

I am a Ph.D. candidate in robotics at [École Centrale de Nantes](https://www.ec-nantes.fr/english-version), conducting my research at the [Laboratoire des Sciences du Numérique de Nantes (LS2N)](https://www.ls2n.fr/annuaire/Hanbang%20GAO/). My doctoral thesis manuscript is complete and I will defend this July — soon to be Dr. Gao.

During my PhD, I have also completed 280 hours of [teaching]({{ "/teaching/" | relative_url }}) in both French and English, spanning mechanical design, computer science, and the simulation and experimental operation of robots. Since 1 September 2025, I have served as a Temporary Teaching and Research Associate (ATER) at [Nantes Université](https://www.univ-nantes.fr/hanbang-gao), teaching undergraduate and graduate engineering students with full responsibility from lectures to exams.

<div class="about-vision" markdown="0">
  <p><span class="q">How can robots be safer, smarter, and more controllable when they truly share space with people?</span> A robot should understand, distinguish, and respond to human physical contact — treating a person not as an obstacle to avoid, but as a collaborator to work with.</p>
</div>

This question drives my research. My doctoral work, *"Management of Physical Human–Robot Interaction in Cable-Driven Parallel Robots,"* supervised by Dr. [Stéphane Caro](https://scholar.google.fr/citations?user=IiBLzvgAAAAJ&hl=fr) and Dr. [Christine Chevallereau](https://scholar.google.com/citations?user=JzYkhbUAAAAJ&hl=en), pursues it in cable-driven parallel robots (CDPRs) — addressing both unintentional collisions and intentional collaboration, and combining model-based methods, signal processing, and learning-based approaches for robust contact detection, identification, and interaction management. You can read more on my [research and publications]({{ "/publications/" | relative_url }}) page.

I received my Bachelor of Engineering degree in Automation from Beijing Institute of Technology, and completed the European Advanced Robotics Master's programme at École Centrale de Nantes (2020–2022).

Outside academia, my interests include tennis, rock climbing, and reading. I am also a certified diver and polyglot.
