---
layout: single
title: "Research"
permalink: /research/
classes: wide
---

<!-- === Custom Style Block === -->
<style>
  /* Top Section: 1 Card Left, 1 Text Box Right */
  .mg-section {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 30px;
    margin-bottom: 40px;
    align-items: stretch;
  }

  /* Bottom Section: 2 Cards Side-by-Side */
  .secondary-research-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 30px;
    margin-bottom: 20px;
  }

  /* Universal Card Styling */
  .research-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    text-align: center;
    transition: box-shadow 0.3s ease;
    display: flex;
    flex-direction: column;
    height: 100%;
  }

  .research-card:hover {
    box-shadow: 0 8px 15px rgba(0,0,0,0.15);
  }

  .research-card a {
    text-decoration: none;
    color: #333;
    display: flex;
    flex-direction: column;
    flex-grow: 1;
  }

  .research-image-wrapper {
    overflow: hidden;
    width: 100%;
    aspect-ratio: 16 / 9; /* Wider ratio for research cards */
  }

  .research-image-wrapper img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
  }

  .research-card:hover .research-image-wrapper img {
    transform: scale(1.05);
  }

  .research-content {
    padding: 20px;
    flex-grow: 1;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .research-card h4 {
    margin: 0 0 5px 0;
    color: #111;
    font-weight: 700;
    font-size: 1.2em; 
  }

  .research-subheader {
    font-size: 0.95em; 
    color: #555;
    margin: 0;
  }

  /* Text Box Styling */
  .info-box {
    background-color: #f9f9f9;
    border-left: 4px solid #005bb5;
    padding: 25px;
    border-radius: 0 8px 8px 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  
  .info-box.full-width {
    border-left: none;
    border-top: 4px solid #005bb5;
    border-radius: 8px;
  }

  .info-box h3 {
    margin-top: 0;
    color: #222;
  }

  .info-box p {
    color: #444;
    line-height: 1.6;
    margin-bottom: 0;
  }

  /* Mobile Layout */
  @media (max-width: 850px) {
    .mg-section, .secondary-research-grid {
      grid-template-columns: 1fr;
    }
    .info-box {
      border-left: none;
      border-top: 4px solid #005bb5;
      border-radius: 8px;
    }
  }
</style>
<!-- === End of Custom Style Block === -->


<!-- === Top Section: MG Research === -->
<div class="mg-section">
  
  <!-- Left Side: MG Card -->
  <div class="research-card">
    <a href="/mg-research/">
      <div class="research-image-wrapper">
        <img src="/images/mg_research_cover.jpg" alt="MG Research">
      </div>
      <div class="research-content">
        <h4>Computational Nanobody Decoy Design</h4>
        <div class="research-subheader">Myasthenia Gravis Targeting</div>
      </div>
    </a>
  </div>

  <!-- Right Side: MG Description Box -->
  <div class="info-box">
    <h3>Targeting Acetylcholine Receptors</h3>
    <p>This project focuses on computational drug design to address Myasthenia Gravis. Operating under a research mentor, I engineered computational nanobody decoys specifically designed to target acetylcholine receptors (AChR). I structured a comprehensive research manuscript detailing this methodology and presented our findings at the American Academy of Neurology Annual Meeting in April 2026.</p>
  </div>

</div>

<hr style="margin: 40px 0; border: 0; border-top: 1px solid #eee;">

<!-- === Bottom Section: AI & Piezo Research === -->
<div class="secondary-research-grid">

  <!-- AI Review Card -->
  <div class="research-card">
    <a href="/ai-agriculture/">
      <div class="research-image-wrapper">
        <img src="/images/ai_ag_cover.jpg" alt="AI in Precision Agriculture">
      </div>
      <div class="research-content">
        <h4>AI in Precision Agriculture</h4>
        <div class="research-subheader">Review Paper</div>
      </div>
    </a>
  </div>

  <!-- Piezoelectric Lattice Card -->
  <div class="research-card">
    <a href="/piezo-lattice/">
      <div class="research-image-wrapper">
        <img src="/images/piezo_cover.jpg" alt="Piezoelectric Lattice Research">
      </div>
      <div class="research-content">
        <h4>Piezoelectric Micro-Structures</h4>
        <div class="research-subheader">University of Texas at Dallas</div>
      </div>
    </a>
  </div>

</div>

<!-- Bottom Full-Width Description Box -->
<div class="info-box full-width">
  <h3>Secondary Research Initiatives</h3>
  <p>Beyond drug design, I have expanded my research into agricultural technology and material science. My review paper evaluates the current implementation and future scalability of artificial intelligence within precision agriculture. Concurrently, I conducted research at the University of Texas at Dallas, utilizing ANSYS software to simulate and analyze the mechanical responses of piezoelectric micro-structures.</p>
</div>
