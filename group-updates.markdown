---
layout: page
title: Group Updates
permalink: /group-updates/
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@700&display=swap');

  body {
    background: url('/assets/images/cloud.jpg') no-repeat center center fixed;
    background-size: cover;
    margin: 0;
    padding: 0;
    font-family: 'Arial', sans-serif;
  }
  .navbar {
    margin-bottom: 0;
    border-bottom: none;
  }
  .page-content {
    padding-top: 0;
  }
  .page-content h1 {
    display: none;
  }

  .container {
    background-color: rgba(255, 255, 255, 0.8);
    padding: 20px;
    border-radius: 8px;
    margin: 20px 0;
    text-align: center;
  }

  .divider {
    width: 90%;
    height: 2px;
    background-color: black;
    margin: 20px auto;
  }

  .welcome-title {
    font-size: 16px;
    font-weight: bold;
    text-align: center;
    margin: 20px 0;
  }

  /* Default container images (full-width) */
  .container img {
    width: 90%;
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    display: block;
    margin: 0 auto;
  }

  .full-width-text {
    font-size: 14px;
    width: 90%;
    margin: 0 auto;
    text-align: justify;
    text-justify: inter-word;
    padding-top: 10px;
    line-height: 1.4;
  }

  .note-italic {
    width: 90%;
    margin: 10px auto 0 auto;
    font-size: 14px;
    font-style: italic;
    text-align: center;
  }

  /* Split rows */
  .split-row {
    width: 90%;
    margin: 0 auto;
    display: flex;
    align-items: stretch;
    justify-content: space-between;
    gap: 10px;
  }

  .split-col {
    width: 50%;
    display: flex;
    align-items: center;
  }

  /* Make split-row images truly half-width (override the default .container img rule) */
  .split-row img {
    width: 100%;
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    display: block;
    margin: 0;
  }

  /* Justified text next to images (fixes flex-justify issue) */
  .split-text-inner {
    font-size: 14px;
    line-height: 1.4;
    text-align: justify;
    text-justify: inter-word;
    width: 100%;
  }

  /* UPDATED: 75% sized images */
  .split-row img.half-size {
    width: 75%;
    margin: 0 auto;
  }

  /* Two images side-by-side */
  .two-image-row {
    width: 90%;
    margin: 0 auto;
    display: flex;
    gap: 10px;
    justify-content: space-between;
    align-items: stretch;
  }
  .two-image-row .img-col {
    width: 50%;
    text-align: center;
    display: flex;
    align-items: stretch;
  }
  .two-image-row .img-col img {
    width: 100%;
    height: 260px;
    object-fit: cover;
    border-radius: 8px;
    display: block;
    margin: 0;
  }

  .two-image-caption {
    width: 90%;
    margin: 10px auto 0 auto;
    font-size: 14px;
    text-align: justify;
    text-justify: inter-word;
    line-height: 1.4;
  }

  /* Responsive stacking */
  @media (max-width: 900px) {
    .split-row {
      flex-direction: column;
      align-items: stretch;
    }
    .split-col {
      width: 100%;
    }
    /* Keep slightly larger on mobile so it doesn't look tiny */
    .split-row img.half-size {
      width: 85%;
    }
    .two-image-row {
      flex-direction: column;
    }
    .two-image-row .img-col {
      width: 100%;
    }
    .two-image-row .img-col img {
      height: auto;
    }
  }
</style>

<div class="page-content">

  <!-- NEW TOP CONTAINER (December 2025 Updates) -->
  <div class="container">
    <img src="/assets/images/december2025_updates.png" alt="December 2025 Updates">
    <div class="note-italic">~ for more information on the following updates, please click their corresponding image ~</div>
    <div class="divider"></div>
<!-- 1 -->
    <div class="welcome-title">Ben Becomes the New Dean of the Rosenstiel School</div>
    <div class="divider"></div>
    <div class="split-row">
      <div class="split-col">
        <a href="https://news.miami.edu/stories/2025/07/rosenstiel-school-sets-a-new-course.html" target="_blank">
          <img src="/assets/images/news_2025_1.jpg" alt="Ben becomes the new dean">
        </a>
      </div>
      <div class="split-col">
        <div class="split-text-inner">
          Ben began his time at the Rosenstiel School back in 2007, and has since helped shape the careers of many scientists while contributing greatly to the weather and climate field. In August, Ben became the new dean of the Rosenstiel School. He succeeds Roni Avissar, who has served in that post since 2009. Congratulations, Ben!
        </div>
      </div>
    </div>
    <div class="divider"></div>
<!-- 2 -->
    <div class="welcome-title">New Kirtman Group Member: Tori Paige Sargent</div>
    <div class="divider"></div>
    <div class="split-row">
      <div class="split-col">
        <div class="split-text-inner">
          Tori is a first-year Ph.D. student focusing on understanding how global climate dynamics drive local coastal impacts to better inform adaptation and resilience strategies. Her research interests include coastal climate dynamics, downscaling climate models for regional applications, sub-seasonal predictions and exploring how sea level variability and extreme heat affect coastal communities. She is passionate about linking solution-driven climate research with regional adaptation, especially by integrating uncertainty into planning and improving communication with local officials. She grew up in Hollywood, Florida and has been a Miami Beach resident for over a decade, who loves spending time outdoors, rollerblading along the Beachwalk, exploring local parks, trying the newest restaurants, practicing yoga, photographing nature, hosting daytime disco parties on sunny days, and enjoying life with her husband and their dog.
        </div>
      </div>
      <div class="split-col">
        <!-- UPDATED to 75% via CSS -->
        <img class="half-size" src="/assets/images/tori.png" alt="Tori Paige Sargent">
      </div>
    </div>
    <div class="divider"></div>
<!-- 3 -->
    <div class="welcome-title">Cait Presented at the 5th Annual CLIVAR Climate Dynamics Panel Workshop</div>
    <div class="divider"></div>
    <div class="split-row">
      <div class="split-col">
        <a href="https://www.clivar.org/events/clivar-climate-dynamics-panel-5th-annual-workshop__;!!KVu0SnhVq1hAFvslES2Y!LqDjPG0PGJzsHRUbJl_5zcRvJq9B3aQZAkamPJjtoTHhvPP-CzmcGN42vqkKRbQtMq0QX1GdAl6ZZAErTdczNIbn__Q$" target="_blank">
          <img src="/assets/images/updates_2025_2.png" alt="CLIVAR Climate Dynamics Panel Workshop">
        </a>
      </div>
      <div class="split-col">
        <div class="split-text-inner">
          In February, Cait Martinez won late-stage funding to travel, attend, and present her poster titled "An Advanced Framework for Disentangling Deterministic Dynamics and Stochastic Processes in ENSO Predictability" at the 5th Annual CLIVAR Climate Dynamics Panel Workshop in Lorne, VIC, Australia.
        </div>
      </div>
    </div>
    <div class="divider"></div>
<!-- 4 -->
    <div class="welcome-title">Kirtman Group Publication is Now Available!</div>
    <div class="divider"></div>
    <div class="split-row">
      <div class="split-col">
        <div class="split-text-inner">
          Kirtman group members worked together to develop a global atmospheric modeling framework that blends powerful research capabilities with accessibility for students and scientists alike. Written entirely in Python, a high-level, general-purpose programming language, and designed to run on an interactive Jupyter Notebook, allowing anyone with a standard laptop to explore cutting-edge climate experiments.
        </div>
      </div>
      <div class="split-col">
        <a href="https://news.miami.edu/rosenstiel/stories/2025/09/university-of-miami-scientists-launch-accessible-global-climate-modeling-framework.html" target="_blank">
          <img src="/assets/images/publication.jpg" alt="Kirtman group publication available">
        </a>
      </div>
    </div>
    <div class="divider"></div>
<!-- 5 -->
    <div class="welcome-title">Karen &amp; Victoria Graduated in the Summer</div>
    <div class="divider"></div>
    <div class="split-row">
      <div class="split-col">
        <!-- UPDATED to 75% via CSS -->
        <img class="half-size" src="/assets/images/K_V_GRAD.png" alt="Karen &amp; Victoria Graduated">
      </div>
      <div class="split-col">
        <div class="split-text-inner">
          Both Karen Papazian and Victoria Schoenwald have completed their Ph.D.’s. Victoria’s dissertation is titled Understanding Regional Sea Level Rise Acceleration Along the North American Eastern Seaboard, and Karen’s is An Idealized Study of Cold Air Outbreaks. They have both begun their next chapter as Postdoc’s with Ben!
        </div>
      </div>
    </div>
    <div class="divider"></div>
<!-- 6 -->
    <div class="welcome-title">Cait was Named an IDSC 2024-25 Fellow</div>
    <div class="divider"></div>
    <div class="split-row">
      <div class="split-col">
        <div class="split-text-inner">
          Cait Martinez was an IDSC Fellow 2024-25, and presented her capstone project titled "A Machine Learning-based Interactive Ensemble for ENSO" on April 24, 2025. She was featured in the Fall 2025 IDSC Magazine.
        </div>
      </div>
      <div class="split-col">
        <a href="https://idsc.miami.edu/magazine/fall-2025/idsc-fellow-cait-martinez-finds-confidence-and-community/" target="_blank">
          <img src="/assets/images/updates_2025_4.png" alt="IDSC Fellow Cait Martinez">
        </a>
      </div>
    </div>
    <div class="divider"></div>
<!-- 7 -->
    <div class="welcome-title">In November, Kelsey Gave a TEDx Talk</div>
    <div class="divider"></div>
    <div class="split-row">
      <div class="split-col">
        <a href="https://www.youtube.com/watch?v=AwJ4Zeq4slM__;!!KVu0SnhVq1hAFvslES2Y!LqDjPG0PGJzsHRUbJl_5zcRvJq9B3aQZAkamPJjtoTHhvPP-CzmcGN42vqkKRbQtMq0QX1GdAl6ZZAErTdczb70Hsy0$" target="_blank">
          <img src="/assets/images/updates_2025_5.png" alt="Kelsey TEDx Talk">
        </a>
      </div>
      <div class="split-col">
        <div class="split-text-inner">
          On the TEDxUniversityofDelaware stage, Kelsey Malloy aimed to share climate science through storytelling of climate’s fingerprint on human history and how modern climate change is both a unique, critical challenge and defining opportunity for society.
        </div>
      </div>
    </div>
    <div class="divider"></div>
<!-- 8 -->
    <div class="welcome-title">Marybeth was Featured in the IDSC Magazine</div>
    <div class="divider"></div>
    <div class="split-row">
      <div class="split-col">
        <div class="split-text-inner">
          Marybeth Arcodia has re-joined the University of Miami as an assistant professor. To read more about her academic and professional journey, this IDSC magazine article outlines her career path and research interests.
        </div>
      </div>
      <div class="split-col">
        <a href="https://idsc.miami.edu/magazine/fall-2025/marybeth-arcodia-applies-xai-to-extreme-weather-systems/" target="_blank">
          <img src="/assets/images/updates_2025_6.png" alt="Marybeth IDSC feature">
        </a>
      </div>
    </div>
    <div class="divider"></div>
<!-- 9 -->
    <div class="welcome-title">Cait Attended the 2025 ENSO Winter School</div>
    <div class="divider"></div>
    <div class="split-row">
      <div class="split-col">
        <a href="https://sites.google.com/hawaii.edu/enso-winter-school-2025/" target="_blank">
          <img src="/assets/images/updates_2025_7.png" alt="ENSO Winter School 2025">
        </a>
      </div>
      <div class="split-col">
        <div class="split-text-inner">
          In March 2025, Cait Martinez attended the ENSO Winter School 2025 at the University of Hawaii at Manoa.
        </div>
      </div>
    </div>
    <div class="divider"></div>
<!-- 10 -->
    <div class="welcome-title">Ben Received the Distinguished Faculty Scholar Award</div>
    <div class="divider"></div>
    <div class="split-row">
      <div class="split-col">
        <div class="split-text-inner">
          Ben received the Distinguished Faculty Scholar Award on Monday, March 31, during the Faculty Senate Awards Ceremony. The Distinguished Faculty Scholar Award recognizes either a single outstanding scholarly achievement or a lifetime of distinguished accomplishment in any area of research or creative activity. Award winners are nominated by faculty of the University and are selected by a committee. Congratulations, Ben!
        </div>
      </div>
      <div class="split-col">
        <a href="https://news.miami.edu/stories/2025/03/el-nino-inspires-a-young-mans-passion-for-science.html" target="_blank">
          <img src="/assets/images/news_2025_3.jpg" alt="Distinguished Faculty Scholar Award">
        </a>
      </div>
    </div>
    <div class="divider"></div>
<!-- 11 -->
    <div class="welcome-title">Kirtman Group Members Attend NOAA EPIC’s UIFCW 2025 Event</div>
    <div class="divider"></div>
    <div class="two-image-row">
      <div class="img-col">
        <img src="/assets/images/updates_2025_8.jpg" alt="UIFCW 2025 photo 1">
      </div>
      <div class="img-col">
        <img src="/assets/images/updates_2025_9.jpg" alt="UIFCW 2025 photo 2">
      </div>
    </div>
    <div class="two-image-caption">
      Pictures are from the yearly NOAA EPIC's UIFCW2025 event - NOAA Earth Prediction Innovation Center, yearly Unified Innovations in Forecast Capabilities Workshop. A couple of posters were presented there, highlighting some collaborative efforts between NOAA EPIC (including Natalie Perlin and some EPIC team members), University of Miami (Ben Kirtman), and Sonoma Tech (Samantha Kramer).
    </div>
    <div class="divider"></div>
<!-- 12 -->
    <div class="welcome-title">Cait Gives COMPASS Talk &amp; Lecture</div>
    <div class="divider"></div>
    <div class="full-width-text">
      In November, Cait Martinez gave a COMPASS talk titled "Diagnosing Ocean Memory in ENSO Initial Conditions: Insights from CESM2 Release Experiments". Additionally, she was accepted as a University of Miami Graduate School Teaching Academy Fellow. On Thursday, November 20, 2025, she gave a lecture titled "ENSO and cloud microphysics" to Cassie Gaston's ATM 305 Atmospheric Thermodynamics class.
    </div>
    <div class="divider"></div>
  </div>

  <!-- EXISTING CONTAINER -->
  <div class="container">
    <img src="/assets/images/update1.jpg" alt="Descriptive Image">
    <div class="divider"></div>
    <div class="welcome-title">Welcome New Group Members</div>
    <div class="divider"></div>
    <img src="/assets/images/update1_1.jpg" alt="Another Descriptive Image">
    <div class="divider"></div>
    <div class="welcome-title">Ben Participated in a Field Hearing for Congresswoman Debbie Wasserman Schultz</div>
    <div class="divider"></div>
    <a href="https://www.sun-sentinel.com/2024/09/15/climate-problems-are-causing-financial-problems-in-south-florida-panel-says/" target="_blank">
      <img src="/assets/images/update1_3.jpg" alt="Ben participating in field hearing">
    </a>
    <div class="full-width-text">
      Ben participated in a field hearing for Congresswoman Debbie Wasserman Schultz where he discussed how climate issues are causing financial issues in South Florida. To read more, click on the image above.
    </div>
    <div class="divider"></div>
  </div>

</div>
