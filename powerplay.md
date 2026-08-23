---
layout: single
title: "2022-2023 POWERPLAY with FTC Team Area 52, 18227"
permalink: /powerplay/
classes: wide
---

<!-- === Custom Style Block for Powerplay Page === -->
<style>
  /* Odometry Image Gallery */
  .odo-gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin: 30px 0;
  }
  
  .odo-item img {
    width: 100%;
    aspect-ratio: 1 / 1;
    object-fit: cover;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }

  .odo-caption {
    text-align: center;
    font-size: 0.9em;
    color: #555;
    margin-top: 10px;
    font-weight: 600;
  }

  /* Outreach Card Styling */
  .outreach-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition: box-shadow 0.3s ease;
    margin-top: 50px;
    display: block;
    text-decoration: none !important;
  }

  .outreach-card:hover {
    box-shadow: 0 8px 15px rgba(0,0,0,0.15);
  }

  .outreach-card img {
    width: 100%;
    height: 300px;
    object-fit: cover;
  }

  .outreach-content {
    padding: 25px;
    color: #333;
  }

  .outreach-content h3 {
    margin: 0 0 10px 0;
    font-size: 1.5em;
    color: #111;
  }

  .outreach-content p {
    margin: 0;
    font-size: 1.05em;
    line-height: 1.6;
    color: #444;
  }

  /* Mobile responsiveness */
  @media (max-width: 768px) {
    .odo-gallery {
      grid-template-columns: 1fr;
    }
    .outreach-card img {
      height: 200px;
    }
  }
</style>
<!-- === End of Custom Style Block === -->

## Custom Odometry Pod Development

My first major project in FTC was developing custom odometry pods to accurately track our robot's position on the field. The design process required multiple iterations to handle the physical demands of the Powerplay arena. 

The initial v1 design was highly complex and relied entirely on commercial off-the-shelf parts, lacking any 3D printed components. For the v2 iteration, I transitioned to a custom approach, utilizing advanced techniques in Autodesk Fusion 360 to design tailored geometry that reduced weight and part count. 

The final v3 design was an operable, highly reliable pod. We successfully deployed this version on our competition robot specifically to navigate and absorb the impacts from the uneven terrain created by the ground junctions during matches.

<!-- Image Gallery -->
<div class="odo-gallery">
  <div class="odo-item">
    <img src="/images/v1_odo_pod.JPG" alt="v1 Odometry Pod">
    <div class="odo-caption">v1: Complex COTS Assembly</div>
  </div>
  <div class="odo-item">
    <img src="/images/all_odo_pod_versions.JPG" alt="Odometry Pod Iterations">
    <div class="odo-caption">Iterative Progression</div>
  </div>
  <div class="odo-item">
    <img src="/images/v3_odo_pod.JPG" alt="v3 Odometry Pod">
    <div class="odo-caption">v3: Final Competition Pod</div>
  </div>
</div>

---

<!-- Outreach Clickable Card -->
<a href="/outreach22/" class="outreach-card">
  <img src="/images/plano2022.JPG" alt="2022 STEM Outreach">
  <div class="outreach-content">
    <h3>Community STEM Outreach</h3>
    <p>Beyond hardware development, I organized and led community initiatives throughout the 2022-2023 season to expand robotics access. We actively demonstrated engineering principles and competition robotics to local students, aiming to grow the next generation of engineers in our region.</p>
  </div>
</a>
