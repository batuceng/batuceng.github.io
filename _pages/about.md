---
permalink: /
title: "Hello there! 🖐️"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* Background gif styling */
  body::before {
    content: "";
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
    background: url('../files/xor.gif') center center fixed;
    background-size: cover;
    opacity: 0.1; /* Adjust transparency level (0.0 to 1.0) */
    pointer-events: none;
  }

  /* Make page content background slightly transparent */
  #main {
    background-color: rgba(255, 255, 255, 0.95); /* Adjust last value for content background transparency */
  }

  /* Existing research styles */
  .research-item {
    display: flex;
    align-items: flex-start;
    margin-bottom: 30px;
    flex-direction: row;
    gap: 20px;
  }
  .research-item img {
    flex: 0 0 20%;
    max-width: 20%;
    height: auto;
    border-radius: 4px;
    object-fit: cover;
  }
  .research-item div {
    flex: 1;
  }
  .research-item b {
    display: block;
    margin-bottom: 8px;
    font-size: 1.1em;
    line-height: 1.4;
  }
  .research-item span {
    font-size: 0.95em;
    line-height: 1.6;
  }

  /* Responsive styles */
  @media screen and (max-width: 768px) {
    .research-item {
      flex-direction: column;
    }
    .research-item img {
      flex: 0 0 100%;
      max-width: 100%;
      margin-bottom: 15px;
    }
    .research-item b {
      font-size: 1em;
    }
    .research-item span {
      font-size: 0.9em;
    }
  }

  @media screen and (max-width: 480px) {
    .research-item {
      margin-bottom: 25px;
    }
    .research-item b {
      font-size: 0.95em;
    }
    .research-item span {
      font-size: 0.85em;
    }
  }
</style>

Welcome to my homepage! My name is Batuhan Cengiz. I am a PhD Student and a Research Assistant at the [Istanbul Technical University](https://ituvisionlab.github.io/), supervised by [Gozde Unal](https://gozde-unal.github.io/). I have received my Bachelor's and Master's also from Istanbul Technical University. My main research is focused on 3D Vision, robustness, and generative models.

## Research

<ul>
  <li class="research-item">
    <img src="../images/eps_mesh_headman.png" alt="Research Image 1">
    <div>
      <b>&epsilon;-Mesh Attack: A Surface-based Adversarial Point Cloud Attack for Facial Expression Recognition</b>
      <span>
         <span style="font-weight:bold">Batuhan Cengiz</span>, Mert Gulsen, Yusuf H. Sahin, Gozde Unal<br>
        IEEE International Conference on Automatic Face and Gesture Recognition, 2024<br>
        <a href="https://arxiv.org/pdf/2403.06661">Paper</a>, <a href="https://github.com/batuceng/e-mesh-attack">Code</a>
      </span>
    </div>
  </li>
  <li class="research-item">
    <img src="../images/pcld-mainfig.png" alt="Research Image 2">
    <div>
      <b>PCLD: Point Cloud Layerwise Diffusion for Adversarial Purification</b>
      <span>
        Mert Gulsen, <span style="font-weight:bold">Batuhan Cengiz</span>, Yusuf H. Sahin, Gozde Unal<br>
        Arxiv (Accepted at IEEE ICIP), 2024<br>
        <a href="https://arxiv.org/pdf/2403.06698">Paper</a>, <a href="https://github.com/batuceng/diffusion-layer-robustness-pc">Code</a>
      </span>
    </div>
  </li>
  <li class="research-item">
    <img src="../images/3dunetr-mainfig.png" alt="Research Image 3">
    <div>
      <b>3D U-NetR: Low Dose Computed Tomography Reconstruction via Deep Learning and 3 Dimensional Convolutions</b>
      <span>
        Doga Gunduzalp*,  <span style="font-weight:bold">Batuhan Cengiz</span>*, Mehmet Ozan Unal, Isa Yildirim<br>
        Arxiv, 2021<br>
        *Denotes Equal Contribution<br>
        <a href="https://arxiv.org/pdf/2105.14130">Paper</a>, <a href="https://github.com/batuceng/3D_UNetR">Code</a>
      </span>
    </div>
  </li>
</ul>
