---
layout: single
title: "Dev Gavande"
excerpt: "Engineering Portfolio"
header:
  overlay_image: /images/header_bg.jpg
  overlay_color: "#0f2847" # This applies the dark blue tint
  overlay_filter: "0.75" # 75% opacity to make the white text readable
permalink: /
classes: wide
author_profile: false
---

<!-- === Custom Style Block === -->
<style>
  /* Force page to expand into the empty sidebar space */
  .page {
    width: 100% !important;
    max-width: 1200px !important;
    margin: 0 auto;
  }
  
  /* Section Headers & Dark Grey Separation Bars */
  .section-title {
    font-size: 2.2em;
    font-weight: 700;
    color: #111;
    margin-bottom: 5px;
    margin-top: 50px;
  }
  
  .section-divider {
    border: 0;
    border-top: 3px solid #333;
    margin-bottom: 30px;
  }

  /* Quick Links Button Grid */
  .quick-links-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 15px;
    margin-bottom: 40px;
  }

  .quick-link-btn {
    display: block;
    text-align: center;
    padding: 12px 10px;
    background-color: #f1f3f5;
    color: #333;
    text-decoration: none;
    font-weight: 600;
    border-radius: 6px;
    border: 1px solid #dee2e6;
    transition: all 0.2s ease;
  }

  .quick-link-btn:hover {
    background-color: #e9ecef;
    border-color: #ced4da;
    text-decoration: none;
    color: #0f2847;
  }

  /* Featured Projects Row Styling */
  .featured-row {
    display: grid;
    grid-template-columns: 1.2fr 1fr; 
    gap: 0; 
    margin-bottom: 40px;
    background-color: #f9f9f9; 
    border: 1px solid #e9ecef;
    border-radius: 8px;
    overflow: hidden;
  }

  .featured-image-wrapper {
    width: 100%;
    aspect-ratio: 16 / 9;
    overflow: hidden;
    border-right: 1px solid #e9ecef; 
  }

  .featured-image-wrapper img, .featured-image-wrapper video {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .featured-text {
    padding: 30px;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .featured-text h3 {
    margin-top: 0;
    margin-bottom: 15px;
    font-size: 1.4em;
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
    background-color: #fff;
    color: #333;
    text-decoration: none;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-weight: 600;
    font-size: 0.9em;
    transition: all 0.2s ease;
  }

  .read-more-btn:hover {
    background-color: #f1f3f5;
    text-decoration: none;
    color: #111;
  }

  @media (max-width: 900px) {
    .featured-row {
      grid-template-columns: 1fr;
    }
    .featured-image-wrapper {
      border-right: none;
      border-bottom: 1px solid #e9ecef;
    }
    .quick-links-grid {
      grid-template-columns: repeat(2, 1fr);
    }
  }
</style>
<!-- === End of Custom Style Block === -->

<h2 class="section-title">Background</h2>
<hr class="section-divider">
<p>My name is Dev Gavande. I am a high school senior and aspiring mechanical engineer based in Frisco, Texas. My technical experience spans custom hardware fabrication and drivetrain design for competitive robotics, alongside finite element analysis of piezoelectric micro-structures. Independently, I conduct computational structural protein modeling for neurological drug discovery. This portfolio details my ongoing engineering projects and academic research. For a comprehensive overview of my background, please visit my <a href="/about/">About Me</a> page.</p>

<h2 class="section-title">Quick Links</h2>
<hr class="section-divider">
<div class="quick-links-grid">
  <a href="/first/" class="quick-link-btn">FIRST Robotics</a>
  <a href="/pltw/" class="quick-link-btn">PLTW Projects</a>
  <a href="/combat/" class="quick-link-btn">Combat Robotics</a>
  <a href="/research/" class="quick-link-btn">College Level Research</a>
</div>

<h2 class="section-title">Featured Projects</h2>
<hr class="section-divider">

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
