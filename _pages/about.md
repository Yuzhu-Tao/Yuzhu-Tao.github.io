---
layout: page
title:
permalink: /
nav: true
---

<style>
/* ===== Homepage background ===== */
body {
  background: #f5f6f7;
}

/* remove excessive page title spacing */
.post-header {
  display: none;
}

/* ===== Main layout ===== */
.my-home {
  display: grid;
  grid-template-columns: 255px minmax(0, 1fr);
  gap: 28px;
  max-width: 1120px;
  margin: 12px auto 60px;
  align-items: start;
}

/* ===== Card ===== */
.home-card {
  background: #ffffff;
  border: 1px solid #eeeeee;
  border-radius: 14px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
}

/* ===== Left profile ===== */
.profile-card {
  padding: 24px 22px 22px;
  text-align: center;
  position: sticky;
  top: 85px;
}

.profile-photo {
  width: 100%;
  aspect-ratio: 1 / 1.28;
  object-fit: cover;
  display: block;
  margin-bottom: 12px;
}

.profile-name {
  font-size: 24px;
  font-weight: 700;
  line-height: 1.2;
  margin: 8px 0 8px;
  color: #262626;
}

.profile-role {
  margin: 0;
  font-size: 14px;
  color: #333;
}

.profile-school {
  margin: 3px 0;
  font-size: 14px;
}

.profile-email {
  margin: 3px 0 12px;
  font-size: 14px;
}

.profile-school a,
.profile-email a {
  color: #1677ff;
  text-decoration: none;
}

.profile-links {
  margin-top: 10px;
  display: flex;
  justify-content: center;
  gap: 15px;
}

.profile-links a {
  font-size: 21px;
  color: #1677ff;
  text-decoration: none;
}

/* ===== Right column ===== */
.home-right {
  min-width: 0;
}

/* ===== About ===== */
.about-card {
  padding: 32px 40px 34px;
  margin-bottom: 16px;
}

.about-card h1 {
  margin: 0 0 22px;
  font-size: 28px;
  font-weight: 700;
  color: #252525;
}

.about-card p {
  margin: 0 0 14px;
  font-size: 15.5px;
  line-height: 1.65;
  color: #272727;
}

/* ===== Section card ===== */
.section-card {
  overflow: hidden;
  margin-bottom: 16px;
}

.section-header {
  padding: 15px 20px;
  border-bottom: 1px solid #e5e5e5;
  font-size: 17px;
  font-weight: 700;
  color: #282828;
}

.section-header a {
  color: #1677ff;
  font-weight: 600;
  text-decoration: none;
}

/* ===== Publication item ===== */
.pub-item {
  display: grid;
  grid-template-columns: 105px minmax(0, 1fr);
  gap: 18px;
  padding: 18px 20px;
  border-bottom: 1px solid #e7e7e7;
}

.pub-item:last-of-type {
  border-bottom: none;
}

.pub-thumb {
  width: 105px;
  height: 70px;
  object-fit: cover;
  border-radius: 4px;
  margin-top: 2px;
}

.pub-title {
  margin: 0 0 4px;
  font-size: 18px;
  line-height: 1.3;
  font-weight: 500;
  color: #242424;
}

.pub-authors {
  margin: 0 0 3px;
  font-size: 12.5px;
  line-height: 1.45;
  color: #222;
}

.pub-authors strong {
  font-weight: 700;
}

.pub-venue {
  margin: 0 0 3px;
  font-size: 13px;
  line-height: 1.4;
  font-style: italic;
  color: #333;
}

.pub-description {
  margin: 0 0 3px;
  font-size: 13px;
  line-height: 1.5;
  color: #68717c;
}

.pub-buttons a {
  color: #0675ff;
  font-size: 13px;
  text-decoration: none;
  margin-right: 2px;
}

.all-publications {
  padding: 14px 18px;
  text-align: right;
}

.all-publications a {
  color: #1677ff;
  text-decoration: none;
  font-size: 14px;
  font-weight: 600;
}

/* ===== Awards ===== */
.awards-card {
  padding-bottom: 16px;
}

.awards-content {
  padding: 16px 22px 4px;
  font-size: 14px;
  line-height: 1.8;
}

/* ===== Mobile ===== */
@media (max-width: 800px) {
  .my-home {
    display: block;
    margin-top: 0;
  }

  .profile-card {
    position: static;
    max-width: 320px;
    margin: 0 auto 18px;
  }

  .about-card {
    padding: 24px;
  }

  .pub-item {
    grid-template-columns: 1fr;
  }

  .pub-thumb {
    width: 150px;
    height: 95px;
  }
}
</style>


<div class="my-home">

  <!-- ================= LEFT ================= -->
  <aside>

    <div class="home-card profile-card">

      <img
        class="profile-photo"
        src="{{ '/assets/img/yuzhutao.jpg' | relative_url }}"
        alt="Portrait of Yuzhu Tao"
      >

      <div class="profile-name">
        Yuzhu Tao
      </div>

      <p class="profile-role">
        M.Sc. Student
      </p>

      <p class="profile-school">
        <a href="https://www.bjtu.edu.cn/" target="_blank">
          Beijing Jiaotong University
        </a>
      </p>

      <p class="profile-email">
        <a href="mailto:taoyuzhu@bjtu.edu.cn">
          taoyuzhu@bjtu.edu.cn
        </a>
      </p>

      <div class="profile-links">

        <a
          href="https://github.com/Yuzhu-Tao"
          target="_blank"
          title="GitHub">
          <i class="fa-brands fa-github"></i>
        </a>

        <a
          href="https://scholar.google.com/citations?user=V3IxgpwAAAAJ"
          target="_blank"
          title="Google Scholar">
          <i class="ai ai-google-scholar"></i>
        </a>

      </div>

    </div>

  </aside>


  <!-- ================= RIGHT ================= -->
  <main class="home-right">

    <!-- About -->
    <section class="home-card about-card">

      <h1>About Me</h1>

      <p>
        I am <strong>Yuzhu Tao</strong>, a master's student in Artificial Intelligence
        at <strong>Beijing Jiaotong University</strong>.
      </p>

      <p>
        My research lies at the intersection of
        <strong>computer vision and multimodal intelligence</strong>,
        with a focus on
        <strong>image generation and editing, panoramic reconstruction,
        image stitching, and multimodal large models</strong>.
      </p>

      <p>
        My recent work explores HDR panoramic reconstruction with spike cameras,
        robust image stitching under large parallax, and generative image editing
        with multimodal foundation models.
      </p>

    </section>


    <!-- Selected Publications -->
    <section class="home-card section-card">

      <div class="section-header">
        ★ Selected Publications
        <a href="{{ '/publications/' | relative_url }}">
          (view all 》)
        </a>
      </div>


      <!-- Paper 1 -->
      <div class="pub-item">

        <img
          class="pub-thumb"
          src="{{ '/assets/img/panorama.png' | relative_url }}"
          alt="Fast-Rotating Panoramic HDR Reconstruction"
        >

        <div>

          <div class="pub-title">
            Fast-Rotating Panoramic HDR Reconstruction from Single-Second Spikes
          </div>

          <p class="pub-authors">
            <strong>Yuzhu Tao</strong>, Yakun Chang, Shikui Wei, Lang Nie,
            Qingwen Li, Bo Li, Boxin Shi, Yao Zhao
          </p>

          <p class="pub-venue">
            ACM Multimedia (CCF-A), 2026
          </p>

          <p class="pub-description">
            We present a fast panoramic HDR reconstruction framework that combines
            spike-based imaging and multimodal generative modeling to recover
            full-color HDR panoramas from one-second spike acquisition.
          </p>

          <div class="pub-buttons">
            <a href="{{ '/publications/' | relative_url }}">[Paper]</a>
            <a href="{{ '/projects/' | relative_url }}">[Project]</a>
          </div>

        </div>

      </div>


      <!-- Paper 2 -->
      <div class="pub-item">

        <img
          class="pub-thumb"
          src="{{ '/assets/img/scene1.jpg' | relative_url }}"
          alt="Seam-Guided Image Stitching"
        >

        <div>

          <div class="pub-title">
            Seam-Guided Unsupervised Image Stitching with Parallax-Aware Mask Generation
          </div>

          <p class="pub-authors">
            <strong>Yuzhu Tao</strong>, Lang Nie, Yakun Chang,
            Bo Li, Qingwen Li, Hong Li, Shikui Wei
          </p>

          <p class="pub-venue">
            IEEE Transactions on Circuits and Systems for Video Technology (CCF-B), 2026
          </p>

          <p class="pub-description">
            A seam-guided iterative alignment framework with parallax-aware
            mask generation for robust image stitching under challenging
            large-parallax scenes.
          </p>

          <div class="pub-buttons">
            <a href="{{ '/publications/' | relative_url }}">[Paper]</a>
          </div>

        </div>

      </div>


      <div class="all-publications">
        <a href="{{ '/publications/' | relative_url }}">
          All publications 》
        </a>
      </div>

    </section>


    <!-- Honors -->
    <section class="home-card section-card awards-card">

      <div class="section-header">
        Honors & Awards
      </div>

      <div class="awards-content">
        First-Class Scholarship for Academic Excellence, Beijing Jiaotong University, 2024 & 2025<br>
        Outstanding Student Leader, Beijing Jiaotong University, 2025<br>
        Outstanding Undergraduate Graduate of Hebei Province, 2024
      </div>

    </section>

  </main>

</div>
