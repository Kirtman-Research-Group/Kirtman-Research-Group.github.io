---
layout: page
title: Research
permalink: /research/
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@700&display=swap'); /* Example of importing a Google Font */

  body {
    background: url('/assets/images/cloud.jpg') no-repeat center center fixed;
    background-size: cover;
    margin: 0;
    padding: 0;
    font-family: 'Arial', sans-serif; /* Default font for the page */
  }
  .navbar {
    margin-bottom: 0;
    border-bottom: none;
  }
  .page-content {
    padding-top: 0; /* Remove any top padding */
  }
  .page-content h1 {
    display: none; /* Hide the large title */
  }
  .content-container, .container, .new-container, .third-container, .fourth-container, .fifth-container, .final-container {
    background-color: rgba(255, 255, 255, 0.8); /* Slightly transparent white background for better readability */
    padding: 20px;
    border-radius: 8px;
    margin: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    max-width: 800px; /* Center the container on the page */
  }
  .new-container, .third-container, .fourth-container, .fifth-container, .final-container {
    margin-top: 20px; /* Add space between containers */
  }
  .content-container h2, .new-container h2, .third-container h3, .fourth-container h3, .fifth-container h3, .final-container h3 {
    font-size: 25px;
    color: black;
    margin-bottom: 10px; /* Smaller distance between title and content */
    font-weight: bold;
  }
  .container .content-wrapper {
    display: flex;
    align-items: flex-start;
  }
  .container .content-wrapper img {
    margin-right: 20px;
    width: 125px; /* Half the original width */
    height: auto;
  }
  .container .content-wrapper div {
    flex: 1;
  }
  .container .content-wrapper div h2 {
    margin-top: 0;
  }
  .content-wrapper p {
    margin: 0;
    font-size: 14px; /* Smaller font size for all lines except the first */
    color: black;
  }
  .content-wrapper p a {
    color: blue;
    text-decoration: none;
  }
  .content-wrapper p a:hover {
    text-decoration: underline;
  }
  .third-container h4, .fifth-container h4 {
    font-size: 20px;
    color: black;
    font-weight: normal;
    margin-top: 1px; /* Less padding between titles */
    margin-bottom: 1px; /* Reduce padding below h4 */
  }
  .third-container .image-wrapper, .fifth-container .image-wrapper, .final-container .image-wrapper {
    display: flex;
    justify-content: space-between;
    margin-top: 1px; /* Reduce margin-top for images */
  }
  .third-container .image-wrapper img, .fifth-container .image-wrapper img, .final-container .image-wrapper img {
    width: 48%; /* Adjust width to take up half the container */
    height: auto;
  }
  .third-container .image-wrapper p, .fifth-container .image-wrapper p {
    text-align: center;
    font-size: 10px;
    margin-top: 1px;
  }
  .third-container .description, .fifth-container .description {
    font-size: 14px;
    color: black;
    margin-top: 1px; /* Reduce margin-top for description */
  }
  .fourth-container video {
    width: 100%;
    height: auto;
    display: block;
    margin: 0 auto;
  }
  .fourth-container p {
    text-align: center;
    font-size: 10px;
    color: black;
    margin-top: 5px;
  }
  .final-container .image-wrapper {
    display: flex;
    justify-content: space-between;
    margin-top: 10px;
  }
  .final-container .image-wrapper img {
    width: 48%; /* Adjust width for two side by side images */
    height: auto;
  }
  .final-container .full-width-image img {
    width: 100%;
    height: auto;
    margin-top: 10px;
  }
</style>

<div class="content-container">
  <div class="content-wrapper">
    <img src="/assets/images/kirtman_speaking.jpg" alt="Kirtman Speaking">
    <div>
      <h2>Research</h2>
      <p>Many of our model experiments are performed using the computing facilities on campus. Special thanks to the <a href="https://idsc.miami.edu/">University of Miami Center for Computational Sciences (CCS)</a> for computational support.</p>
    </div>
  </div>
</div>

<div class="content-container">
  <h2>Overview</h2>
  <div class="content-wrapper">
    <div>
      <p>Dr. Kirtman’s research is a wide-ranging program designed to understand and quantify the limits of climate predictability from days to decades. The research also involves understanding how the climate will change in response to changes in anthropogenic (e.g., greenhouse gases) and natural (e.g., volcanoes) forcing. This research involves hypothesis testing numerical experiments using sophisticated state-of-the-art climate models and experimental real-time prediction. The group uses and has access to a suite of climate models, climate data and high performance computational platforms. Some results from various projects are briefly summarized here.</p>
    </div>
  </div>
</div>

<div class="content-container">
  <h3>Ocean Eddies and Large-Scale Climate Variability</h3>
  <h4>The importance of model resolution.</h4>
  <div class="image-wrapper">
    <div>
      <img src="/assets/images/hi_res.jpg" alt="High Resolution">
      <p>High Resolution</p>
    </div>
    <div>
      <img src="/assets/images/low_res.jpg" alt="Low Resolution">
      <p>Low Resolution</p>
    </div>
  </div>
  <div class="description">
    <p>One of Dr. Kirtman’s projects is a collaborative effort including scientists from George Mason University and the National Center for Atmospheric Research. The project seeks to understand how ocean eddies impact large-scale climate variability. This requires global climate simulations conducted at resolutions that have never before been attempted. The figures above show a snap shot of the surface current speeds in this high-resolution simulation compared to the typical resolutions used. Capturing the details of these currents has been shown to dramatically affect the global distribution of rainfall.</p>
  </div>
</div>

<div class="content-container">
  <video controls>
    <source src="/assets/images/historical_simulation.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p>Here you will find a movie of our historical simulation from 1990-2010. The overall historical simulation is from 1940-2010.</p>
</div>

<div class="content-container">
  <h3>Seasonal Climate Prediction</h3>
  <h4>North American Multi-Model Ensemble (NMME)</h4>
  <div class="description">
    <p>Dr. Kirtman’s research group is also leading an effort to develop a US National Multi-Model Ensemble prediction system for intraseasonal-to-interannual prediction. The figure on the bottom right shows the forecast skill (as measured by the correlation between the predictions and observations. The bottom left shows the forecast skill for global sea surface temperatures. The new prediction system has considerable skill in the southern tier of the US and is being used to understand the mechanisms for persistent drought and the limits of predictability. <a href="https://benkirtman.weebly.com/climate-forecasts.html">See more about the NMME here</a> and <a href="https://cpo.noaa.gov/tag/nmme/">here</a>.</p>
  </div>
  <div class="image-wrapper">
    <div>
      <img src="/assets/images/nmme_precip.jpg" alt="NMME Precipitation Correlation">
      <p>6-month lead precipitation correlation</p>
    </div>
    <div>
      <img src="/assets/images/nmme_ssta.jpg" alt="NMME SSTA Correlation">
      <p>6-month lead SSTA correlation</p>
    </div>
  </div>
</div>

<div class="content-container">
  <h3>Interactive Ensemble</h3>
  <div class="description">
    <p>We have also developed a new ocean-atmosphere-sea-ice-land coupling system called the “interactive ensemble” that is specifically designed to diagnose coupled feedbacks between the component models and estimate how high frequency variability in one component affect the other components. In the example shown below we have used the interactive ensemble to diagnose how atmospheric weather impacts the low frequency meridional overturning circulation in the Atlantic Ocean. This meridional overturning circulation is critical for maintaining the relatively warm climate over Europe. The top two panel show the mean meridional overturning circulation from a simulation with realistic atmospheric weather (left panel) and from the interactive ensemble simulation with reduced atmospheric weather (right panel). The bottom panel shows how this meridional overturning circulation changes with time (blue control and red interactive ensemble). The result suggests that atmospheric weather is an important factor in the overturning circulation.</p>
  </div>
  <div class="image-wrapper">
    <div>
      <img src="/assets/images/depth_a.jpg" alt="Depth A">
    </div>
    <div>
      <img src="/assets/images/depth_b.jpg" alt="Depth B">
    </div>
  </div>
  <div class="full-width-image">
    <img src="/assets/images/depth_c.jpg" alt="Depth C">
  </div>
</div>
