---
layout: single
title: "2022-2023 POWERPLAY with FTC Team Area 52, 18227"
permalink: /powerplay/
classes: wide
---

<!-- === Custom Style Block for Powerplay Page === -->
<style>
  .odo-gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin: 30px 0;
  }
  
  .odo-item img, .odo-item video {
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

  .feature-section {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 30px;
    margin: 40px 0;
    align-items: center;
  }

  .feature-image img, .feature-image video {
    width: 100%;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }

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

  @media (max-width: 768px) {
    .odo-gallery, .feature-section {
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

The initial v1 design was highly complex and relied entirely on commercial off-the-shelf parts, lacking any 3D printed components. For the v2 iteration, I transitioned to a custom approach, utilizing Autodesk Fusion 360 to design tailored geometry that reduced weight and part count. The final v3 design was an operable, highly reliable pod engineered to navigate the uneven terrain created by the ground junctions during matches.

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

<div class="feature-section">
  <div class="feature-text">
    <h3>Winch Pulley Lift System</h3>
    <p>As we pushed the robot's capabilities and increased the chassis motor RPM gearbox, the odometry pods became vulnerable to high-speed impacts with ground junctions. To protect the delicate tracking hardware, I designed a winch pulley lifting system to retract and shield the pods during aggressive maneuvering.</p>
  </div>
  <div class="feature-image">
    <img src="/images/odo_lift.jpeg" alt="Winch Pulley Lift CAD">
  </div>
</div>

---

## Rotating Claw Subsystem

After finalizing the odometry pods, I observed a significant bottleneck in our scoring cycle. Placing cones on junctions was too slow because our drivers had to rotate the entire chassis to orient the cone properly. I realized that if the claw itself could rotate independently, we could eliminate the need to reposition the heavy chassis.

<div class="feature-section">
  <div class="feature-image">
    <img src="/images/rotatingv1.jpeg" alt="v1 Rotating Claw CAD">
  </div>
  <div class="feature-text">
    <p>I designed a complete rotating arm assembly. The v1 iteration featured a large structural tube, but it proved too bulky. For the final build, I optimized the 3D printed structure, carefully adjusting layer counts and infill percentages to balance weight and durability.</p> 
    <p>The core rotation mechanism relies on a single goBILDA torque servo mounted to the back of the claw. To manage the physical stress of rapid cycles, I integrated a 32mm ID bearing to effectively minimize the axial load on the servo shaft.</p>
  </div>
</div>

<div class="odo-gallery">
  <div class="odo-item">
    <img src="/images/rotating_claw_only.jpeg" alt="Rotating Claw Assembly">
    <div class="odo-caption">Final Assembly</div>
  </div>
  <div class="odo-item" style="grid-column: span 2;">
    <video src="/images/rotating_claw_final.mov" autoplay loop muted playsinline></video>
    <div class="odo-caption">Subsystem in Action</div>
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
