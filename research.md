---
layout: single
title: "Research"
permalink: /research/
classes: wide
---

<!-- === Custom Style Block === -->
<style>
  .research-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 30px;
    margin-bottom: 50px;
    align-items: stretch;
  }

  .research-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    text-align: center;
    transition: box-shadow 0.3s ease;
    display: flex;
    flex-direction: column;
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
    aspect-ratio: 16 / 9; 
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

  .info-box {
    background-color: #f9f9f9;
    border-left: 4px solid #005bb5;
    padding: 30px;
    border-radius: 0 8px 8px 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
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
    .research-row {
      grid-template-columns: 1fr;
      gap: 0;
    }
    .research-card {
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

<!-- === Row 1: MG Research === -->
<div class="research-row">
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
  <div class="info-box">
    <h3>Targeting Acetylcholine Receptors</h3>
    <p>This project focuses on computational drug design to address Myasthenia Gravis. I engineered computational nanobody decoys to specifically target acetylcholine receptors (AChR). Following the modeling phase, I structured a comprehensive research manuscript detailing the methodology and presented our findings at the American Academy of Neurology Annual Meeting in April 2026.</p>
  </div>
</div>

<!-- === Row 2: AI in Precision Agriculture === -->
<div class="research-row">
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
  <div class="info-box">
    <h3>Machine Learning in Agriculture</h3>
    <p>This review paper evaluates the current implementation and future scalability of artificial intelligence within precision agriculture. I analyzed existing literature to identify technological bottlenecks and assess the practical deployment of machine learning models for crop yield optimization and resource management.</p>
  </div>
</div>

<!-- === Row 3: Piezoelectric Lattice === -->
<div class="research-row">
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
  <div class="info-box">
    <h3>ANSYS Mechanical Simulations</h3>
    <p>I conducted material science research at the University of Texas at Dallas to evaluate the mechanical responses of complex geometries. I utilized ANSYS software to simulate and analyze piezoelectric micro-structures under various stress conditions, gathering data on their structural integrity and electrical output.</p>
  </div>
</div>

<!-- === Row 4: UTD Business Intelligence === -->
<div class="research-row">
  <div class="research-card">
    <a href="/utd-bida/">
      <div class="research-image-wrapper">
        <img src="/images/utd_bida_cover.jpg" alt="Business Intelligence and Data Analytics">
      </div>
      <div class="research-content">
        <h4>Business Intelligence and Data Analytics</h4>
        <div class="research-subheader">University of Texas at Dallas</div>
      </div>
    </a>
  </div>
  <div class="info-box">
    <h3>Data-Driven Strategy</h3>
    <p>This section encompasses my work within the UTD Business Intelligence and Data Analytics program. I focused on extracting actionable insights from large datasets to drive operational efficiency and informed decision-making.</p>
  </div>
</div>
