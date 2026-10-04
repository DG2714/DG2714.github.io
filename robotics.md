---
layout: single
title: "Robotics & Hardware"
permalink: /robotics/
classes: wide
---

<!-- === Custom Style Block === -->
<style>
  .hw-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 30px;
    margin-bottom: 50px;
    align-items: center; 
  }

  .hw-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    text-align: center;
    transition: box-shadow 0.3s ease;
    display: flex;
    flex-direction: column;
  }

  .hw-card:hover {
    box-shadow: 0 8px 15px rgba(0,0,0,0.15);
  }

  .hw-card a {
    text-decoration: none;
    color: #333;
    display: block; 
  }

  .hw-image-wrapper {
    overflow: hidden;
    width: 100%;
    aspect-ratio: 16 / 9; 
  }

  .hw-image-wrapper img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
  }

  .hw-card:hover .hw-image-wrapper img {
    transform: scale(1.05);
  }

  .hw-content {
    padding: 20px 20px 25px 20px; 
  }

  .hw-card h4 {
    margin: 0 0 5px 0;
    color: #111;
    font-weight: 700;
    font-size: 1.2em; 
  }

  .hw-subheader {
    font-size: 0.95em; 
    color: #555;
    margin: 0;
  }

  .info-box {
    background-color: #f9f9f9;
    border-left: 4px solid #005bb5;
    padding: 30px;
    border-radius: 0 8px 8px 0;
  }

  .info-box h3 {
    margin-top: 0;
    color: #222;
    font-size: 1.4em;
    margin-bottom: 15px;
  }

  .info-box p {
    color: #444;
    line-height: 1.6;
    margin: 0;
  }

  @media (max-width: 850px) {
    .hw-row {
      grid-template-columns: 1fr;
      gap: 0;
    }
    .hw-card {
      border-radius: 8px 8px 0 0;
    }
    .info-box {
      border-left: none;
      border-top: 4px solid #005bb5;
      border-radius: 0 0 8px 8px;
    }
  }
</style>
<!-- === End of Custom Style Block === -->

<!-- === Row 1: FIRST Robotics === -->
<div class="hw-row">
  <div class="hw-card">
    <a href="/first/">
      <div class="hw-image-wrapper">
        <img src="/images/first_cover.jpg" alt="FIRST Robotics">
      </div>
      <div class="hw-content">
        <h4>FIRST Robotics</h4>
        <div class="hw-subheader">FLL, FTC, and FRC Competition History</div>
      </div>
    </a>
  </div>
  <div class="info-box">
    <h3>Competitive Engineering & Strategy</h3>
    <p>This section details my progression through the FIRST ecosystem. I served in primary technical and leadership roles across multiple teams, including founding Wolverine Robotics and leading design and drive coaching for Area 52. My work spans custom odometry fabrication, 3D printed active mechanisms, and live match strategy mapping.</p>
  </div>
</div>

<!-- === Row 2: Combat Robotics === -->
<div class="hw-row">
  <div class="hw-card">
    <a href="/combat/">
      <div class="hw-image-wrapper">
        <img src="/images/combat_cover.jpg" alt="Combat Robotics">
      </div>
      <div class="hw-content">
        <h4>Combat Robotics</h4>
        <div class="hw-subheader">Plastic Antweight Class</div>
      </div>
    </a>
  </div>
  <div class="info-box">
    <h3>Drum Spinner Development</h3>
    <p>I design, CAD, and build plastic antweight combat robots. This requires stringent weight distribution analysis and impact-resistant geometry. I integrate high-performance electronics into compact footprints, pairing components like Repeat Robotics motors and Turnabot planetary gearmotors with AM32 speed controllers and RadioMaster ELRS systems to maximize kinetic energy and drive reliability.</p>
  </div>
</div>

<!-- === Row 3: PLTW === -->
<div class="hw-row">
  <div class="hw-card">
    <a href="/pltw/">
      <div class="hw-image-wrapper">
        <img src="/images/pltw_cover.jpg" alt="Project Lead The Way">
      </div>
      <div class="hw-content">
        <h4>Project Lead The Way</h4>
        <div class="hw-subheader">Engineering Coursework</div>
      </div>
    </a>
  </div>
  <div class="info-box">
    <h3>Academic Hardware Fabrication</h3>
    <p>Through my Intro to Engineering Design and Principles of Engineering coursework, I developed foundational CAD and rapid prototyping skills. I engineered functional assemblies including a multi-axis robotic arm, kinetic automata, and compound machine systems, bridging the gap between theoretical physics and applied mechanics.</p>
  </div>
</div>
