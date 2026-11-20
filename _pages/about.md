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
  <p>I'm a third-year Ph.D. student advised by <a href="https://www.danxurgb.net">Prof. Dan Xu</a> at The Hong Kong University of Science and Technology (<a href="https://hkust.edu.hk/">HKUST</a>). I earned my bachelor’s degree in Computer Science and Electronic Engineering from HKUST. I also spent a semester on exchange at <a href="https://ethz.ch/en.html">ETH Zurich</a>, where I was fortunate to work with <a href="https://insait.ai/dr-danda-paudel/">Prof. Danda Paudel</a> on 3D gaze estimation and eye modeling.</p>
  <p>My research lies in Generative AI, with a focus on <strong>Controllable</strong> and <strong>Efficient</strong> image/video generation. More recently, I have been increasingly interested in how such generative models can serve for <strong>Embodied Intelligence</strong>. Feel free to reach out for discussions and collaborations.</p>
</div>

<style>
  .cv-text {
    margin-bottom: 1.5em;
    font-size: 0.85rem;
    line-height: 1.6;
    color: #494e52;
  }

  .cv-text p {
    font-size: 0.85rem;
    line-height: 1.6;
    margin: 0 0 1em 0;
  }

  .news-list {
    font-size: 0.85rem;
    line-height: 1.6;
    color: #494e52;
  }

  .news-list ul {
    list-style: none;
    margin: 0;
    padding: 0;
  }

  .news-list li {
    margin: 0 0 0.45em 0;
    padding-left: 5.8em;
    text-indent: -5.8em;
    font-size: 0.85rem;
  }

  .news-list li > strong:first-child {
    display: inline-block;
    width: 5.8em;
    text-indent: 0;
    color: #1460b3;
    font-weight: 600;
  }

  .news-list:not(.expanded) li:nth-child(n+6) {
    display: none;
  }

  .news-toggle {
    margin: 0.2em 0 1.5em 5.8em;
    font-size: 0.85rem;
  }

  .news-toggle button {
    padding: 0;
    font-size: 0.8rem;
    font-weight: 600;
    color: #1460b3;
    background: none;
    border: none;
    cursor: pointer;
  }

  .news-toggle button:hover {
    color: #0f508f;
    text-decoration: underline;
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

  .tl-body .tl-title {
    display: block;
    font-weight: 700;
    font-size: 0.85rem;
    color: #2f3338;
  }

  .tl-body .tl-date {
    display: block;
    margin-top: 0.15em;
    font-size: 0.8rem;
    font-weight: 400;
    color: #7a8288;
  }

  .tl-body .tl-detail {
    display: block;
    margin-top: 0.2em;
    font-size: 0.85rem;
    color: #494e52;
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
    border-left: 3px solid #1460b3;
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
    color: #1460b3;
    font-weight: 600;
    font-style: normal;
    font-size: 0.85rem;
  }

  ul.section-reviewer > li em {
    display: inline-block;
    min-width: 3.4em;
    margin-right: 0.55em;
  }

  ul.section-courses > li em {
    min-width: 5.6em;
  }

  .paper-box {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    flex-direction: row;
    flex-wrap: nowrap;
    border-bottom: 1px solid #efefef;
    padding: 1.2em 0;
    gap: 0;
    clear: both;
  }

  .paper-box .paper-box-image {
    flex: 0 0 34%;
    max-width: 34%;
    justify-content: flex-start;
    display: flex;
    order: 1;
  }

  .paper-box .paper-box-image > div {
    position: relative;
    width: 100%;
    max-width: 400px;
  }

  .paper-box .paper-box-image img {
    display: block;
    width: 100%;
    max-width: 400px;
    height: auto;
    aspect-ratio: 2.15 / 1;
    box-shadow: 3px 3px 6px #888;
    object-fit: contain;
    background: #fff;
  }

  .paper-box .paper-box-text {
    flex: 1 1 66%;
    max-width: 66%;
    order: 2;
    padding-left: 1.5em;
    min-width: 0;
    font-size: 0.8125rem;
    line-height: 1.45;
    color: #494e52;
  }

  .paper-box .paper-box-text p {
    margin: 0 0 0.3rem 0;
  }

  .paper-box .paper-box-text p:first-child {
    font-size: 0.875rem;
    line-height: 1.3;
  }

  .paper-box .paper-box-text p:first-child a,
  .paper-box .paper-box-text p:first-child a:visited,
  .paper-box .paper-box-text p:first-child a:active {
    color: #1460b3;
    font-weight: 500;
  }

  .paper-box .paper-box-text p:first-child a {
    text-decoration: none;
  }

  .paper-box .paper-box-text p:first-child a:hover {
    color: #0f508f;
    text-decoration: underline;
  }

  .paper-box .paper-box-text p.pub-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4em;
    margin: 0.4rem 0 0.45rem 0;
  }

  .paper-box .paper-box-text p.pub-links a.pub-link,
  .paper-box .paper-box-text p.pub-links a.pub-link:visited {
    display: inline-flex;
    align-items: center;
    gap: 0.35em;
    padding: 0.12em 0.75em;
    font-size: 0.72rem;
    font-weight: 600;
    line-height: 1.6;
    color: #1460b3;
    background: #eef4fb;
    border: 1px solid #d4e3f5;
    border-radius: 999px;
    text-decoration: none;
    transition: background 0.2s ease, color 0.2s ease, border-color 0.2s ease;
  }

  .paper-box .paper-box-text p.pub-links a.pub-link:hover {
    color: #fff;
    background: #1460b3;
    border-color: #1460b3;
  }

  .paper-box .paper-box-text a,
  .paper-box .paper-box-text a:visited,
  .paper-box .paper-box-text a:active {
    color: #1460b3;
  }

  .paper-box .paper-box-text a:hover {
    color: #0f508f;
  }

  .paper-box .paper-box-text p:last-child {
    font-size: 0.75rem;
    color: #6a737d;
  }

  .paper-box .badge {
    padding-left: 1rem;
    padding-right: 1rem;
    position: absolute;
    margin-top: 0.5em;
    margin-left: -0.5em;
    color: #fff;
    background-color: #0d4da8;
    font-size: 0.8em;
    z-index: 1;
  }

  .paper-box .paper-box-text .pub-pending {
    color: #1460b3;
  }

  .paper-box .paper-box-text p:first-child .pub-pending {
    font-weight: 500;
  }

  .pubs-more {
    margin: 1.2em 0 1.5em 0;
    text-align: center;
  }

  .pubs-more a.pubs-more-btn,
  .pubs-more a.pubs-more-btn:visited {
    display: inline-block;
    padding: 0.45em 1.4em;
    font-size: 0.8125rem;
    font-weight: 600;
    color: #1460b3;
    border: 1.5px solid #1460b3;
    border-radius: 999px;
    text-decoration: none;
    transition: background 0.2s ease, color 0.2s ease;
  }

  .pubs-more a.pubs-more-btn:hover {
    color: #fff;
    background: #1460b3;
  }

  .visitor-map {
    width: 100%;
    max-width: 360px;
    margin: 0 auto 1.5em auto;
  }

  .visitor-map #mapmyvisitors-widget {
    border: 1px solid #e8e8e8;
    border-radius: 8px;
    overflow: hidden;
  }

  .visitor-map #clstminf {
    color: #7a8288 !important;
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

    .paper-box {
      flex-direction: column;
      align-items: flex-start;
    }

    .paper-box .paper-box-image,
    .paper-box .paper-box-text {
      flex: 1 1 100%;
      max-width: 100%;
      order: unset;
    }

    .paper-box .paper-box-text {
      padding-left: 0;
      padding-top: 1em;
    }
  }
</style>

## 🗞️ News

<div class="news-list" id="news-list">
  <ul>
    <li><strong>Sep 2026</strong>Two papers (SAFE-Hair and VTP) on <strong>3D Generation</strong> and <strong>Multi-task Learning</strong> accepted by NeurIPS 2026. Thanks to <a href="https://www.danxurgb.net">Prof. Dan Xu</a> for his great help and all coauthors. Appreciate the dedication of <a href="https://jacky1128.github.io/">Zedong Wang</a>!</li>
    <li><strong>Jul 2026</strong>One co-authored <a href="https://living-lighting.github.io/">paper</a> (<em>LiveLight</em>) on <strong>Video Relighting</strong> accepted by ACM TOG 2026. Appreciate the dedication of <a href="https://mayuelala.github.io/">Yue Ma</a>!</li>
    <li><strong>Mar 2026</strong>One <a href="https://care-edit.github.io/">paper</a> (<em>CARE-Edit</em>) on <strong>Image Editing</strong> accepted by CVPR 2026. Thanks to <a href="https://www.danxurgb.net">Prof. Dan Xu</a> for his great help and all coauthors. Appreciate the dedication of <a href="https://jacky1128.github.io/">Zedong Wang</a>!</li>
    <li><strong>Mar 2026</strong>One co-authored <a href="https://easy-vfx.github.io/">paper</a> (<em>EasyVFX</em>) on <strong>VFX Generation</strong> accepted by SIGGRAPH 2026. Appreciate the dedication of <a href="https://mayuelala.github.io/">Yue Ma</a>!</li>
    <li><strong>Aug 2025</strong>One co-authored survey on <strong>Controllable Video Generation</strong> released on <em><a href="https://arxiv.org/abs/2507.16869">arXiv</a></em>. Appreciate the dedication of <a href="https://mayuelala.github.io/">Yue Ma</a>!</li>
    <li><strong>Jul 2025</strong>One co-authored <a href="https://copart3d.github.io/">paper</a> (<em>CoPart</em>) on <strong>3D Generation</strong> accepted by ICCV 2025. Appreciate the dedication of <a href="https://hkdsc.github.io/">Shaocong Dong</a>!</li>
    <li><strong>Jul 2025</strong>One paper on <strong>Talking Head Generation</strong> released on <em><a href="https://arxiv.org/abs/2507.05092">arXiv</a></em>.</li>
    <li><strong>Jun 2024</strong>I’ve graduated from HKUST with the <a href="https://registry.hkust.edu.hk/academic-achievement-medal">Academic Achievement Medal</a>. Thank you all my mentors and friends!</li>
  </ul>
</div>
<div class="news-toggle">
  <button type="button" onclick="var l=document.getElementById('news-list');this.textContent=l.classList.toggle('expanded')?'Show less ↑':'Show more ↓';">Show more ↓</button>
</div>

## 📚 Selected Publications

<!-- CARE-Edit -->
<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">CVPR2026</div>
      <img src="/images/pubs/CARE-Edit.png" alt="CARE-Edit" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><a href="https://arxiv.org/abs/2603.08589">CARE-Edit: Condition-Aware Routing of Experts for Contextual Image Editing</a></p>
    <p><strong>Yucheng Wang</strong><sup>*</sup>, Zedong Wang<sup>*</sup>, Yuetong Wu, Yue Ma, Dan Xu <br></p>
    <p class="pub-links"><a class="pub-link" href="https://arxiv.org/abs/2603.08589"><i class="fas fa-file-alt" aria-hidden="true"></i>Paper</a> <a class="pub-link" href="https://github.com/CARE-Edit/Code"><i class="fab fa-github" aria-hidden="true"></i>Code</a> <a class="pub-link" href="https://care-edit.github.io/"><i class="fas fa-globe" aria-hidden="true"></i>Project Page</a></p>
    <p>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026</p>
  </div>
</div>

<!-- SAFE-Hair -->
<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">NeurIPS2026</div>
      <img src="/images/pubs/SAFE-Hair.png" alt="SAFE-Hair" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><a href="https://arxiv.org/abs/2611.12037">SAFE-Hair: Scalp-Anchored Fields for Exportable Single-View Hair Reconstruction</a></p>
    <p><strong>Yucheng Wang</strong><sup>*</sup>, Zedong Wang<sup>*</sup>, Yuetong Wu, Yue Ma, Dan Xu <br></p>
    <p class="pub-links"><a class="pub-link" href="https://arxiv.org/abs/2611.12037"><i class="fas fa-file-alt" aria-hidden="true"></i>Paper</a> <a class="pub-link" href="https://github.com/SAFE-Hair/Code"><i class="fab fa-github" aria-hidden="true"></i>Code</a> <a class="pub-link" href="https://safe-hair.github.io/"><i class="fas fa-globe" aria-hidden="true"></i>Project Page</a></p>
    <p>Conference on Neural Information Processing Systems (NeurIPS), 2026</p>
  </div>
</div>

<!-- VTP -->
<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">NeurIPS2026</div>
      <img src="/images/pubs/VTP.png" alt="VTP" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><a href="https://arxiv.org/abs/2611.11041">Virtual Task Prompting for Multi-Task Scene Understanding</a></p>
    <p>Zedong Wang<sup>*</sup>, <strong>Yucheng Wang</strong><sup>*</sup>, Dan Xu <br></p>
    <p class="pub-links"><a class="pub-link" href="https://arxiv.org/abs/2611.11041"><i class="fas fa-file-alt" aria-hidden="true"></i>Paper</a> <a class="pub-link" href="https://jacky1128.github.io/VTP/"><i class="fas fa-globe" aria-hidden="true"></i>Project Page</a></p>
    <p>Conference on Neural Information Processing Systems (NeurIPS), 2026</p>
  </div>
</div>

<!-- LiveLight -->
<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">TOG2026</div>
      <img src="/images/pubs/LiveLight.png" alt="LiveLight" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><a href="https://living-lighting.github.io/">LiveLight: Real-time Streaming Video Relighting with Interactive Control</a></p>
    <p>Yue Ma, Jiangming Wang, <strong>Yucheng Wang</strong>, Xilai Wang, Zhiyuan Li, Xinyu Wang, Hongyu Liu, Ruofan Liang, Songchun Zhang, Yuxuan Xue, Qifeng Chen <br></p>
    <p class="pub-links"><a class="pub-link" href="https://arxiv.org/abs/2608.01771"><i class="fas fa-file-alt" aria-hidden="true"></i>Paper</a> <a class="pub-link" href="https://github.com/mayuelala/LiveLight"><i class="fab fa-github" aria-hidden="true"></i>Code</a> <a class="pub-link" href="https://living-lighting.github.io/"><i class="fas fa-globe" aria-hidden="true"></i>Project Page</a></p>
    <p>ACM Transactions on Graphics (TOG), 2026</p>
  </div>
</div>

<div class="pubs-more">
  <a class="pubs-more-btn" href="/publications/">View Full Publication List →</a>
</div>

## 🎓 Education

<ul class="section-timeline">
  <li>
    <div class="tl-body">
      <span class="tl-title">The Hong Kong University of Science and Technology</span>
      <span class="tl-date">2024 - Present</span>
      <span class="tl-detail">Doctor of Philosophy, Computer Science</span>
    </div>
    <img class="tl-logo" src="/images/HKUST.png" alt="HKUST logo">
  </li>
  <li>
    <div class="tl-body">
      <span class="tl-title">ETH Zurich</span>
      <span class="tl-date">2023 Spring</span>
      <span class="tl-detail">Exchange student, Computer Science</span>
    </div>
    <img class="tl-logo" src="/images/ETH.png" alt="ETH Zurich logo">
  </li>
  <li>
    <div class="tl-body">
      <span class="tl-title">The Hong Kong University of Science and Technology</span>
      <span class="tl-date">2020 - 2024 with Academic Achievement Medal</span>
      <span class="tl-detail">Bachelor of Science, Computer Science</span>
      <span class="tl-detail">Bachelor of Engineering, Electronic Engineering (Double Major)</span>
    </div>
    <img class="tl-logo" src="/images/HKUST.png" alt="HKUST logo">
  </li>
</ul>

## 💼 Experience

<ul class="section-timeline">
  <!-- <li>
    <div class="tl-body">
      <span class="tl-title">Kling AI, Kuaishou Technology</span>
      <span class="tl-date">Jul 2026 - Present</span>
      <span class="tl-detail">Research Intern</span>
      <span class="tl-detail">Focus: Embodied AI</span>
    </div>
    <img class="tl-logo" src="/images/klingai_thumb.png" alt="Kling AI logo">
  </li> -->
  <li>
    <div class="tl-body">
      <span class="tl-title">SmartMore</span>
      <span class="tl-date">Nov 2023 - Jan 2024</span>
      <span class="tl-detail">Research Intern, Mentored by: <a href="https://julianjuaner.github.io/">Dr. Yuechen Zhang</a> and <a href="https://yukangchen.com/">Dr. Yukang Chen</a></span>
      <span class="tl-detail">Focus: Vision-Language Model</span>
    </div>
    <img class="tl-logo" src="/images/SmartMore.png" alt="SmartMore logo">
  </li>
  <li>
    <div class="tl-body">
      <span class="tl-title">Computer Vision Laboratory @ETH Zurich </span>
      <span class="tl-date">Aug 2023 - Nov 2023</span>
      <span class="tl-detail">Research Intern, Mentored by: <a href="https://insait.ai/dr-danda-paudel/">Prof. Danda Paudel</a></span>
      <span class="tl-detail">Focus: Generative Model</span>
    </div>
    <img class="tl-logo" src="/images/ETH.png" alt="ETH Zurich logo">
  </li>
  <!-- <li>
    <div class="tl-body">
      <span class="tl-title">Career Hackers @HKSTP</span>
      <span class="tl-date">Jun 2022 - Aug 2022</span>
      <span class="tl-detail">Backend Developer, Mentored by: <a href="https://www.linkedin.com/in/justin-wang-lap-tang-5523b9175/">Mr. Justin Tang</a></span>
      <span class="tl-detail">Focus: Amazon Web Services and APIs</span>
    </div>
    <img class="tl-logo" src="/images/CH.png" alt="Career Hackers logo">
  </li>-->
 </ul>

## 🎖 Selected Awards

<ul class="section-honors">
  <li><em>2024</em> &nbsp;&nbsp; Hong Kong PhD Fellowship Scheme</li>
  <!-- <li><em>2024</em> &nbsp;&nbsp; HKUST RedBird PhD Scholarship</li> -->
  <!-- <li><em>2024</em> &nbsp;&nbsp; HKUST Academic Achievement Medal</li> -->
  <!-- <li><em>2023</em> &nbsp;&nbsp; HKSAR Government Scholarship</li> -->
  <li><em>2023</em> &nbsp;&nbsp; HKSAR Government Scholarship Fund - Reaching Out Award</li>
  <!-- <li><em>2023</em> &nbsp;&nbsp; Lee Hysan Foundation Exchange Scholarship</li> -->
  <li><em>2022</em> &nbsp;&nbsp; HKSAR Government Scholarship</li>
  <li><em>2021</em> &nbsp;&nbsp; The Joseph Lau Luen Hung Charitable Trust Scholarship</li>
  <!-- <li><em>2018</em> &nbsp;&nbsp; Silver Medal in the 4th China Collegiate Programming Contest (CCPC) Northeast Region</li> -->
  <!-- <li><em>2018</em> &nbsp;&nbsp; First Prize in the 24th National Olympiad in Informatics in Provinces (NOIP)</li> -->
</ul>

## 👨‍🏫 Teaching Assistant

<ul class="section-honors section-reviewer section-courses">
  <li><em>COMP2012</em> Object-Oriented Programming and Data Structures</li>
  <li><em>COMP3211</em> Learning, Reasoning, and Decision Making in AI</li>
  <li><em>COMP5422</em> Deep 2D and 3D Visual Scene Understanding</li>
</ul>

## 📝 Journal Reviewer

<ul class="section-honors section-reviewer">
  <li><em>TPAMI</em> IEEE Transactions on Pattern Analysis and Machine Intelligence</li>
  <li><em>IJCV</em> International Journal of Computer Vision</li>
  <li><em>TIP</em> IEEE Transactions on Image Processing</li>
</ul>

## 👀 Visitors

<!-- <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=080808&w=240&t=tt&d=CegsBXipognXpkc6GUQVYl4fAAwYxrhfjHCiMaDQwvQ&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script> -->

<!-- <script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=080808&w=240&t=n&d=tWMV0ESM0d2eCob7phTG1oQYA4mFpXibjw5olYBqwYA&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script> -->

<div class="visitor-map">
  <script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=c5d0dc&w=a&t=tt&d=tWMV0ESM0d2eCob7phTG1oQYA4mFpXibjw5olYBqwYA&co=f6f8fa&cmo=1460b3&cmn=ff5353&ct=494e52'></script>
</div>
