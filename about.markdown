---
layout: page-people
title: People
permalink: /people/
---

<style>
  body {
    background: url('/assets/images/cloud.jpg') no-repeat center center fixed;
    background-size: cover;
    margin-top: 0;
    padding-top: 0;
  }
  .navbar {
    margin-bottom: 0;
    border-bottom: none;
  }
  .page-content {
    padding-top: 0; /* Remove any top padding */
  }
  .container {
    background-color: rgba(255, 255, 255, 0.8); /* Slightly transparent white background for better readability */
    padding: 20px;
    border-radius: 8px;
    max-width: 800px;
    margin: 20px auto; /* Center the container on the page */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  .content-wrapper {
    display: flex;
    align-items: flex-start;
    flex-direction: column;
  }
  .content-wrapper img {
    margin-right: 20px;
    width: 250px;
    height: auto;
  }
  .content-wrapper div {
    flex: 1;
  }
  .content-wrapper h1 {
    margin: 0;
    font-size: 24px;
    color: black;
  }
  .content-wrapper p {
    margin: 0;
    font-size: 14px; /* Smaller font size for all lines except the first */
    color: black;
    font-style: italic;
  }
  .content-wrapper p.lightgreen a {
    color: green;
    text-decoration: none;
  }
  .content-wrapper p.lightblue a {
    color: lightblue;
    text-decoration: none;
  }
  .page-people .page-title {
    display: none; /* Hide the title on the page */
  }
  .new-container {
    background-color: rgba(255, 255, 255, 0.8); /* Slightly transparent white background for better readability */
    padding: 20px;
    border-radius: 8px;
    max-width: 800px;
    margin: 20px auto; /* Center the container on the page */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    margin-top: 20px; /* Add space between containers */
  }
  .new-container h2 {
    font-size: 24px;
    color: black;
    margin-bottom: 20px;
  }
  .columns {
    display: flex;
    justify-content: space-between;
  }
  .column {
    flex: 1;
    text-align: center;
    margin: 0 10px;
  }
  .column img {
    width: 100%;
    height: auto;
    max-width: 200px;
    margin-bottom: 10px;
  }
  .column p {
    font-size: 14px; /* Adjust the font size as needed */
    color: black;
    font-style: italic;
    margin: 5px 0;
  }
  .column p.name {
    font-size: 18px;
    font-style: normal;
    color: black;
  }
  .column p.navy {
    color: navy;
  }
  .column p.purple {
    color: purple;
  }
</style>

<div class="container">
  <div class="content-wrapper" style="padding-top: 20px;">
      <img src="/assets/images/ben.jpg" alt="Ben Kirtman">
      <div>
          <h1>Ben Kirtman, PhD</h1>
          <p>Professor of Atmospheric Sciences</p>
          <p>William R. Middelthon III Endowed Chair in Earth Sciences</p>
          <p class="lightgreen">
              <a href="https://cimas.earth.miami.edu/">Director: Cooperative Institute for Marine & Atmospheric Studies</a>
          </p>
          <p class="lightblue">
              <a href="https://idsc.miami.edu/about/people/">Program Director: Climate and Environmental Hazards, Center for Computational Science, Rosenstiel School, University of Miami</a>
          </p>
      </div>
  </div>
</div>

<div class="new-container">
  <h2>Postdocs & Researchers</h2>
  <div class="columns">
    <div class="column">
      <img src="/assets/images/leo.jpg" alt="Leo Siqueira">
      <p class="name">Leo Siqueira, PhD</p>
      <p class="navy">Assistant Scientist</p>
      <p class="navy">University of Miami, Rosenstiel School</p>
      <p class="purple">Institute for Data Science & Computing</p>
      <p>My research interests include ENSO dynamics & predictability, Earth system model development, High-resolution global climate modeling and the role of ocean fronts and eddies in decadal climate prediction.</p>
    </div>
    <div class="column">
      <img src="/assets/images/dug.jpg" alt="Dughong Min">
      <p class="name">Dughong Min, PhD</p>
      <p class="navy">Research Scientist</p>
      <p class="navy">University of Miami, Rosenstiel School</p>
      <p class="purple">Center for Computational Sciences</p>
      <p>My research interests include advanced climate modeling techniques and applications in regional climate assessments, with a focus on improving predictive capabilities for environmental hazards.</p>
    </div>
    <div class="column">
      <img src="/assets/images/rachel.jpg" alt="Rachel Gaal">
      <p class="name">Rachel Gaal, PhD</p>
      <p class="navy">Postdoctoral Researcher</p>
      <p class="navy">University of Miami, Rosenstiel School</p>
      <p class="purple">Contact Email: <a href="mailto:rxg1381@earth.miami.edu">rxg1381@earth.miami.edu</a></p>
      <p>My research interests include modeling and working with the WRF model to do high-resolution regional modeling over Florida through dynamical and statistical downscaling techniques. Outside of the office I love hiking and backpacking. I also love the beach and being outdoors.</p>
    </div>
  </div>
</div>
