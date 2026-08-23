---
layout: single
title: "FIRST"
permalink: /first/
classes: wide
---

<!-- === Custom Style Block === -->
<style>
  /* Creates the 2-column grid layout */
  .card-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 30px; /* Space between the two cards */
    margin-top: 20px;
  }

  /* Card styling */
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
    display: block; /* Makes the entire card clickable */
  }

  /* Square Image Formatting */
  .ftc-image-wrapper {
    overflow: hidden;
    width: 100%;
    aspect-ratio: 1 / 1;
  }

  .ftc-image-wrapper img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
  }

  .ftc-card:hover .ftc-image-wrapper img {
    transform: scale(1.1);
  }

  /* Text Content Styling */
  .ftc-content {
    padding: 20px;
  }

  .ftc-card h4 {
    margin: 0 0 5px 0;
    color: #111;
    font-weight: 700;
    font-size: 1.3em;
  }

  .ftc-subheader {
    font-size: 1em;
    color: #555;
    margin: 0;
  }

  /* Keeps it looking good on mobile phones */
  @media (max-width: 768px) {
    .card-grid {
      grid-template-columns: 1fr;
    }
  }
</style>
<!-- === End of Custom Style Block === -->

<!-- === The Visible Card HTML === -->
<div class="card-grid">

  <!-- CENTERSTAGE Card (Left) -->
  <div class="ftc-card">
    <a href="/centerstage/">
      <div class="ftc-image-wrapper">
        <img src="/images/centerstage_photo.JPG" alt="2023-2024 CENTERSTAGE">
      </div>
      <div class="ftc-content">
        <h4>2023-2024 CENTERSTAGE</h4>
        <div class="ftc-subheader">FTC Team Area 52, 18227</div>
      </div>
    </a>
  </div>

  <!-- POWERPLAY Card (Right) -->
  <div class="ftc-card">
    <a href="/powerplay/">
      <div class="ftc-image-wrapper">
        <img src="/images/all_odo_pod_versions.JPG" alt="2022-2023 POWERPLAY">
      </div>
      <div class="ftc-content">
        <h4>2022-2023 POWERPLAY</h4>
        <div class="ftc-subheader">FTC Team Area 52, 18227</div>
      </div>
    </a>
  </div>

</div>
<!-- === End of Visible Card HTML === -->

## Competitive Robotics

**Wolverine Robotics | Founder & Captain**
* Secured school administration approval and managed the $5,000 Garver grant application.
* Led hardware design and fabrication, guiding the team to qualify for the UIL State Tournament.

**Team 18227 Area 52 | Co-Captain & Design Lead**
* Served as drive coach and led design initiatives for the World Championship.

**Team 2714 BBQ | Designer**
* Rapid-prototyped custom components in preparation for the World Championship tournament.

## Mentorship
Actively mentored youth robotics Team 2728 and Team 8816 to develop regional capabilities.
