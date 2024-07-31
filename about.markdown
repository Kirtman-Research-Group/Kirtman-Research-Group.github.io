---
layout: page
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
  h1.page-title, .page-title, .page-header h1, .page-header h1.page-title, .content-wrapper + h1, .container + h1 {
    display: none; /* Hide the title on the page */
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
