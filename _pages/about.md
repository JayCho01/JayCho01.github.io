---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.section-sep { border: none; border-top: 1px solid #ccc; margin: 48px 0; }
.pub { display:flex; align-items:flex-start; gap:20px; margin-bottom:32px; flex-wrap:wrap; }
.pub-thumb { width:300px; flex-shrink:0; margin-top:6px; }
.pub-thumb img { width:100%; border-radius:4px; }
.pub-title { color:#003566; font-weight:700; }
.entry { display:grid; grid-template-columns:1fr 150px; gap:2px 22px; align-items:start; padding:12px 0; border-bottom:1px solid #f0f0f0; }
.entry:last-of-type { border-bottom:none; }
.entry-date { white-space:nowrap; color:#666; font-size:0.85em; text-align:right; }
.note { color:#777; font-size:0.85em; }
.links { margin-top:8px; }
.links a { display:inline-block; padding:3px 12px; margin:4px 6px 0 0; border-radius:5px; background:#5b8bc2; color:#fff; font-size:0.82em; font-weight:600; text-decoration:none; border:1px solid #5b8bc2; }
.links a:hover { background:#3f6fa6; border-color:#3f6fa6; }
.tag { display:inline-block; padding:1px 9px; border-radius:4px; background:#ffe2a8; color:#8a5300; font-size:0.78em; font-weight:700; letter-spacing:0.2px; }
@media (max-width: 600px) {
  .pub-thumb { width:100%; }
  .entry { grid-template-columns:1fr; gap:4px; }
  .entry-date { text-align:left; }
}
</style>

I am an M.S. student in Robotics at Dongguk University, Korea, in the [Interactive Robotics Lab](http://irobot.dgu.edu/) advised by Professor Soo-Chul Lim.

My research focuses on **reinforcement learning and imitation learning for robotic manipulation**, with an emphasis on closing the **sim-to-real gap** — building high-fidelity digital twins, collecting data through humanoid teleoperation, and deploying learned policies on real robots.

**Research interests:** Humanoid Manipulation · Sim-to-Real Transfer · Imitation Learning (Diffusion Policy) · Digital Twin / XR · Dexterous Hand Manipulation · Multi-modal Learning

<hr class="section-sep">

## Publications

<div class="pub">
  <div>
    <span class="pub-title">Pixel2Catch: Multi-Agent Sim-to-Real Transfer for Agile Manipulation with a Single RGB Camera</span><br>
    Seongyong Kim, <b>Junhyeon Cho</b>, Kang-Won Lee, Soo-Chul Lim<br>
    <i>IEEE Robotics and Automation Letters (RA-L), 2026 (Accepted)</i>
    <div class="links">
      <a href="https://seongdrgn.github.io/pixel2catch/" target="_blank">Project Page</a>
      <a href="https://www.youtube.com/watch?v=kV10T-2zh5w" target="_blank">Video</a>
    </div>
  </div>
</div>

<hr class="section-sep">

## Research Projects

<div class="entry">
  <div>
    <b>Isaac Lab — RBY1 Left-Arm Pick &amp; Place (Joint-space Diffusion Policy)</b><br>
    Built a full pipeline (Record → Replay → Annotate → Generate → Train → Play) collecting and augmenting RBY1 left-arm teleoperation demos with Isaac Lab + Robomimic, training a joint-space Diffusion Policy, and replaying it in simulation.
    <div class="links">
      <a href="https://github.com/JayCho01/tv" target="_blank">GitHub</a>
    </div>
  </div>
  <div class="entry-date">2025 – Present</div>
</div>

<div class="entry">
  <div>
    <b>XR-based Human–Manipulator Co-manipulation Data Generation (4-year proposal)</b><br>
    Participated in a 4-year research proposal on generating human co-manipulation data with XR and digital twins for Physical AI, targeting high-difficulty manipulation (e.g., logistics packing). Collaboration with KITECH, SIMES, Dongguk University, and CJ Logistics.
  </div>
  <div class="entry-date">2026 – </div>
</div>

<div class="entry">
  <div>
    <b>SimReady Dataset / Sim-to-Real</b><br>
    Construction and validation of simulation-ready datasets, studying domain randomization and other techniques to mitigate the sim-to-real gap for legged-robot and manipulation tasks.
  </div>
  <div class="entry-date">2025</div>
</div>

<hr class="section-sep">

## Awards

<div class="entry">
  <div>First Prize (Grand Prize), <i>2024 AIoT Creative Integrated Design Competition</i>, Dongguk University Center for Engineering Education Innovation</div>
  <div class="entry-date">Nov 2024</div>
</div>

<div class="entry">
  <div>Minister's Award, <i>2024 Creative Integrated Design Competition</i>, Ministry of Trade, Industry and Energy (MOTIE)</div>
  <div class="entry-date">Nov 2024</div>
</div>

<div class="entry">
  <div>3rd Place, <i>10th 2024 R-BIZ Challenge</i>, Korean Agency for Technology and Standards (KATS)</div>
  <div class="entry-date">Oct 2024</div>
</div>

<hr class="section-sep">

## Technical Blog

<div class="entry">
  <div>
    Physical AI 개발의 가장 큰 벽: Sim-to-Real Gap의 원인과 극복 방법
    <div class="links">
      <a href="https://medium.com/@jayinkr01" target="_blank">Read on Medium</a>
    </div>
  </div>
  <div class="entry-date">Medium</div>
</div>

<div class="entry">
  <div>
    로봇은 어떻게 배울까? 강화학습과 모방학습
    <div class="links">
      <a href="https://medium.com/@jayinkr01" target="_blank">Read on Medium</a>
    </div>
  </div>
  <div class="entry-date">Medium</div>
</div>
