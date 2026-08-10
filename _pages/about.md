---
layout: page
title: about
permalink: /
nav: true
nav_order: 1
---

<div style="
  display: grid;
  grid-template-columns: minmax(0, 1fr) 255px;
  gap: 46px;
  align-items: start;
  max-width: 1120px;
  margin: 20px auto 60px;
">

  <!-- ================= LEFT CONTENT ================= -->
  <div>


    <!-- About Me -->
    <section style="margin-bottom: 42px;">

      <h2 style="
        font-size: 28px;
        font-weight: 700;
        margin-bottom: 20px;
      ">
        About Me
      </h2>

      <p style="
        font-size: 16px;
        line-height: 1.75;
        margin-bottom: 15px;
      ">
        I am <strong>Yuzhu Tao</strong>, a master's student in Artificial Intelligence
        at <strong>Beijing Jiaotong University</strong>.
      </p>

      <p style="
        font-size: 16px;
        line-height: 1.75;
        margin-bottom: 15px;
      ">
        My research lies at the intersection of
        <strong>computer vision and multimodal intelligence</strong>.
        I am particularly interested in
        <strong>image generation and editing, panoramic reconstruction,
        image stitching, and multimodal large models</strong>.
      </p>

      <p style="
        font-size: 16px;
        line-height: 1.75;
        margin-bottom: 0;
      ">
        My recent work explores HDR panoramic reconstruction with spike cameras,
        robust image stitching under large parallax, and generative image editing
        with multimodal foundation models.
      </p>

    </section>


    <!-- News -->
    <section style="margin-bottom: 42px;">

      <h2 style="
        font-size: 24px;
        font-weight: 700;
        margin-bottom: 18px;
      ">
        News
      </h2>

      <div style="
        border-left: 3px solid #e5e7eb;
        padding-left: 18px;
      ">

        <p style="
          margin: 0 0 12px;
          font-size: 15px;
          line-height: 1.65;
        ">
          <strong>2026.03</strong>
          &nbsp; Our paper,
          <em>Seam-Guided Unsupervised Image Stitching With Parallax-Aware Mask Generation</em>,
          has been accepted for publication in IEEE TCSVT.
        </p>

        <p style="
          margin: 0;
          font-size: 15px;
          line-height: 1.65;
        ">
          <strong>2026</strong>
          &nbsp; Our paper,
          <em>Fast-Rotating Panoramic HDR Reconstruction from Single-Second Spikes</em>,
          has been accepted to ACM Multimedia.
        </p>

      </div>

    </section>


    <!-- Selected Publications -->
    <section style="margin-bottom: 44px;">

      <div style="
        display: flex;
        justify-content: space-between;
        align-items: baseline;
        margin-bottom: 20px;
      ">

        <h2 style="
          font-size: 24px;
          font-weight: 700;
          margin: 0;
        ">
          Selected Publications
        </h2>

        <a
          href="{{ '/publications/' | relative_url }}"
          style="
            font-size: 14px;
            font-weight: 600;
            text-decoration: none;
          ">
          View all publications →
        </a>

      </div>


      <!-- Publication 1 -->
      <div style="
        display: grid;
        grid-template-columns: 180px minmax(0,1fr);
        gap: 24px;
        padding: 20px;
        margin-bottom: 18px;
        border: 1px solid #ececec;
        border-radius: 14px;
        background: #ffffff;
        box-shadow: 0 4px 14px rgba(0,0,0,0.035);
      ">

        <img
          src="{{ '/assets/img/panorama.jpg' | relative_url }}"
          alt="Fast-Rotating Panoramic HDR Reconstruction"
          style="
            width: 180px;
            height: 120px;
            object-fit: cover;
            border-radius: 8px;
          "
        >

        <div>

          <div style="
            font-size: 18px;
            font-weight: 700;
            line-height: 1.4;
            margin-bottom: 7px;
          ">
            Fast-Rotating Panoramic HDR Reconstruction from Single-Second Spikes
          </div>

          <div style="
            font-size: 13.5px;
            line-height: 1.55;
            margin-bottom: 6px;
          ">
            <strong>Yuzhu Tao</strong>, Yakun Chang, Shikui Wei, Lang Nie,
            Qingwen Li, Bo Li, Boxin Shi, Yao Zhao
          </div>

          <div style="
            font-size: 13.5px;
            font-style: italic;
            margin-bottom: 8px;
          ">
            ACM Multimedia (CCF-A), 2026
          </div>

          <div style="
            font-size: 14px;
            line-height: 1.6;
            color: #666;
            margin-bottom: 8px;
          ">
            HDR panoramic reconstruction under fast rotation using spike imaging
            and multimodal generative modeling.
          </div>

          <div style="font-size: 13.5px;">
            <a href="{{ '/publications/' | relative_url }}">[Paper]</a>
            <a href="{{ '/projects/' | relative_url }}">[Project]</a>
            <a href="{{ '/projects/' | relative_url }}">[Video]</a>
          </div>

        </div>

      </div>


      <!-- Publication 2 -->
      <div style="
        display: grid;
        grid-template-columns: 180px minmax(0,1fr);
        gap: 24px;
        padding: 20px;
        border: 1px solid #ececec;
        border-radius: 14px;
        background: #ffffff;
        box-shadow: 0 4px 14px rgba(0,0,0,0.035);
      ">

        <img
          src="{{ '/assets/img/stitching.jpg' | relative_url }}"
          alt="Seam-Guided Image Stitching"
          style="
            width: 180px;
            height: 120px;
            object-fit: cover;
            border-radius: 8px;
          "
        >

        <div>

          <div style="
            font-size: 18px;
            font-weight: 700;
            line-height: 1.4;
            margin-bottom: 7px;
          ">
            Seam-Guided Unsupervised Image Stitching with Parallax-Aware Mask Generation
          </div>

          <div style="
            font-size: 13.5px;
            line-height: 1.55;
            margin-bottom: 6px;
          ">
            <strong>Yuzhu Tao</strong>, Lang Nie, Yakun Chang, Bo Li,
            Qingwen Li, Hong Li, Shikui Wei
          </div>

          <div style="
            font-size: 13.5px;
            font-style: italic;
            margin-bottom: 8px;
          ">
            IEEE TCSVT (CCF-B), 2026
          </div>

          <div style="
            font-size: 14px;
            line-height: 1.6;
            color: #666;
            margin-bottom: 8px;
          ">
            Robust image stitching for challenging large-parallax scenes
            using seam-guided alignment and parallax-aware mask generation.
          </div>

          <div style="font-size: 13.5px;">
            <a href="{{ '/publications/' | relative_url }}">[Paper]</a>
          </div>

        </div>

      </div>

    </section>


    <!-- Honors -->
    <section style="
      padding: 24px 26px;
      border: 1px solid #ececec;
      border-radius: 14px;
      background: #ffffff;
      margin-bottom: 20px;
    ">

      <h2 style="
        font-size: 22px;
        font-weight: 700;
        margin: 0 0 16px;
      ">
        Honors & Awards
      </h2>

      <div style="
        font-size: 14.5px;
        line-height: 1.9;
      ">
        Outstanding Undergraduate Graduate of Hebei Province, 2024<br>
        First-Class Scholarship for Academic Excellence, 2024 & 2025<br>
        Outstanding Student Leader, Beijing Jiaotong University, 2025
      </div>

    </section>

  </div>


  <!-- ================= RIGHT PROFILE ================= -->
  <aside style="
    border: 1px solid #ececec;
    border-radius: 16px;
    background: #ffffff;
    padding: 18px 18px 22px;
    text-align: center;
    box-shadow: 0 5px 18px rgba(0,0,0,0.045);
  ">

    <img
      src="{{ '/assets/img/yuzhutao.jpg' | relative_url }}"
      alt="Portrait of Yuzhu Tao"
      style="
        width: 100%;
        height: 330px;
        object-fit: cover;
        object-position: center top;
        border-radius: 10px;
        display: block;
        margin-bottom: 18px;
      "
    >

    <div style="
      font-size: 25px;
      font-weight: 700;
      margin-bottom: 8px;
    ">
      Yuzhu Tao
    </div>

    <div style="
      font-size: 14px;
      line-height: 1.6;
      margin-bottom: 3px;
    ">
      M.Sc. Student
    </div>

    <div style="
      font-size: 14px;
      line-height: 1.6;
      margin-bottom: 3px;
    ">
      Beijing Jiaotong University
    </div>

    <div style="
      font-size: 13.5px;
      margin: 6px 0 15px;
    ">
      <a href="mailto:taoyuzhu@bjtu.edu.cn">
        taoyuzhu@bjtu.edu.cn
      </a>
    </div>

    <div style="
      display: flex;
      justify-content: center;
      gap: 15px;
      font-size: 14px;
      flex-wrap: wrap;
    ">
      <a href="https://github.com/Yuzhu-Tao" target="_blank">GitHub</a>
      <a href="https://scholar.google.com/citations?user=V3IxgpwAAAAJ" target="_blank">Scholar</a>
      <a href="{{ '/cv/' | relative_url }}">CV</a>
    </div>

  </aside>

</div>
