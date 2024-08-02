---
layout: home
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
  }
  .page-content {
    padding-top: 0; /* Remove any top padding */
  }
  .page-content h1 {
    display: none; /* Hide the large title */
  }
  .content-container {
    background-color: rgba(255, 255, 255, 0.8);
    padding: 20px;
    border-radius: 1px;
    margin: 20px;
  }
  header, .content {
    border: none;
  }
  nav {
    border-bottom: 2px solid #ffffff; /* Adding the white line under the tabs */
  }
  .main-container {
    margin: 0;
    padding: 0;
  }
  .slideshow-container {
    position: relative;
    max-width: 1000px;
    margin: auto;
  }
  .slides {
    display: none;
  }
  .prev, .next {
    cursor: pointer;
    position: absolute;
    top: 50%;
    width: auto;
    margin-top: -22px;
    padding: 16px;
    color: white;
    font-weight: bold;
    font-size: 18px;
    transition: 0.6s ease;
    border-radius: 0 3px 3px 0;
    user-select: none;
  }
  .next {
    right: 0;
    border-radius: 3px 0 0 3px;
  }
  .prev:hover, .next:hover {
    background-color: rgba(0, 0, 0, 0.8);
  }
  .dot {
    cursor: pointer;
    height: 15px;
    width: 15px;
    margin: 0 2px;
    background-color: #bbb;
    border-radius: 50%;
    display: inline-block;
    transition: background-color 0.6s ease;
  }
  .active, .dot:hover {
    background-color: #717171;
  }
  .slideshow-title {
    text-align: center;
    font-weight: bold;
    text-decoration: underline;
    font-size: 1.2em; /* Adjusted font size */
    margin-bottom: 10px;
    font-family: 'Roboto', sans-serif; /* Font for the slideshow title */
  }
  .research-box {
    margin-top: 20px;
    padding: 10px;
    background-color: lightblue;
    border: 1px solid #000;
    text-align: center;
  }
  .research-box a {
    text-decoration: none;
    font-weight: bold;
    color: black;
  }
</style>

<div class="main-container">
  <div class="content-container" style="display: flex;">
    <div style="flex: 1; display: flex; flex-direction: column; align-items: center; padding-right: 20px;">
      <img src="/assets/images/kirtman_pic.jpg" alt="Dr. Benjamin Kirtman" class="large-image" style="width: 100%; height: auto;">
    </div>
    <div style="flex: 1;">
      <p style="font-weight: bold; text-decoration: underline;">Welcome To Our Lab Website</p>
      <p>
        The Kirtman Group at the University of Miami's Rosenstiel School of Marine, Atmospheric & Earth Science specializes in climate modeling and climate variability research. Our group is very diverse with concentrations from climate predictability and prediction to weather-climate interactions and high-resolution ocean modeling. We also play an instrumental role in the North American Multi-Model Ensemble prediction system.
      </p>
      <div class="research-box">
        <a href="/research">Our Research</a>
      </div>
    </div>
  </div>

  <div class="content-container" style="display: flex;">
    <div style="flex: 1;">
      <p style="font-weight: bold; text-decoration: underline;">Contact Information</p>
      <p>
        Ben Kirtman<br>
        Professor in the Department of Atmospheric Sciences<br>
        William R Middelthon III Chair of Earth Sciences<br>
        Director of the Cooperative Institute for Marine & Atmospheric Studies<br>
        Deputy Director Frost Institute for Data Science and Computing<br>
        <br>
        University of Miami's Rosenstiel School of Marine, Atmospheric & Earth Science<br>
        Address: 4600 Rickenbacker Causeway Miami, FL 33149<br>
        Email Address: <a href="mailto:bkirtman@rsmas.miami.edu">bkirtman@rsmas.miami.edu</a>
      </p>
    </div>
  </div>

  <div class="content-container" style="display: flex;">
    <div style="flex: 1; display: flex; flex-direction: column; align-items: center; padding-right: 20px;">
      <img src="/assets/images/seasoned_chaos.jpg" alt="Seasoned Chaos Blog" class="large-image" style="width: 100%; height: auto;">
    </div>
    <div style="flex: 1;">
      <p style="font-weight: bold; text-decoration: underline;">Seasoned Chaos Blog</p>
      <p>
        A few members of the group (Kelsey, Kayla, Marybeth, Victoria, Emily, and Kurt) have started a blog about S2S predictability called ‘Seasoned Chaos’. If you haven’t checked it out yet, be sure to see the great work they’ve all done by clicking on the button below! Posts are very informative and fun. New posts are made every 1-2 months.
      </p>
      <div style="margin-top: 40px; padding: 10px; background-color: lightblue; border: 1px solid #000; text-align: center;">
        <a href="https://seasonedchaos.github.io/" style="text-decoration: none; font-weight: bold; color: black;">Visit Seasoned Chaos Blog</a>
      </div>
    </div>
  </div>

  <div class="content-container">
    <div class="slideshow-title">
      Views from the Rosenstiel Campus on Virginia Key in Miami, FL
    </div>
    <div class="slideshow-container">
      <div class="slides fade">
        <img src="/assets/images/pic1.jpg" style="width:100%">
      </div>
      <div class="slides fade">
        <img src="/assets/images/pic2.jpg" style="width:100%">
      </div>
      <div class="slides fade">
        <img src="/assets/images/pic3.jpg" style="width:100%">
      </div>
      <div class="slides fade">
        <img src="/assets/images/pic4.jpg" style="width:100%">
      </div>
      <div class="slides fade">
        <img src="/assets/images/pic5.jpg" style="width:100%">
      </div>
      <div class="slides fade">
        <img src="/assets/images/pic6.jpg" style="width:100%">
      </div>
      <div class="slides fade">
        <img src="/assets/images/pic7.jpg" style="width:100%">
      </div>
      <div class="slides fade">
        <img src="/assets/images/pic8.jpg" style="width:100%">
      </div>
      <div class="slides fade">
        <img src="/assets/images/pic9.jpg" style="width:100%">
      </div>
      <div class="slides fade">
        <img src="/assets/images/pic10.jpg" style="width:100%">
      </div>
      <div class="slides fade">
        <img src="/assets/images/pic11.jpg" style="width:100%">
      </div>
      <div class="slides fade">
        <img src="/assets/images/pic12.jpg" style="width:100%">
      </div>
      <div class="slides fade">
        <img src="/assets/images/pic13.jpg" style="width:100%">
      </div>
      <div class="slides fade">
        <img src="/assets/images/pic14.jpg" style="width:100%">
      </div>
      <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
      <a class="next" onclick="plusSlides(1)">&#10095;</a>
    </div>
    <br>
    <div style="text-align:center">
      <span class="dot" onclick="currentSlide(1)"></span>
      <span class="dot" onclick="currentSlide(2)"></span>
      <span class="dot" onclick="currentSlide(3)"></span>
      <span class="dot" onclick="currentSlide(4)"></span>
      <span class="dot" onclick="currentSlide(5)"></span>
      <span class="dot" onclick="currentSlide(6)"></span>
      <span class="dot" onclick="currentSlide(7)"></span>
      <span class="dot" onclick="currentSlide(8)"></span>
      <span class="dot" onclick="currentSlide(9)"></span>
      <span class="dot" onclick="currentSlide(10)"></span>
      <span class="dot" onclick="currentSlide(11)"></span>
      <span class="dot" onclick="currentSlide(12)"></span>
      <span class="dot" onclick="currentSlide(13)"></span>
      <span class="dot" onclick="currentSlide(14)"></span>
    </div>
  </div>
</div>

<script>
  let slideIndex = 0;
  showSlides();

  function showSlides() {
    let slides = document.getElementsByClassName("slides");
    let dots = document.getElementsByClassName("dot");
    for (let i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
    }
    slideIndex++;
    if (slideIndex > slides.length) {
      slideIndex = 1;
    }
    for (let i = 0; dots && i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
    }
    if (slides[slideIndex - 1]) {
      slides[slideIndex - 1].style.display = "block";
      dots[slideIndex - 1].className += " active";
    }
    setTimeout(showSlides, 3000); // Change image every 3 seconds
  }

  function plusSlides(n) {
    showSlides(slideIndex += n);
  }

  function currentSlide(n) {
    showSlides(slideIndex = n);
  }
</script>
