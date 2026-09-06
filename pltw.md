---
layout: single
title: "PLTW"
permalink: /pltw/
classes: wide
---

<!-- === Custom Style Block === -->
<style>
  .pltw-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px; 
    margin-top: 20px;
  }

  .pltw-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    text-align: center;
    transition: box-shadow 0.3s ease;
  }

  .pltw-card:hover {
    box-shadow: 0 8px 15px rgba(0,0,0,0.15);
  }

  .pltw-card a {
    text-decoration: none;
    color: #333;
    display: block; 
  }

  .pltw-image-wrapper {
    overflow: hidden;
    width: 100%;
    aspect-ratio: 1 / 1;
  }

  .pltw-image-wrapper img, .pltw-image-wrapper video {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
  }

  .pltw-card:hover .pltw-image-wrapper img, .pltw-card:hover .pltw-image-wrapper video {
    transform: scale(1.1);
  }

  .pltw-content {
    padding: 15px;
  }

  .pltw-card h4 {
    margin: 0 0 5px 0;
    color: #111;
    font-weight: 700;
    font-size: 1.1em; 
  }

  .pltw-subheader {
    font-size: 0.9em; 
    color: #555;
    margin: 0;
  }

  @media (max-width: 900px) {
    .pltw-grid {
      grid-template-columns: repeat(2, 1fr);
    }
  }

  @media (max-width: 600px) {
    .pltw-grid {
      grid-template-columns: 1fr;
    }
  }
</style>
<!-- === End of Custom Style Block === -->

<!-- === The Visible Card HTML === -->
<div class="pltw-grid">

  <!-- Motor Car Card -->
  <div class="pltw-card">
    <a href="/motor-car/">
      <div class="pltw-image-wrapper">
        <img src="/images/motor_car_cover.jpg" alt="Motor Car">
      </div>
      <div class="pltw-content">
        <h4>Motor Car</h4>
        <div class="pltw-subheader">Intro to Engineering Design</div>
      </div>
    </a>
  </div>

  <!-- Automata Card -->
  <div class="pltw-card">
    <a href="/automata/">
      <div class="pltw-image-wrapper">
        <img src="/images/automata_cover.jpg" alt="Automata">
      </div>
      <div class="pltw-content">
        <h4>Automata</h4>
        <div class="pltw-subheader">Intro to Engineering Design</div>
      </div>
    </a>
  </div>

  <!-- Compound Machine Card -->
  <div class="pltw-card">
    <a href="/compound-machine/">
      <div class="pltw-image-wrapper">
        <img src="/images/compound_machine_cover.jpg" alt="Compound Machine Project">
      </div>
      <div class="pltw-content">
        <h4>Compound Machine Project</h4>
        <div class="pltw-subheader">Principles of Engineering</div>
      </div>
    </a>
  </div>

  <!-- 3 Axis Arm Card -->
  <div class="pltw-card">
    <a href="/3-axis-arm/">
      <div class="pltw-image-wrapper">
        <img src="/images/3_axis_arm_cover.jpg" alt="3 Axis Arm">
      </div>
      <div class="pltw-content">
        <h4>3 Axis Arm</h4>
        <div class="pltw-subheader">Principles of Engineering</div>
      </div>
    </a>
  </div>

</div>
<!-- === End of Visible Card HTML === -->
