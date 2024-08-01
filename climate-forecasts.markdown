---
layout: page
title: Climate Forecasts
permalink: /climate-forecasts/
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
  .page-content h1 {
    display: none; /* Hide the large title */
  }
  .container {
    background-color: rgba(255, 255, 255, 0.8); /* Slightly transparent white background for better readability */
    padding: 20px;
    border-radius: 8px;
    max-width: 800px;
    margin: 20px auto; /* Center the container on the page */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  .nmme-container {
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
  .nmme-container .nmme-title {
    font-size: 28px; /* Slightly smaller font size */
    color: black;
    margin-bottom: 10px; /* Less padding between title and text/image */
    width: 100%;
  }
  .nmme-content {
    display: flex;
    align-items: flex-start;
    width: 100%;
  }
  .nmme-content img {
    width: 400px; /* Increased width */
    height: auto;
    margin-left: 20px;
  }
  .nmme-content p {
    font-size: 14px; /* Smaller font size */
    color: black;
    margin: 0;
  }
  .nmme-container a {
    color: blue;
    text-decoration: none;
  }
  .nmme-container a:hover {
    text-decoration: underline;
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
</style>

<div class="nmme-container">
  <div class="nmme-title">The North American Multi-Model Ensemble (NMME)</div>
  <div class="nmme-content">
    <div>
      <p>University of Miami (RSMAS) contributes Community Climate System Model version 4.0 (CCSM4) hindcasts and forecasts to the North American Multi-Model Ensemble (NMME) System for Intra-Seasonal to Inter-Annual (ISI) Predictions.</p>
      <p>NMME is a multi-model seasonal forecasting system that consists of coupled climate model hindcasts and forecasts from various North American modeling centers, including University of Miami's Rosenstiel School of Marine and Atmospheric Science (RSMAS).</p>
      <p>For real-time NMME forecasts, data access to hindcasts, and more information, please visit the <a href="https://www.cpc.ncep.noaa.gov/products/NMME/">NMME website</a>.</p>
    </div>
    <img src="/assets/images/nmme.jpg" alt="NMME">
  </div>
</div>
