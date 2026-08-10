---
layout: page
title: about
permalink: /
nav: true
nav_order: 1
---

<div style="
  max-width: 1380px;
  width: 96%;
  margin: 24px auto 70px;
  display: grid;
  grid-template-columns: minmax(0, 1fr) 320px;
  gap: 64px;
  align-items: start;
">

  <!-- ================= LEFT CONTENT ================= -->
  <div style="min-width: 0;">


    <!-- ================= ABOUT ================= -->
    <section style="margin-bottom: 46px;">

      <h2 style="
        margin: 0 0 22px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
        font-size: 30px;
        line-height: 1.2;
        font-weight: 700;
        letter-spacing: -0.02em;
        color: #202124;
      ">
        About Me
      </h2>

      <p style="
        margin: 0 0 14px;
        font-family: Georgia, 'Times New Roman', serif;
        font-size: 18px;
        line-height: 1.52;
        color: #181818;
      ">
        I am <strong>Yuzhu Tao</strong>, a master's student in Artificial Intelligence at
        <a href="https://www.bjtu.edu.cn/"
           target="_blank"
           style="color:#0645ad; text-decoration:none;">
          Beijing Jiaotong University
        </a>.
      </p>

      <p style="
        margin: 0 0 14px;
        font-family: Georgia, 'Times New Roman', serif;
        font-size: 18px;
        line-height: 1.52;
        color: #181818;
      ">
        My research lies at the intersection of
        <strong>computer vision and multimodal intelligence</strong>,
        with particular interests in image generation and editing,
        panoramic reconstruction, image stitching, and multimodal large models.
      </p>

      <p style="
        margin: 0;
        font-family: Georgia, 'Times New Roman', serif;
        font-size: 18px;
        line-height: 1.52;
        color: #181818;
      ">
        My recent work explores HDR panoramic reconstruction with spike cameras,
        robust image stitching under large parallax, and generative image editing
        with multimodal foundation models.
      </p>

    </section>


    <!-- ================= NEWS ================= -->
    <section style="margin-bottom: 48px;">

      <h2 style="
        margin: 0 0 18px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
        font-size: 25px;
        font-weight: 700;
        color: #202124;
      ">
        News
      </h2>

      <div style="
        border-left: 3px solid #dfe3e8;
        padding-left: 20px;
      ">

        <p style="
          margin: 0 0 13px;
          font-family: Georgia, 'Times New Roman', serif;
          font-size: 16.5px;
          line-height: 1.5;
          color: #222;
        ">
          <strong>2026.03</strong>
          &nbsp; Our paper,
          <em>Seam-Guided Unsupervised Image Stitching With Parallax-Aware Mask Generation</em>,
          has been accepted for publication in
          <strong>IEEE TCSVT</strong>.
        </p>

        <p style="
          margin: 0;
          font-family: Georgia, 'Times New Roman', serif;
          font-size: 16.5px;
          line-height: 1.5;
          color: #222;
        ">
          <strong>2026</strong>
          &nbsp; Our paper,
          <em>Fast-Rotating Panoramic HDR Reconstruction from Single-Second Spikes</em>,
          has been accepted to
          <strong>ACM Multimedia</strong>.
        </p>

      </div>

    </section>


    <!-- ================= SELECTED PUBLICATIONS ================= -->
    <section style="margin-bottom: 48px;">

      <div style="
        display: flex;
        justify-content: space-between;
        align-items: baseline;
        gap: 20px;
        margin-bottom: 22px;
      ">

        <h2 style="
          margin: 0;
          font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
          font-size: 25px;
          font-weight: 700;
          color: #202124;
        ">
          Selected Publications
        </h2>

        <a
          href="{{ '/publications/' | relative_url }}"
          style="
            flex-shrink: 0;
            font-size: 14.5px;
            font-weight: 600;
            text-decoration: none;
          ">
          View all publications →
        </a>

      </div>


      <!-- ================= PAPER 1 ================= -->
      <div style="
        display: grid;
        grid-template-columns: 250px minmax(0, 1fr);
        gap: 28px;
        padding: 24px;
        margin-bottom: 20px;
        border: 1px solid #e7e9ec;
        border-radius: 15px;
        background: #ffffff;
        box-shadow: 0 4px 16px rgba(0,0,0,0.035);
      ">

        <div style="
          width: 250px;
          height: 165px;
          overflow: hidden;
          border-radius: 9px;
          background: #f3f4f5;
        ">
          <img
            src="{{ '/assets/img/panoramic.jpg' | relative_url }}"
            alt="Fast-Rotating Panoramic HDR Reconstruction"
            style="
              width: 100%;
              height: 100%;
              display: block;
              object-fit: cover;
            "
          >
        </div>

        <div style="min-width: 0;">

          <div style="
            margin-bottom: 8px;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
            font-size: 20px;
            line-height: 1.35;
            font-weight: 700;
            color: #1f2328;
          ">
            Fast-Rotating Panoramic HDR Reconstruction from Single-Second Spikes
          </div>

          <div style="
            margin-bottom: 6px;
            font-family: Georgia, 'Times New Roman', serif;
            font-size: 14.5px;
            line-height: 1.5;
            color: #262626;
          ">
            <strong>Yuzhu Tao</strong>, Yakun Chang, Shikui Wei, Lang Nie,
            Qingwen Li, Bo Li, Boxin Shi, Yao Zhao
          </div>

          <div style="
            margin-bottom: 9px;
            font-family: Georgia, 'Times New Roman', serif;
            font-size: 14px;
            line-height: 1.45;
            font-style: italic;
            color: #333;
          ">
            ACM Multimedia (CCF-A), 2026
          </div>

          <div style="
            margin-bottom: 10px;
            font-family: Georgia, 'Times New Roman', serif;
            font-size: 15.5px;
            line-height: 1.52;
            color: #555;
          ">
            HDR panoramic reconstruction under fast rotation using spike imaging
            and multimodal generative modeling.
          </div>

          <div style="
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
            font-size: 14px;
          ">
            <a href="{{ '/publications/' | relative_url }}">[Paper]</a>
            &nbsp;
            <a href="{{ '/projects/' | relative_url }}">[Project]</a>
            &nbsp;
            <a href="{{ '/projects/' | relative_url }}">[Video]</a>
          </div>

        </div>

      </div>


      <!-- ================= PAPER 2 ================= -->
      <div style="
        display: grid;
        grid-template-columns: 250px minmax(0, 1fr);
        gap: 28px;
        padding: 24px;
        border: 1px solid #e7e9ec;
        border-radius: 15px;
        background: #ffffff;
        box-shadow: 0 4px 16px rgba(0,0,0,0.035);
      ">

        <div style="
          width: 250px;
          height: 165px;
          overflow: hidden;
          border-radius: 9px;
          background: #f3f4f5;
        ">
          <img
            src="{{ '/assets/img/publication_preview/seam.png' | relative_url }}"
            alt="Seam-Guided Image Stitching"
            style="
              width: 100%;
              height: 100%;
              display: block;
              object-fit: cover;
            "
          >
        </div>

        <div style="min-width: 0;">

          <div style="
            margin-bottom: 8px;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
            font-size: 20px;
            line-height: 1.35;
            font-weight: 700;
            color: #1f2328;
          ">
            Seam-Guided Unsupervised Image Stitching with Parallax-Aware Mask Generation
          </div>

          <div style="
            margin-bottom: 6px;
            font-family: Georgia, 'Times New Roman', serif;
            font-size: 14.5px;
            line-height: 1.5;
            color: #262626;
          ">
            <strong>Yuzhu Tao</strong>, Lang Nie, Yakun Chang, Bo Li,
            Qingwen Li, Hong Li, Shikui Wei
          </div>

          <div style="
            margin-bottom: 9px;
            font-family: Georgia, 'Times New Roman', serif;
            font-size: 14px;
            line-height: 1.45;
            font-style: italic;
            color: #333;
          ">
            IEEE TCSVT (CCF-B), 2026
          </div>

          <div style="
            margin-bottom: 10px;
            font-family: Georgia, 'Times New Roman', serif;
            font-size: 15.5px;
            line-height: 1.52;
            color: #555;
          ">
            Robust image stitching for challenging large-parallax scenes using
            seam-guided alignment and parallax-aware mask generation.
          </div>

          <div style="
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
            font-size: 14px;
          ">
            <a href="{{ '/publications/' | relative_url }}">[Paper]</a>
          </div>

        </div>

      </div>

    </section>


    <!-- ================= HONORS ================= -->
    <section style="
      padding: 26px 30px;
      margin-bottom: 20px;
      border: 1px solid #e7e9ec;
      border-radius: 15px;
      background: #ffffff;
    ">

      <h2 style="
        margin: 0 0 16px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
        font-size: 23px;
        font-weight: 700;
        color: #202124;
      ">
        Honors & Awards
      </h2>

      <div style="
        font-family: Georgia, 'Times New Roman', serif;
        font-size: 16px;
        line-height: 1.75;
        color: #222;
      ">
        Outstanding Undergraduate Graduate of Hebei Province, 2024<br>
        First-Class Scholarship for Academic Excellence, 2024 & 2025<br>
        Outstanding Student Leader, Beijing Jiaotong University, 2025
      </div>

    </section>

  </div>


  <!-- ================= RIGHT PROFILE ================= -->
  <aside style="
    width: 320px;
    box-sizing: border-box;
    padding: 20px 20px 24px;
    border: 1px solid #e7e9ec;
    border-radius: 17px;
    background: #ffffff;
    text-align: center;
    box-shadow: 0 5px 18px rgba(0,0,0,0.04);
    position: sticky;
    top: 92px;
  ">

    <img
      src="{{ '/assets/img/yuzhutao.jpg' | relative_url }}"
      alt="Portrait of Yuzhu Tao"
      style="
        width: 100%;
        height: 430px;
        display: block;
        object-fit: cover;
        object-position: center top;
        border-radius: 11px;
        margin-bottom: 20px;
      "
    >

    <div style="
      margin-bottom: 7px;
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
      font-size: 27px;
      line-height: 1.2;
      font-weight: 700;
      color: #202124;
    ">
      Yuzhu Tao
    </div>

    <div style="
      margin-bottom: 3px;
      font-family: Georgia, 'Times New Roman', serif;
      font-size: 15px;
      line-height: 1.5;
      color: #333;
    ">
      M.Sc. Student in Artificial Intelligence
    </div>

    <div style="
      margin-bottom: 5px;
      font-family: Georgia, 'Times New Roman', serif;
      font-size: 15px;
      line-height: 1.5;
      color: #333;
    ">
      Beijing Jiaotong University
    </div>

    <div style="
      margin: 8px 0 16px;
      font-family: Georgia, 'Times New Roman', serif;
      font-size: 14px;
    ">
      <a href="mailto:taoyuzhu@bjtu.edu.cn">
        taoyuzhu@bjtu.edu.cn
      </a>
    </div>

    <div style="
      display: flex;
      justify-content: center;
      gap: 16px;
      flex-wrap: wrap;
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
      font-size: 14px;
    ">
      <a href="https://github.com/Yuzhu-Tao" target="_blank">GitHub</a>

      <a
        href="https://scholar.google.com/citations?user=V3IxgpwAAAAJ"
        target="_blank">
        Scholar
      </a>

      <a href="{{ '/cv/' | relative_url }}">
        CV
      </a>
    </div>

  </aside>

</div>
