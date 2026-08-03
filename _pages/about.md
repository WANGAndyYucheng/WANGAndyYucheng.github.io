---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="cv-text">
  <p>I'm a second-year Ph.D. student advised by <a href="https://www.danxurgb.net">Prof. Dan Xu</a> at The Hong Kong University of Science and Technology (<a href="https://hkust.edu.hk/">HKUST</a>). I earned my bachelor’s degree in Computer Science and Electronic Engineering from HKUST. I also spent a semester on exchange at <a href="https://ethz.ch/en.html">ETH Zurich</a>, where I was fortunate to work with <a href="https://insait.ai/dr-danda-paudel/">Dr. Danda Paudel</a> on 3D gaze estimation and eye modeling.</p>
  <p>My research lies in Generative AI, with a focus on <strong>Controllable</strong> and <strong>Efficient</strong> image/video generation. More recently, I have been increasingly interested in how such generative models can serve for <strong>Embodied Intelligence</strong>. Feel free to reach out for discussions and collaborations.</p>
</div>

<style>
  .cv-text {
    margin-bottom: 1.5em;
    font-size: 0.85rem;
    line-height: 1.6;
    color: #494e52;
  }

  .cv-line {
    margin: 0.3em 0;
  }

  .cv-text p {
    font-size: 0.85rem;
    line-height: 1.6;
    margin: 0 0 1em 0;
  }

  .news-scroll {
    max-height: 300px;
    overflow-y: auto;
    padding-right: 70px;
    font-size: 0.85rem;
    line-height: 1.6;
    color: #494e52;
  }

  .news-scroll li {
    margin: 0.3em 0;
    font-size: 0.85rem;
  }

  /* Timeline (Education / Internship) — franklinz-style + logos */
  ul.section-timeline {
    list-style: none;
    padding-left: 0;
    margin: 0 0 1.5em 0;
    position: relative;
    font-size: 0.85rem;
    line-height: 1.6;
    color: #494e52;
  }

  ul.section-timeline::before {
    content: '';
    position: absolute;
    left: 0;
    top: 0.35em;
    bottom: 0.35em;
    width: 2px;
    background: linear-gradient(180deg, #1460b3 0%, #0f508f 100%);
  }

  ul.section-timeline > li {
    position: relative;
    display: flex;
    align-items: flex-start;
    gap: 1.25em;
    padding: 0 0 1.35em 2.5em;
    margin: 0 0 0.35em 0;
    border-bottom: 1px solid #e8e8e8;
  }

  ul.section-timeline > li:last-child {
    border-bottom: none;
    margin-bottom: 0;
    padding-bottom: 0.25em;
  }

  ul.section-timeline > li::before {
    content: '';
    position: absolute;
    left: -6px;
    top: 0.35em;
    width: 14px;
    height: 14px;
    border-radius: 50%;
    background: #1460b3;
    border: 3px solid #fff;
    box-shadow: 0 0 0 2px #1460b3;
    z-index: 1;
  }

  .tl-body {
    flex: 1 1 auto;
    min-width: 0;
    font-size: 0.85rem;
    line-height: 1.55;
    color: #494e52;
  }

  .tl-body .tl-date {
    display: block;
    font-weight: 700;
    color: #2f3338;
    margin-bottom: 0.2em;
  }

  .tl-logo {
    flex: 0 0 75px;
    align-self: center;
    width: 75px;
    height: 75px;
    object-fit: contain;
  }

  ul.section-honors {
    list-style: none;
    padding-left: 0;
    margin: 0 0 1.5em 0;
    font-size: 0.85rem;
    line-height: 1.6;
    color: #494e52;
  }

  ul.section-honors > li {
    background: #fafafa;
    padding: 0.75em 1.1em;
    margin: 0 0 0.55em 0;
    border-radius: 6px;
    border-left: 3px solid #c9a227;
    font-size: 0.85rem;
    transition: background 0.2s ease, border-left-width 0.2s ease;
  }

  ul.section-honors > li:last-child {
    margin-bottom: 0;
  }

  ul.section-honors > li:hover {
    background: #f5f5f5;
    border-left-width: 4px;
  }

  ul.section-honors > li em {
    color: #a8891f;
    font-weight: 600;
    font-style: normal;
    font-size: 0.85rem;
  }

  @media (max-width: 768px) {
    ul.section-timeline > li {
      gap: 0.9em;
      padding-bottom: 1.1em;
    }

    .tl-logo {
      flex-basis: 48px;
      width: 48px;
      height: 48px;
    }
  }
</style>

## 🗞️ News

<div class="news-scroll">
  <ul>
    <li><strong>Jul 2026</strong>: One co-authored <a href="https://living-lighting.github.io/">paper</a> (<em>LiveLight</em>) on <strong>Video Relighting</strong> accepted by ACM TOG 2026. Appreciate the dedication of <a href="https://mayuelala.github.io/">Yue Ma</a>!</li>
    <li><strong>Mar 2026</strong>: One <a href="https://care-edit.github.io/">paper</a> (<em>CARE-Edit</em>) on <strong>Image Editing</strong> accepted by CVPR 2026. Thanks to <a href="https://www.danxurgb.net">Prof. Dan Xu</a> for his great help and all coauthors. Appreciate the dedication of <a href="https://jacky1128.github.io/">Zedong Wang</a>!</li>
    <li><strong>Mar 2026</strong>: One co-authored <a href="https://easy-vfx.github.io/">paper</a> (<em>EasyVFX</em>) on <strong>VFX Generation</strong> accepted by SIGGRAPH 2026. Appreciate the dedication of <a href="https://mayuelala.github.io/">Yue Ma</a>!</li>
    <li><strong>Aug 2025</strong>: One co-authored survey on <strong>Controllable Video Generation</strong> released on <em><a href="https://arxiv.org/abs/2507.16869">arXiv</a></em>. Appreciate the dedication of <a href="https://mayuelala.github.io/">Yue Ma</a>!</li>
    <li><strong>Jul 2025</strong>: One co-authored <a href="https://copart3d.github.io/">paper</a> (<em>CoPart</em>) on <strong>3D Generation</strong> accepted by ICCV 2025. Appreciate the dedication of <a href="https://hkdsc.github.io/">Shaocong Dong</a>!</li>
    <li><strong>Jul 2025</strong>: One paper on <strong>Talking Head Generation</strong> released on <em><a href="https://arxiv.org/abs/2507.05092">arXiv</a></em>.</li>
    <li><strong>Sep 2024</strong>: I’ve started my Ph.D. in Computer Science at HKUST advised by <a href="https://www.danxurgb.net">Prof. Dan Xu</a>.</li>
    <li><strong>Jun 2024</strong>: I’ve graduated from HKUST with the <a href="https://registry.hkust.edu.hk/academic-achievement-medal">Academic Achievement Medal</a>. Thank you all my mentors and friends!</li>
  </ul>
</div>

## 🎓 Education

<ul class="section-timeline">
  <li>
    <div class="tl-body">
      <span class="tl-date">2024 - Present</span>
      <strong>Doctor of Philosophy, Computer Science</strong> - The Hong Kong University of Science and Technology
    </div>
    <img class="tl-logo" src="/images/HKUST.png" alt="HKUST logo">
  </li>
  <li>
    <div class="tl-body">
      <span class="tl-date">2020 - 2024</span>
      <strong>Bachelor of Science, Computer Science</strong> &amp; <strong>Bachelor of Engineering, Electronic Engineering</strong> (Double Major) - The Hong Kong University of Science and Technology
    </div>
    <img class="tl-logo" src="/images/HKUST.png" alt="HKUST logo">
  </li>
  <li>
    <div class="tl-body">
      <span class="tl-date">2023 Spring</span>
      <strong>Exchange student, Computer Science</strong> - ETH Zurich
    </div>
    <img class="tl-logo" src="/images/ETH.png" alt="ETH Zurich logo">
  </li>
</ul>

## 💼 Internship

<ul class="section-timeline">
  <!-- <li>
    <div class="tl-body">
      <span class="tl-date">Jul 2026 - Present</span>
      <strong>Research Intern</strong> - Kling AI, Kuaishou Technology<br>
      Research included: Embodied AI
    </div>
    <img class="tl-logo" src="/images/klingai_thumb.png" alt="Kling AI logo">
  </li> -->
  <li>
    <div class="tl-body">
      <span class="tl-date">Nov 2023 - Jan 2024</span>
      <strong>Research Intern</strong> - SmartMore<br>
      Mentored by: <a href="https://julianjuaner.github.io/">Dr. Yuechen Zhang</a> and <a href="https://yukangchen.com/">Dr. Yukang Chen</a><br>
      Research included: Vision-Language Model
    </div>
    <img class="tl-logo" src="/images/SmartMore.png" alt="SmartMore logo">
  </li>
  <li>
    <div class="tl-body">
      <span class="tl-date">Jun 2022 - Aug 2022</span>
      <strong>Backend Developer</strong> - Career Hackers @HKSTP<br>
      Mentored by: <a href="https://www.linkedin.com/in/justin-wang-lap-tang-5523b9175/">Mr. Justin Tang</a><br>
      Work included: Web Service and API
    </div>
    <img class="tl-logo" src="/images/CH.png" alt="Career Hackers logo">
  </li>
</ul>

## 🎖 Honors and Awards

<ul class="section-honors">
  <li><em>2024</em> &nbsp;&nbsp; Hong Kong PhD Fellowship Scheme</li>
  <li><em>2024</em> &nbsp;&nbsp; HKUST RedBird PhD Scholarship</li>
  <li><em>2024</em> &nbsp;&nbsp; HKUST Academic Achievement Medal</li>
  <li><em>2022</em> &nbsp;&nbsp; HKSAR Government Scholarship</li>
  <li><em>2023</em> &nbsp;&nbsp; HKSAR Government Scholarship Fund - Reaching Out Award</li>
  <li><em>2021</em> &nbsp;&nbsp; The Joseph Lau Luen Hung Charitable Trust Scholarship</li>
</ul>

## 👨‍🏫 Teaching Assistant

<div class="cv-text">
  <div class="cv-line">Deep 2D and 3D Visual Scene Understanding, 2025-2026 Spring</div>
  <div class="cv-line">Object-Oriented Programming and Data Structures, 2024-2025 Spring</div>
</div>

## 📝 Reviewer

<div class="cv-text">
  <div class="cv-line">International Journal of Computer Vision (IJCV)</div>
</div>

## 👀 Visitors

<!-- <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=080808&w=240&t=tt&d=CegsBXipognXpkc6GUQVYl4fAAwYxrhfjHCiMaDQwvQ&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script> -->

<script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=080808&w=240&t=n&d=tWMV0ESM0d2eCob7phTG1oQYA4mFpXibjw5olYBqwYA&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script>
