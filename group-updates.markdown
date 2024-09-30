here's my updated code:

---
layout: page
title: Group Updates
permalink: /group-updates/
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
  .container {
    background-color: rgba(255, 255, 255, 0.8);
    padding: 20px;
    border-radius: 8px;
    margin: 20px 0;
    text-align: center; /* Center align the content */
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
  .container img {
    width: 90%;
    max-width: 100%; 
    height: auto;
    border-radius: 8px;
    display: block;
    margin: 0 auto; /* Centers the image */
  }
    .divider {
    width: 90%; /* Adjust the width of the divider */
    height: 2px; /* Thickness of the line */
    background-color: black; /* Color of the line */
    margin: 20px auto; /* Adds padding above and below the line */
  }
    .welcome-title {
    font-size: 32px; /* Large font for the title, but nothing too crazy */
    font-weight: bold;
    text-align: center;
    margin: 20px 0;
  }
</style>

<div class="page-content">
  <div class="container">
    <img src="/assets/images/update1.jpg" alt="Descriptive Image">
    <div class="divider"></div> <!-- Custom black divider underneath the image -->
    <div class="welcome-title">Welcome New Group Members</div>
    <div class="divider"></div>
    <img src="/assets/images/update1_1.jpg" alt="Another Descriptive Image">
    <div class="divider"></div>
  </div>
</div>
