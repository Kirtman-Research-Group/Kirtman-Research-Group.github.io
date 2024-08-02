---
layout: page
title: Climate Forecasts
permalink: /climate-forecasts/
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
  .custom-title {
    font-size: 25px;
    font-weight: bold;
    text-decoration: underline;
  }
  .custom-description {
    margin-top: 10px;
    font-size: 16px;
  }
  .sub-container {
    display: flex;
    align-items: flex-start;
    margin-top: 20px;
  }
  .year-title {
    font-size: 20px;
    font-weight: bold;
    text-decoration: underline;
    margin-right: 20px;
  }
  .publication-text {
    font-size: 14px;
  }
  .publication-text a {
    text-decoration: none;
    color: inherit;
  }
  .underline {
    text-decoration: underline;
  }
  .bold {
    font-weight: bold;
  }
  .pad {
    margin-top: 10px;
  }
  .divider {
    border-top: 1px solid #000;
    width: fit-content;
    margin: 10px 0;
  }
  .container {
    background-color: rgba(255, 255, 255, 0.8); /* Slightly transparent white background for better readability */
    padding: 20px;
    border-radius: 8px;
    max-width: 800px;
    margin: 20px auto; /* Center the container on the page */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  .nmme-container, .ccsm4-container {
    background-color: rgba(255, 255, 255, 0.9); /* Slightly transparent white background */
    padding: 20px;
    border-radius: 8px;
    max-width: 1200px; /* Increase the max-width to make the container wider */
    margin: 20px auto; /* Center the container on the page */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    display: flex;
    flex-direction: column; /* Ensure title is above text and image */
    align-items: flex-start;
  }
  .nmme-title, .ccsm4-title {
    font-size: 25px; /* Slightly smaller font size */
    color: black;
    margin-bottom: 10px; /* Less padding between title and text/image */
    width: 100%;
    text-align: center; /* Center the title */
  }
  .nmme-content, .ccsm4-content {
    display: flex;
    align-items: flex-start;
    width: 100%;
  }
  .nmme-content img, .ccsm4-content img {
    width: 400px; /* Increased width */
    height: auto;
    margin-left: 20px;
  }
  .nmme-content p, .ccsm4-content p {
    font-size: 12px; /* Smaller font size */
    color: black;
    margin: 0;
  }
  .nmme-container a, .ccsm4-container a {
    color: blue;
    text-decoration: none;
  }
  .nmme-container a:hover, .ccsm4-container a:hover {
    text-decoration: underline;
  }
  .full-width-text {
    width: 100%;
    margin-top: 20px; /* Add some space between the sections */
    font-size: 12px;
    color: black;
  }
  .full-width-text ul {
    list-style-type: disc;
    padding-left: 40px; /* Adjust the padding to control indentation */
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
    margin-bottom: 10px; /* Smaller distance between title and content */
  }
  .columns {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap; /* Allow columns to wrap to the next line */
  }
  .column {
    flex: 1;
    text-align: center;
    margin: 10px; /* Add margin to space out columns */
    max-width: calc(33.333% - 20px); /* Ensure three columns per row */
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
  .former-container .content-wrapper h1 {
    font-weight: bold;
  }
  .former-container .content-wrapper p {
    margin-top: 10px; /* Add margin between lines */
    font-style: normal; /* Ensure no italic style */
  }
  .former-container .content-wrapper p.contact-email {
    font-style: normal;
    margin-top: 5px;
  }
  .former-container .content-wrapper p.italic {
    font-style: italic;
  }
  .smaller-image {
    width: 150px;
    height: auto;
  }
  .webpage-button {
    display: inline-block;
    padding: 10px 20px;
    margin-top: 10px;
    background-color: lightblue;
    color: white;
    border: 2px solid white;
    border-radius: 4px;
    text-decoration: none;
    font-size: 14px;
  }
  .webpage-button:hover {
    background-color: #87CEEB; /* Darker shade of light blue */
  }
  .centered-image {
    display: flex;
    justify-content: center;
    width: 100%;
    margin-top: 10px; /* Reduce the space between the text and the image */
  }
  .centered-image img {
    width: 400px; /* Set the desired width */
    height: auto;
  }
  .nmme-content p {
    padding-top: 10px; /* Add padding to the text under the title in the first container */
  }
</style>

<div class="nmme-container">
  <div class="nmme-title">The North American Multi-Model Ensemble (NMME)</div>
  <div class="nmme-content">
    <div>
      <p>University of Miami (Rosenstiel School) contributes Community Climate System Model version 4.0 (CCSM4) hindcasts and forecasts to the North American Multi-Model Ensemble (NMME) System for Intra-Seasonal to Inter-Annual (ISI) Predictions.</p>
      <p style="margin-top: 10px; font-size: 12px;">NMME is a multi-model seasonal forecasting system that consists of coupled climate model hindcasts and forecasts from various North American modeling centers, including University of Miami's Rosenstiel School of Marine, Atmospheric and Earth Science.</p>
      <p style="margin-top: 10px">For real-time NMME forecasts, data access to hindcasts, and more information, please visit the <a href="https://www.cpc.ncep.noaa.gov/products/NMME/">NMME website</a>.</p>
    </div>
    <img src="/assets/images/nmme.jpg" alt="NMME">
  </div>
  <div class="full-width-text">
    <p>The <a href="https://www.cpc.ncep.noaa.gov/products/NMME/">NMME website</a> includes real-time forecasts of global SST, precipitation and 2-meter temperature, and precipitation and 2-meter temperature over North America for individual models and the full NMME suite on the timescales listed below:</p>
    <ul>
      <li><a href="https://www.cpc.ncep.noaa.gov/products/NMME/monanom.shtml">Monthly Climate Anomaly Forecasts</a></li>
      <li><a href="https://www.cpc.ncep.noaa.gov/products/NMME/seasanom.shtml">Seasonal Climate Anomaly Forecasts</a></li>
    </ul>
    <p style="margin-top: 10px;"> A description of the NMME system is provided <a href="https://www.cpc.ncep.noaa.gov/products/NMME/NMME_description.html">here.</a> </p>
    <p style="margin-top: 10px;"> Data access for hindcasts and real-time forecasts for all individual models and NMME ensemble mean is provided <a href="https://www.cpc.ncep.noaa.gov/products/NMME/data.html">here.</a> </p>
  </div>
  <div class="centered-image">
    <img src="/assets/images/nmme2.jpg" alt="NMME 2">
  </div>
</div>

<div class="ccsm4-container">
  <div class="ccsm4-title">CCSM4 Southeast US Climate Predictions (Experimental)</div>
  <div class="ccsm4-content">
    <div>
      <p>In addition to NMME, University of Miami (RSMAS) maintains Community Climate System Model version 4.0 (CCSM4) experimental climate forecasts of southeastern US precipitation, 2-meter temperature, horizontal (u) winds, evaporation, runoff, and soil moisture on monthly and seasonal time-scales.</p>
      <p style="margin-top: 10px; font-size: 12px;">For climate southeastern US CCSM4 climate forecasts, please see the <a href="https://rsmas-ccsm4.weebly.com/">CCSM4 Southeastern US Climate Prediction website.</a></p>
      <p style="margin-top: 10px;"> The <a href="https://rsmas-ccsm4.weebly.com/">CCSM4 Southeastern US Climate Prediction website</a> includes predictions on <a href="https://rsmas-ccsm4.weebly.com/monthly.html">monthly</a> and <a href="https://rsmas-ccsm4.weebly.com/seasonal.html">seasonal</a> time-scales, and at present includes forecasts initialized April 2016 through the current month for lead times 0 through 5.  For more information on these predictions, visit the <a href="https://rsmas-ccsm4.weebly.com/faq.html">FAQ</a>.  </p>
    </div>
    <img src="/assets/images/ccsm4.jpg" alt="CCSM4">
  </div>
  <div class="centered-image">
    <img src="/assets/images/ccsm42.jpg" alt="CCSM4 2">
  </div>
</div>
