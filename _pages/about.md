---
layout: page
title: 
permalink: /
nav: true
nav_order: 1
---

<style>
.post-header {
  display: none !important;
}
</style>

<div style="
  max-width: 1380px;
  width: 96%;
  margin: 24px auto 70px;
">

  <!-- ================= TOP AREA ================= -->
  <div style="
    display: grid;
    grid-template-columns: minmax(0, 1fr) 320px;
    gap: 64px;
    align-items: start;
    margin-bottom: 52px;
  ">

    <!-- ================= LEFT ================= -->
    <div style="min-width: 0;">

      <!-- About -->
      <section style="margin-bottom: 46px;">

        <h2 style="
          margin: 0 0 22px;
          font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
          font-size: 30px;
          font-weight: 700;
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
          <a href="https://www.bjtu.edu.cn/" target="_blank"
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


      <!-- News -->
      <section>

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
          ">
            <strong>2026.07.10</strong>
            &nbsp; 🎉Our paper,
            <em>Fast-Rotating Panoramic HDR Reconstruction from Single-Second Spikes</em>,
            has been accepted to <strong>ACM Multimedia</strong>.
            
          </p>

          <p style="
            margin: 0;
            font-family: Georgia, 'Times New Roman', serif;
            font-size: 16.5px;
            line-height: 1.5;
          ">
            <strong>2026.03.04</strong>
            &nbsp; 🎉Our paper,
            <em>Seam-Guided Unsupervised Image Stitching With Parallax-Aware Mask Generation</em>,
            has been accepted for publication in <strong>IEEE TCSVT</strong>.
          </p>

        </div>

      </section>

    </div>


    <!-- ================= RIGHT PROFILE ================= -->
    <aside style="
      width: 360px;
      box-sizing: border-box;
      padding: 20px 20px 24px;
      border: 1px solid #e7e9ec;
      border-radius: 17px;
      background: #ffffff;
      text-align: center;
      box-shadow: 0 5px 18px rgba(0,0,0,0.04);
      position: sticky;
      top: 90px;
    ">

      <img
        src="{{ '/assets/img/yuzhutao.jpg' | relative_url }}"
        alt="Portrait of Yuzhu Tao"
        style="
          width: 100%;
          height: 300px;
          object-fit: cover;
          object-position: center top;
          border-radius: 11px;
          display: block;
          margin-bottom: 20px;
        "
      >

      <div style="
        font-size: 27px;
        font-weight: 700;
        margin-bottom: 7px;
      ">
        Yuzhu Tao
      </div>

      <div style="
        font-family: Georgia, 'Times New Roman', serif;
        font-size: 15px;
        margin-bottom: 3px;
      ">
        M.Sc. Student in Artificial Intelligence
      </div>

      <div style="
        font-family: Georgia, 'Times New Roman', serif;
        font-size: 15px;
        margin-bottom: 6px;
      ">
        Beijing Jiaotong University
      </div>

      <div style="
        font-family: Georgia, 'Times New Roman', serif;
        font-size: 14px;
        margin-bottom: 16px;
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
        font-size: 14px;
      ">
        <a href="https://github.com/Yuzhu-Tao" target="_blank">GitHub</a>
        <a href="https://scholar.google.com/citations?user=V3IxgpwAAAAJ" target="_blank">Scholar</a>
        <a href="{{ '/cv/' | relative_url }}">CV</a>
      </div>

    </aside>

  </div>


  <!-- ================= FULL WIDTH PUBLICATIONS ================= -->
  <section style="margin-bottom: 50px;">

    <div style="
      display: flex;
      justify-content: space-between;
      align-items: baseline;
      margin-bottom: 22px;
    ">

      <h2 style="
        margin: 0;
        font-size: 26px;
        font-weight: 700;
      ">
        Selected Publications
      </h2>

      <a
        href="{{ '/publications/' | relative_url }}"
        style="
          font-size: 14.5px;
          font-weight: 600;
          text-decoration: none;
        ">
        View all publications →
      </a>

    </div>


    <!-- Paper 1 -->
    <div style="
      display: grid;
      grid-template-columns: 280px minmax(0, 1fr);
      gap: 32px;
      padding: 26px;
      margin-bottom: 20px;
      border: 1px solid #e7e9ec;
      border-radius: 15px;
      background: #ffffff;
      box-shadow: 0 4px 16px rgba(0,0,0,0.035);
    ">

      <img
        src="{{ '/assets/img/panoramic.jpg' | relative_url }}"
        alt="Fast-Rotating Panoramic HDR Reconstruction"
        style="
          width: 280px;
          height: 180px;
          object-fit: cover;
          border-radius: 9px;
        "
      >

      <div>

        <div style="
          font-size: 21px;
          font-weight: 700;
          line-height: 1.35;
          margin-bottom: 8px;
        ">
          Fast-Rotating Panoramic HDR Reconstruction from Single-Second Spikes
        </div>

        <div style="
          font-family: Georgia, 'Times New Roman', serif;
          font-size: 14.5px;
          line-height: 1.5;
          margin-bottom: 6px;
        ">
          <strong>Yuzhu Tao</strong>, Yakun Chang, Shikui Wei, Lang Nie,
          Qingwen Li, Bo Li, Boxin Shi, Yao Zhao
        </div>

        <div style="
          font-family: Georgia, 'Times New Roman', serif;
          font-size: 14px;
          font-style: italic;
          margin-bottom: 10px;
        ">
          ACM Multimedia (CCF-A), 2026
        </div>

        <div style="
          font-family: Georgia, 'Times New Roman', serif;
          font-size: 15.5px;
          line-height: 1.55;
          color: #555;
          margin-bottom: 10px;
        ">
          HDR panoramic reconstruction under fast rotation using spike imaging
          and multimodal generative modeling.
        </div>

        <div style="font-size: 14px;">
          <a href="{{ '/publications/' | relative_url }}">[Paper]</a>
          &nbsp;
          <a href="{{ '/projects/' | relative_url }}">[Project]</a>
          &nbsp;
          <a href="{{ '/projects/' | relative_url }}">[Video]</a>
        </div>

      </div>

    </div>


    <!-- Paper 2 -->
    <div style="
      display: grid;
      grid-template-columns: 280px minmax(0, 1fr);
      gap: 32px;
      padding: 26px;
      border: 1px solid #e7e9ec;
      border-radius: 15px;
      background: #ffffff;
      box-shadow: 0 4px 16px rgba(0,0,0,0.035);
    ">

      <img
        src="{{ '/assets/img/publication_preview/seam.png' | relative_url }}"
        alt="Seam-Guided Image Stitching"
        style="
          width: 280px;
          height: 180px;
          object-fit: cover;
          border-radius: 9px;
        "
      >

      <div>

        <div style="
          font-size: 21px;
          font-weight: 700;
          line-height: 1.35;
          margin-bottom: 8px;
        ">
          Seam-Guided Unsupervised Image Stitching with Parallax-Aware Mask Generation
        </div>

        <div style="
          font-family: Georgia, 'Times New Roman', serif;
          font-size: 14.5px;
          line-height: 1.5;
          margin-bottom: 6px;
        ">
          <strong>Yuzhu Tao</strong>, Lang Nie, Yakun Chang, Bo Li,
          Qingwen Li, Hong Li, Shikui Wei
        </div>

        <div style="
          font-family: Georgia, 'Times New Roman', serif;
          font-size: 14px;
          font-style: italic;
          margin-bottom: 10px;
        ">
          IEEE TCSVT (CCF-B), 2026
        </div>

        <div style="
          font-family: Georgia, 'Times New Roman', serif;
          font-size: 15.5px;
          line-height: 1.55;
          color: #555;
          margin-bottom: 10px;
        ">
          Robust image stitching for challenging large-parallax scenes using
          seam-guided alignment and parallax-aware mask generation.
        </div>

        <div style="font-size: 14px;">
          <a href="{{ '/publications/' | relative_url }}">[Paper]</a>
        </div>

      </div>

    </div>

  </section>


  <!-- ================= FULL WIDTH HONORS ================= -->
  <section style="
    padding: 28px 32px;
    border: 1px solid #e7e9ec;
    border-radius: 15px;
    background: #ffffff;
    margin-bottom: 20px;
  ">

    <h2 style="
      margin: 0 0 18px;
      font-size: 24px;
      font-weight: 700;
    ">
      Honors & Awards
    </h2>

    <div style="
      font-family: Georgia, 'Times New Roman', serif;
      font-size: 16px;
      line-height: 1.8;
    ">
      Outstanding Undergraduate Graduate of Hebei Province, 2024<br>
      First-Class Scholarship for Academic Excellence, 2024 & 2025<br>
      Outstanding Student Leader, Beijing Jiaotong University, 2025
    </div>

  </section>

</div>
