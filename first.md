---
layout: single
title: "FIRST"
permalink: /first/
classes: wide
---

<!-- === Custom Style Block === -->
<style>
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
  }

  .ftc-image-wrapper img, .ftc-image-wrapper video {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
  }

  .ftc-card:hover .ftc-image-wrapper img, .ftc-card:hover .ftc-image-wrapper video {
    transform: scale(1.1);
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

<!-- === The Visible Card HTML === -->
<div class="card-grid">

  <!-- REBUILT Card (Top Left - Above Centerstage) -->
  <div class="ftc-card">
    <a href="/rebuilt/">
      <div class="ftc-image-wrapper">
        <video src="/images/rebuilt_vid.mov" autoplay loop muted playsinline></video>
      </div>
      <div class="ftc-content">
        <h4>2026 FRC REBUILT</h4>
        <div class="ftc-subheader">FRC Team 2714 BBQ & 2728 TACO</div>
      </div>
    </a>
  </div>

  <!-- DECODE Card (Top Middle - Above Powerplay) -->
  <div class="ftc-card">
    <a href="/decode/">
      <div class="ftc-image-wrapper">
        <video src="/images/decode_vid.mov" autoplay loop muted playsinline></video>
      </div>
      <div class="ftc-content">
        <h4>2025-2026 DECODE</h4>
        <div class="ftc-subheader">FTC Team 33791 Wolverine Robotics</div>
      </div>
    </a>
  </div>

  <!-- REEFSCAPE Card (Top Right - Above FLL) -->
  <div class="ftc-card">
    <a href="/reefscape/">
      <div class="ftc-image-wrapper">
        <video src="/images/frc_2025_covervid.mov" autoplay loop muted playsinline></video>
      </div>
      <div class="ftc-content">
        <h4>2025 FRC REEFSCAPE</h4>
        <div class="ftc-subheader">FRC Team 2714 BBQ</div>
      </div>
    </a>
  </div>

  <!-- CENTERSTAGE Card (Bottom Left) -->
  <div class="ftc-card">
    <a href="/centerstage/">
      <div class="ftc-image-wrapper">
        <video src="/images/centerstage_recording.MOV" autoplay loop muted playsinline></video>
      </div>
      <div class="ftc-content">
        <h4>2023-2024 CENTERSTAGE</h4>
        <div class="ftc-subheader">FTC Team Area 52, 18227</div>
      </div>
    </a>
  </div>

  <!-- POWERPLAY Card (Bottom Middle) -->
  <div class="ftc-card">
    <a href="/powerplay/">
      <div class="ftc-image-wrapper">
        <video src="/images/rotating_claw_final.mov" autoplay loop muted playsinline></video>
      </div>
      <div class="ftc-content">
        <h4>2022-2023 POWERPLAY</h4>
        <div class="ftc-subheader">FTC Team Area 52, 18227</div>
      </div>
    </a>
  </div>

  <!-- FLL Card (Bottom Right) -->
  <div class="ftc-card">
    <a href="/fll/">
      <div class="ftc-image-wrapper">
        <video src="/images/fll_vid.mov" autoplay loop muted playsinline></video>
      </div>
