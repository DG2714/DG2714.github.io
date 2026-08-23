---
layout: single
title: "FIRST"
permalink: /first/
---
<!-- === Custom Style Block === -->
<style>
  /* This creates the clean 'card' container */
  .powerplay-card {
    max-width: 320px;
    margin: 1em auto;
    border: 1px solid #ddd;   /* The nice clean border */
    border-radius: 8px;      /* Slightly rounded corners, which look cleaner */
    overflow: hidden;        /* Keeps the image zoom contained */
    box-shadow: 0 4px 6px rgba(0,0,0,0.1); /* Subtle shadow for depth */
    text-align: center;
    transition: box-shadow 0.3s ease; /* Smoothly changes shadow on hover */
  }

  /* Increases the card's shadow on hover */
  .powerplay-card:hover {
    box-shadow: 0 8px 15px rgba(0,0,0,0.15);
  }

  .powerplay-card a {
    text-decoration: none; /* Removes the underline from the link text */
    color: #333; /* Sets a professional title color */
  }

  /* === Controls the Square Image === */
  .powerplay-image-wrapper {
    overflow: hidden; /* Crucial for the zoom effect */
    width: 100%;
    aspect-ratio: 1 / 1; /* Forces the image container to be a perfect square */
  }

  .powerplay-image-wrapper img {
    width: 100%;
    height: 100%;
    object-fit: cover; /* Ensures image covers the square without stretching */
    transition: transform 0.3s ease; /* The magic that makes the zoom smooth */
  }

  /* === The Zoom on Hover effect === */
  .powerplay-card:hover .powerplay-image-wrapper img {
    transform: scale(1.1); /* Zooms the image in by 10% */
  }

  /* Controls the text styling underneath */
  .powerplay-content {
    padding: 15px;
  }

  /* Styles for the Main Title */
  .powerplay-card h4 {
    margin: 0 0 5px 0;
    color: #111;
    font-weight: 700;
  }

  /* Styles for the Smaller Subheader */
  .powerplay-card .powerplay-subheader {
    font-size: 0.9em;
    color: #555;
    margin: 0;
  }
</style>
<!-- === End of Custom Style Block === -->

<!-- === The Visible Card HTML === -->
<div class="powerplay-card">
  <a href="/powerplay/">
    <div class="powerplay-image-wrapper">
      <img src="/images/all_odo_pod_versions.JPG" alt="FTC POWERPLAY FTC Team Area 52, 18227">
    </div>
    <div class="powerplay-content">
      <h4>2022-2023 POWERPLAY</h4>
      <div class="powerplay-subheader">FTC Team Area 52, 18227</div>
    </div>
  </a>
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
