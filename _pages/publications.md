---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
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
    flex: 0 0 36%;
    max-width: 36%;
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
    flex: 1 1 64%;
    max-width: 64%;
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

  .paper-box .paper-box-text p:first-child a:hover {
    color: #0f508f;
  }

  .paper-box .paper-box-text a,
  .paper-box .paper-box-text a:visited,
  .paper-box .paper-box-text a:active {
    color: #1460b3;
  }

  .paper-box .paper-box-text a:hover {
    color: #0f508f;
  }

  .paper-box .paper-box-text .pub-pending {
    color: #1460b3;
  }

  .paper-box .paper-box-text p:first-child .pub-pending {
    font-weight: 500;
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

  @media (max-width: 768px) {
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

<!-- SAFE-Hair -->
<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">NeurIPS2026</div>
      <img src="/images/pubs/SAFE-Hair.png" alt="SAFE-Hair" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><span class="pub-pending">SAFE-Hair: Scalp-Anchored Fields for Exportable Single-View Hair Reconstruction</span></p>
    <p><strong>Yucheng Wang</strong><sup>*</sup>, Zedong Wang<sup>*</sup>, Yuetong Wu, Yue Ma, Dan Xu <br></p>
    <p><span class="pub-pending">(Coming Soon!)</span> <br></p>
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
    <p><span class="pub-pending">Virtual Task Prompting for Multi-Task Scene Understanding</span></p>
    <p>Zedong Wang<sup>*</sup>, <strong>Yucheng Wang</strong><sup>*</sup>, Dan Xu <br></p>
    <p><span class="pub-pending">(Coming Soon!)</span> <br></p>
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
    <p><a href="https://arxiv.org/abs/2608.01771">[Paper]</a> <a href="https://github.com/mayuelala/LiveLight">[Code]</a> <a href="https://living-lighting.github.io/">[Project Page]</a> <br></p>
    <p>ACM Transactions on Graphics (TOG), 2026</p>
  </div>
</div>

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
    <p><a href="https://arxiv.org/abs/2603.08589">[Paper]</a> <a href="https://github.com/CARE-Edit/Code">[Code]</a> <a href="https://care-edit.github.io/">[Project Page]</a> <br></p>
    <p>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026</p>
  </div>
</div>

<!-- EasyVFX -->
<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">SIGGRAPH2026</div>
      <img src="/images/pubs/teaser_vfx.png" alt="EasyVFX" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><a href="https://arxiv.org/abs/2605.22051">EasyVFX: Frequency-Driven Decoupling for Resource-Efficient VFX Generation</a></p>
    <p>Yue Ma, Xu Ye, Qinghe Wang, <strong>Yucheng Wang</strong>, Hongyu Liu, Yinhan Zhang, Xinyu Wang, Yuanpeng Che, Shanhui Mo, Paul Liang, Fangneng Zhan, Qifeng Chen <br></p>
    <p><a href="https://arxiv.org/abs/2605.22051">[Paper]</a> <a href="https://github.com/mayuelala/EasyVFX">[Code]</a> <a href="https://easy-vfx.github.io/">[Project Page]</a> <br></p>
    <p>ACM SIGGRAPH Conference Proceedings (SIGGRAPH), 2026</p>
  </div>
</div>

<!-- Copart -->
<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">ICCV2025</div>
      <img src="/images/pubs/Copart.png" alt="Copart" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><a href="https://arxiv.org/abs/2507.08772">From One to More: Contextual Part Latents for 3D Generation</a></p>
    <p>Shaocong Dong<sup>*</sup>, Lihe Ding<sup>*</sup>, Xiao Chen, Yaokun Li, Yuxin Wang, <strong>Yucheng Wang</strong>, Qi Wang, Jaehyeok Kim, Chenjian Gao, Zhanpeng Huang, Zibin Wang, Tianfan Xue, Dan Xu <br></p>
    <p><a href="https://arxiv.org/abs/2507.08772">[Paper]</a> <a href="https://github.com/hkdsc/copart">[Code]</a> <a href="https://hkdsc.github.io/project/copart/">[Project Page]</a> <br></p>
    <p>IEEE/CVF International Conference on Computer Vision (ICCV), 2025</p>
  </div>
</div>

<!-- Controllable Video Generation Survey -->
<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">Survey</div>
      <img src="/images/pubs/CVGAS.png" alt="Controllable Video Generation" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><a href="https://arxiv.org/abs/2507.16869">Controllable Video Generation: A Survey</a></p>
    <p>Yue Ma<sup>*</sup>, Kunyu Feng<sup>*</sup>, Zhongyuan Hu<sup>*</sup>, Xinyu Wang<sup>*</sup>, <strong>Yucheng Wang</strong>, Mingzhe Zheng, Bingyuan Wang, Qinghe Wang, Xuanhua He, Hongfa Wang, Chenyang Zhu, Hongyu Liu, Yingqing He, Zeyu Wang, Zhifeng Li, Xiu Li, Sirui Han, Yike Guo, Wei Liu, Dan Xu, Linfeng Zhang, Qifeng Chen <br></p>
    <p><a href="https://arxiv.org/abs/2507.16869">[Paper]</a> <a href="https://github.com/mayuelala/Awesome-Controllable-Video-Generation">[Code]</a> <br></p>
    <p>Survey on controllable video generation (arXiv), 2025</p>
  </div>
</div>

<!-- MoDiT -->
<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">UG Thesis</div>
      <img src="/images/pubs/MoDiT.png" alt="MoDiT" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><a href="https://arxiv.org/abs/2507.05092">Learning Highly Consistent 3D Motion Coefficients with Diffusion Transformer for Talking Head Generation</a></p>
    <p><strong>Yucheng Wang</strong>, Dan Xu <br></p>
    <p><a href="https://arxiv.org/abs/2507.05092">[Paper]</a> <br></p>
    <p>Undergraduate Thesis, The Hong Kong University of Science and Technology (HKUST), 2025</p>
  </div>
</div>
