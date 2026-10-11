---
layout: single
title: "Dev Gavande | Engineering Portfolio"
permalink: /
classes: wide
---

My name is Dev Gavande, and I am an aspiring mechanical engineer dedicated to bridging physical hardware fabrication with advanced computational modeling. My technical background spans custom drivetrain design for competitive robotics, finite element analysis of piezoelectric structures, and structural protein modeling for neurological drug discovery. For a comprehensive overview of my background and academic trajectory, please visit my [About Me](/about/) page.

### Quick Links
* [FIRST Robotics](/first/)
* [PLTW Projects](/pltw/)
* [Combat Robotics](/combat/)
* [College Level Research](/research/)

<hr style="margin: 40px 0; border: 0; border-top: 1px solid #eee;">

<!-- === Custom Style Block for Featured Projects === -->
<style>
  .featured-section-title {
    font-size: 2em;
    font-weight: 700;
    margin-bottom: 30px;
    color: #111;
  }

  .featured-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 40px;
    margin-bottom: 60px;
    align-items: flex-start;
  }

  .featured-image-wrapper {
    width: 100%;
    aspect-ratio: 16 / 9;
    overflow: hidden;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }

  .featured-image-wrapper img, .featured-image-wrapper video {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .featured-text {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
  }

  .featured-text h3 {
    margin-top: 0;
    margin-bottom: 15px;
    font-size: 1.5em;
    color: #222;
    line-height: 1.3;
  }

  .featured-text p {
    color: #444;
    line-height: 1.6;
    margin-bottom: 20px;
  }

  .read-more-btn {
    align-self: flex-start;
    display: inline-block;
    padding: 8px 16px;
    background-color: #f8f9fa;
    color: #333;
    text-decoration: none;
    border: 1px solid #ddd;
    border-radius: 4px;
    font-weight: 600;
    font-size: 0.9em;
    transition: all 0.2s ease;
  }

  .read-more-btn:hover {
    background-color: #e2e6ea;
    text-decoration: none;
    color: #111;
  }

  @media (max-width: 850px) {
    .featured-row {
      grid-template-columns: 1fr;
      gap: 20px;
    }
  }
</style>
<!-- === End of Custom Style Block === -->

<h2 class="featured-section-title">Featured Projects</h2>

<!-- === Featured Project 1: MG Research === -->
<div class="featured-row">
  <div class="featured-image-wrapper">
    <img src="/images/mg_research_cover.jpg" alt="Myasthenia Gravis Research">
  </div>
  <div class="featured-text">
    <h3>American Academy of Neurology Annual Meeting and Autoimmunology Conference</h3>
    <p>Operating under a research mentor, I engineered computational nanobody decoys specifically designed to target acetylcholine receptors (AChR) to address Myasthenia Gravis. I structured a comprehensive research manuscript detailing this methodology and presented our computational findings at the American Academy of Neurology Annual Meeting in Chicago.</p>
    <a href="/mg-research/" class="read-more-btn">Read More</a>
  </div>
</div>

<!-- === Featured Project 2: REBUILT === -->
<div class="featured-row">
  <div class="featured-image-wrapper">
    <video src="/images/rebuilt_vid.mp4" loop muted playsinline></video>
  </div>
  <div class="featured-text">
    <h3>FIRST Robotics Competition: 2026 REBUILT Season</h3>
    <p>As a designer and technical contributor for FRC Team 2714 BBQ and 2728 TACO, I rapidly prototyped custom components and managed live match strategy. This season demanded rigorous iteration of active intake mechanisms and robust drive capabilities to prepare for highly competitive World Championship qualification tiers.</p>
    <a href="/rebuilt/" class="read-more-btn">Read More</a>
  </div>
</div>

<!-- === Featured Project 3: Combat Robotics === -->
<div class="featured-row">
  <div class="featured-image-wrapper">
    <img src="/images/combat_cover.jpg" alt="Combat Robotics">
  </div>
  <div class="featured-text">
    <h3>Wolf Tech Combat Robotics - 1 Pound Plastic Antweight Division</h3>
    <p>I conceptualize, CAD, and assemble custom plastic antweight combat robots. This engineering process requires stringent weight distribution analysis, impact-resistant 3D printed chassis geometry, and the integration of high-performance brushless outrunner motors and planetary gearboxes to maximize kinetic weapon energy.</p>
    <a href="/combat/" class="read-more-btn">Read More</a>
  </div>
</div>

<!-- === Featured Project 4: DECODE === -->
<div class="featured-row">
  <div class="featured-image-wrapper">
    <video src="/images/decode_vid.mp4" loop muted playsinline></video>
  </div>
  <div class="featured-text">
    <h3>FIRST Tech Challenge: 2025 DECODE Season</h3>
    <p>Serving as Founder, Captain, and Hardware Lead for FTC Team 33791 Wolverine Robotics, I established the organization and led all mechanical design initiatives. By integrating custom hardware fabrication with strategic match execution, I guided our team through regional qualifiers directly to the UIL State Tournament in Waco, Texas.</p>
    <a href="/decode/" class="read-more-btn">Read More</a>
  </div>
</div>

<!-- === Hover-to-Play Script for Featured Videos === -->
<script>
  document.addEventListener("DOMContentLoaded", function() {
    const rows = document.querySelectorAll('.featured-row');
    rows.forEach(row => {
      const vid = row.querySelector('video');
      if (vid) {
        row.addEventListener('mouseenter', () => vid.play());
        row.addEventListener('mouseleave', () => vid.pause());
      }
    });
  });
</script>
