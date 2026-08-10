---
layout: page
title:
permalink: /
nav: true
---

<div style="
  max-width: 1180px;
  margin: 20px auto 70px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
">

  <!-- ================= HERO ================= -->

  <div style="
    display: grid;
    grid-template-columns: 250px 1fr;
    gap: 48px;
    align-items: center;
    padding: 34px 36px;
    margin-bottom: 28px;
    background: #ffffff;
    border: 1px solid #ececec;
    border-radius: 18px;
    box-shadow: 0 8px 28px rgba(0,0,0,0.045);
  ">

    <div style="text-align: center;">

      <img
        src="{{ '/assets/img/yuzhutao.jpg' | relative_url }}"
        alt="Portrait of Yuzhu Tao"
        style="
          width: 190px;
          height: 190px;
          object-fit: cover;
          border-radius: 14px;
          display: block;
          margin: 0 auto 18px;
        "
      >

      <div style="
        font-size: 28px;
        font-weight: 700;
        color: #1f2328;
        margin-bottom: 6px;
      ">
        Yuzhu Tao
      </div>

      <div style="
        font-size: 15px;
        color: #555;
        margin-bottom: 3px;
      ">
        M.Sc. Student in Artificial Intelligence
      </div>

      <div style="
        font-size: 15px;
        color: #555;
      ">
        Beijing Jiaotong University
      </div>

    </div>


    <div>

      <div style="
        font-size: 14px;
        font-weight: 600;
        letter-spacing: 0.08em;
        text-transform: uppercase;
        color: #777;
        margin-bottom: 8px;
      ">
        About Me
      </div>

      <h1 style="
        font-size: 36px;
        line-height: 1.2;
        margin: 0 0 20px;
        color: #1f2328;
        font-weight: 700;
      ">
        Exploring Visual Intelligence through
        Geometry and Generative Models.
      </h1>

      <p style="
        font-size: 16px;
        line-height: 1.75;
        color: #363b42;
        margin-bottom: 14px;
      ">
        I am <strong>Yuzhu Tao</strong>, a master's student in Artificial Intelligence
        at <strong>Beijing Jiaotong University</strong>.
      </p>

      <p style="
        font-size: 16px;
        line-height: 1.75;
        color: #363b42;
        margin-bottom: 14px;
      ">
        My research lies at the intersection of
        <strong>computer vision and multimodal intelligence</strong>,
        with particular interests in
        <strong>image generation and editing, panoramic reconstruction,
        image stitching, and multimodal large models</strong>.
      </p>

      <p style="
        font-size: 16px;
        line-height: 1.75;
        color: #363b42;
        margin-bottom: 22px;
      ">
        My recent work explores HDR panoramic reconstruction with spike cameras,
        robust image stitching under large parallax, and generative image editing
        with multimodal foundation models.
      </p>

      <div style="
        display: flex;
        gap: 10px;
        flex-wrap: wrap;
      ">

        <a
          href="mailto:taoyuzhu@bjtu.edu.cn"
          style="
            padding: 8px 14px;
            border: 1px solid #d9d9d9;
            border-radius: 8px;
            text-decoration: none;
            font-size: 14px;
          ">
          Email
        </a>

        <a
          href="https://scholar.google.com/citations?user=V3IxgpwAAAAJ"
          target="_blank"
          style="
            padding: 8px 14px;
            border: 1px solid #d9d9d9;
            border-radius: 8px;
            text-decoration: none;
            font-size: 14px;
          ">
          Google Scholar
        </a>

        <a
          href="https://github.com/Yuzhu-Tao"
          target="_blank"
          style="
            padding: 8px 14px;
            border: 1px solid #d9d9d9;
            border-radius: 8px;
            text-decoration: none;
            font-size: 14px;
          ">
          GitHub
        </a>

        <a
          href="{{ '/cv/' | relative_url }}"
          style="
            padding: 8px 14px;
            border: 1px solid #d9d9d9;
            border-radius: 8px;
            text-decoration: none;
            font-size: 14px;
          ">
          CV
        </a>

      </div>

    </div>

  </div>


  <!-- ================= FEATURED RESEARCH HEADER ================= -->

  <div style="
    display: flex;
    justify-content: space-between;
    align-items: end;
    margin: 46px 2px 18px;
  ">

    <div>
      <div style="
        font-size: 13px;
        color: #777;
        font-weight: 600;
        letter-spacing: 0.08em;
        text-transform: uppercase;
        margin-bottom: 4px;
      ">
        Research
      </div>

      <div style="
        font-size: 28px;
        font-weight: 700;
        color: #1f2328;
      ">
        Featured Work
      </div>
    </div>

    <a
      href="{{ '/publications/' | relative_url }}"
      style="
        text-decoration: none;
        font-size: 14px;
        font-weight: 600;
      ">
      View all publications →
    </a>

  </div>


  <!-- ================= PAPER 1 ================= -->

  <div style="
    display: grid;
    grid-template-columns: 44% 56%;
    overflow: hidden;
    margin-bottom: 22px;
    background: #ffffff;
    border: 1px solid #e9e9e9;
    border-radius: 18px;
    box-shadow: 0 8px 26px rgba(0,0,0,0.04);
  ">

    <div style="
      min-height: 270px;
      background: #f4f5f6;
      display: flex;
      align-items: center;
      justify-content: center;
    ">

      <img
        src="{{ '/assets/img/panorama.jpg' | relative_url }}"
        alt="Fast-Rotating Panoramic HDR Reconstruction"
        style="
          width: 100%;
          height: 100%;
          min-height: 270px;
          object-fit: cover;
          display: block;
        "
      >

    </div>


    <div style="
      padding: 30px 34px;
      display: flex;
      flex-direction: column;
      justify-content: center;
    ">

      <div style="
        display: inline-block;
        width: fit-content;
        padding: 4px 9px;
        margin-bottom: 12px;
        border-radius: 999px;
        background: #eef5ff;
        color: #2463b5;
        font-size: 12px;
        font-weight: 700;
      ">
        ACM MM 2026 · CCF-A
      </div>

      <div style="
        font-size: 23px;
        line-height: 1.35;
        font-weight: 700;
        color: #20242a;
        margin-bottom: 11px;
      ">
        Fast-Rotating Panoramic HDR Reconstruction from Single-Second Spikes
      </div>

      <div style="
        font-size: 13.5px;
        line-height: 1.6;
        color: #555d66;
        margin-bottom: 12px;
      ">
        <strong>Yuzhu Tao</strong>, Yakun Chang, Shikui Wei, Lang Nie,
        Qingwen Li, Bo Li, Boxin Shi, Yao Zhao
      </div>

      <div style="
        font-size: 15px;
        line-height: 1.7;
        color: #59616b;
        margin-bottom: 18px;
      ">
        Panoramic HDR reconstruction under fast rotation using spike imaging
        and multimodal generative modeling, enabling full-color HDR panorama
        recovery from single-second spike acquisition.
      </div>

      <div style="
        display: flex;
        gap: 10px;
        flex-wrap: wrap;
      ">

        <a
          href="{{ '/publications/' | relative_url }}"
          style="
            padding: 7px 12px;
            border-radius: 7px;
            border: 1px solid #d9d9d9;
            text-decoration: none;
            font-size: 13px;
          ">
          Paper
        </a>

        <a
          href="{{ '/projects/' | relative_url }}"
          style="
            padding: 7px 12px;
            border-radius: 7px;
            border: 1px solid #d9d9d9;
            text-decoration: none;
            font-size: 13px;
          ">
          Project
        </a>

        <a
          href="{{ '/projects/' | relative_url }}"
          style="
            padding: 7px 12px;
            border-radius: 7px;
            border: 1px solid #d9d9d9;
            text-decoration: none;
            font-size: 13px;
          ">
          Video Demo
        </a>

      </div>

    </div>

  </div>


  <!-- ================= PAPER 2 ================= -->

  <div style="
    display: grid;
    grid-template-columns: 44% 56%;
    overflow: hidden;
    margin-bottom: 44px;
    background: #ffffff;
    border: 1px solid #e9e9e9;
    border-radius: 18px;
    box-shadow: 0 8px 26px rgba(0,0,0,0.04);
  ">

    <div style="
      min-height: 270px;
      background: #f4f5f6;
      display: flex;
      align-items: center;
      justify-content: center;
    ">

      <img
        src="{{ '/assets/img/stitching.jpg' | relative_url }}"
        alt="Seam-Guided Image Stitching"
        style="
          width: 100%;
          height: 100%;
          min-height: 270px;
          object-fit: cover;
          display: block;
        "
      >

    </div>


    <div style="
      padding: 30px 34px;
      display: flex;
      flex-direction: column;
      justify-content: center;
    ">

      <div style="
        display: inline-block;
        width: fit-content;
        padding: 4px 9px;
        margin-bottom: 12px;
        border-radius: 999px;
        background: #f2f4f7;
        color: #525963;
        font-size: 12px;
        font-weight: 700;
      ">
        IEEE TCSVT 2026 · CCF-B
      </div>

      <div style="
        font-size: 23px;
        line-height: 1.35;
        font-weight: 700;
        color: #20242a;
        margin-bottom: 11px;
      ">
        Seam-Guided Unsupervised Image Stitching with Parallax-Aware Mask Generation
      </div>

      <div style="
        font-size: 13.5px;
        line-height: 1.6;
        color: #555d66;
        margin-bottom: 12px;
      ">
        <strong>Yuzhu Tao</strong>, Lang Nie, Yakun Chang, Bo Li,
        Qingwen Li, Hong Li, Shikui Wei
      </div>

      <div style="
        font-size: 15px;
        line-height: 1.7;
        color: #59616b;
        margin-bottom: 18px;
      ">
        A seam-guided iterative alignment framework with parallax-aware mask
        generation for robust image stitching in challenging large-parallax scenes.
      </div>

      <div>

        <a
          href="{{ '/publications/' | relative_url }}"
          style="
            display: inline-block;
            padding: 7px 12px;
            border-radius: 7px;
            border: 1px solid #d9d9d9;
            text-decoration: none;
            font-size: 13px;
          ">
          Paper
        </a>

      </div>

    </div>

  </div>


  <!-- ================= NEWS + HONORS ================= -->

  <div style="
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 22px;
    margin-bottom: 30px;
  ">

    <div style="
      padding: 26px 28px;
      border: 1px solid #ececec;
      border-radius: 16px;
      background: #ffffff;
    ">

      <div style="
        font-size: 20px;
        font-weight: 700;
        margin-bottom: 16px;
        color: #222;
      ">
        Recent News
      </div>

      <div style="
        font-size: 14.5px;
        line-height: 1.75;
        color: #505760;
      ">
        <strong>2026.03</strong> —
        Our paper on large-parallax image stitching was accepted for publication
        in IEEE TCSVT.
      </div>

      <div style="
        font-size: 14.5px;
        line-height: 1.75;
        color: #505760;
        margin-top: 10px;
      ">
        <strong>2026</strong> —
        Our work on fast-rotating panoramic HDR reconstruction was accepted
        to ACM Multimedia.
      </div>

    </div>


    <div style="
      padding: 26px 28px;
      border: 1px solid #ececec;
      border-radius: 16px;
      background: #ffffff;
    ">

      <div style="
        font-size: 20px;
        font-weight: 700;
        margin-bottom: 16px;
        color: #222;
      ">
        Selected Honors
      </div>

      <div style="
        font-size: 14.5px;
        line-height: 1.8;
        color: #505760;
      ">
        First-Class Scholarship for Academic Excellence, 2024 & 2025
        <br>
        Outstanding Student Leader, 2025
        <br>
        Outstanding Undergraduate Graduate of Hebei Province, 2024
      </div>

    </div>

  </div>

</div>
