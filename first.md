---
layout: single
title: "FIRST"
permalink: /first/
classes: wide
---

<!-- === Custom Style Block === -->
<style>
  .first-intro {
    font-size: 1.05em;
    line-height: 1.7;
    color: #333;
    margin-bottom: 40px;
  }

  .first-intro p {
    margin-bottom: 20px;
  }

  .card-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px; 
    margin-top: 20px;
  }

  .ftc-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    text-align: center;
    transition: box-shadow 0.3s ease;
  }

  .ftc-card:hover {
    box-shadow: 0 8px 15px rgba(0,0,0,0.15);
  }

  .ftc-card a {
    text-decoration: none;
    color: #333;
    display: block; 
  }

  .ftc-image-wrapper {
    overflow: hidden;
    width: 100%;
    aspect-ratio: 1 / 1;
    -webkit-mask-image: -webkit-radial-gradient(white, black);
  }

  .ftc-image-wrapper img, .ftc-image-wrapper video {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
    will-change: transform;
    backface-visibility: hidden;
    -webkit-backface-visibility: hidden;
  }

  .ftc-card:hover .ftc-image-wrapper img, .ftc-card:hover .ftc-image-wrapper video {
    transform: scale(1.1) translateZ(0);
  }

  .ftc-content {
    padding: 15px;
  }

  .ftc-card h4 {
    margin: 0 0 5px 0;
    color: #111;
    font-weight: 700;
    font-size: 1.1em; 
  }

  .ftc-subheader {
    font-size: 0.9em; 
    color: #555;
    margin: 0;
  }

  @media (max-width: 768px) {
    .card-grid {
      grid-template-columns: 1fr;
    }
  }
</style>
<!-- === End of Custom Style Block === -->

<!-- === FIRST Introduction === -->
<div class="first-intro">
  <p>For the past ten years, FIRST Robotics has been the defining catalyst of my engineering journey. What began as a childhood fascination with structural stability evolved into a lifelong commitment to mechanical design, strategic problem-solving, and the core philosophy of Gracious Professionalism. Through a decade of hands-on fabrication and rigorous iterative design, FIRST has fundamentally shaped not only the engineer I am today, but the leader I have become.</p>

  <p>My competitive progression deeply mirrors my technical growth. I started by forming my own FIRST LEGO League (FLL) team, learning the foundational logic of programming and assembly. As I advanced into the FIRST Tech Challenge (FTC) and the FIRST Robotics Competition (FRC), the engineering challenges scaled exponentially. I transitioned to engineering custom drivetrains, modeling complex mechanisms in CAD, and managing the rapid prototyping of robust physical assemblies. This dedication culminated in advancing to the FIRST World Championship at the highest levels of both FTC and FRC.</p>

  <p>However, the true impact of FIRST extends far beyond the competition field. Driven to expand access to STEM education within my own community, I founded FTC Team 33791, Wolverine Robotics, at Wakeland High School. Transitioning from a team member to a Founder and Captain allowed me to cultivate a culture of engineering excellence and strategic execution. By actively mentoring junior robotics programs and organizing extensive community outreach initiatives, I strive to pass on the same technical curiosity and collaborative spirit that FIRST originally instilled in me.</p>
</div>
<!-- === End of FIRST Introduction === -->

<!-- === The Visible Card HTML === -->
<div class="card-grid">

  <!-- REBUILT Card (FRC 26 - MP4) -->
  <div class="ftc-card">
    <a href="/rebuilt/">
      <div class="ftc-image-wrapper">
        <video src="/images/rebuilt_vid.mp4" autoplay loop muted playsinline></video>
      </div>
      <div class="ftc-content">
        <h4>2026 FRC REBUILT</h4>
        <div class="ftc-subheader">FRC Team 2714 BBQ & 2728 TACO</div>
      </div>
    </a>
  </div>

  <!-- DECODE Card (FTC 25-26 - WebP Image) -->
  <div class="ftc-card">
    <a href="/decode/">
      <div class="ftc-image-wrapper">
        <img src="/images/decode_cover.webp" alt="2025-2026 DECODE">
      </div>
      <div class="ftc-content">
        <h4>2025-2026 DECODE</h4>
        <div class="ftc-subheader">FTC Team 33791 Wolverine Robotics</div>
      </div>
    </a>
  </div>

  <!-- REEFSCAPE Card (FRC 25 - MP4) -->
  <div class="ftc-card">
    <a href="/reefscape/">
      <div class="ftc-image-wrapper">
        <video src="/images/frc_2025_covervid.mp4" autoplay loop muted playsinline></video>
      </div>
      <div class="ftc-content">
        <h4>2025 FRC REEFSCAPE</h4>
        <div class="ftc-subheader">FRC Team 2714 BBQ</div>
      </div>
    </a>
  </div>

  <!-- CENTERSTAGE Card (FTC 23-24 - WebP Image) -->
  <div class="ftc-card">
    <a href="/centerstage/">
      <div class="ftc-image-wrapper">
        <img src="/images/centerstage_recording.webp" alt="2023-2024 CENTERSTAGE">
      </div>
      <div class="ftc-content">
        <h4>2023-2024 CENTERSTAGE</h4>
        <div class="ftc-subheader">FTC Team Area 52, 18227</div>
      </div>
    </a>
  </div>

  <!-- POWERPLAY Card (FTC 22-23 - MP4) -->
  <div class="ftc-card">
    <a href="/powerplay/">
      <div class="ftc-image-wrapper">
        <video src="/images/rotating_claw_final.mp4" autoplay loop muted playsinline></video>
      </div>
      <div class="ftc-content">
        <h4>2022-2023 POWERPLAY</h4>
        <div class="ftc-subheader">FTC Team Area 52, 18227</div>
      </div>
    </a>
  </div>

  <!-- FLL Card (FLL - WebP Image) -->
  <div class="ftc-card">
    <a href="/fll/">
      <div class="ftc-image-wrapper">
        <img src="/images/fll_vid.webp" alt="2017-2020 FLL">
      </div>
      <div class="ftc-content">
        <h4>2017-2020 FLL</h4>
        <div class="ftc-subheader">FLL Team DNA Robotics, 38335</div>
      </div>
    </a>
  </div>

</div>
<!-- === End of Visible Card HTML === -->
