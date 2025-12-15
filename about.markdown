---
layout: page-people
title: People
permalink: /people/
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
  /* Custom class to limit to two columns for Lily and Theresia */
.two-column-row .column {
  max-width: calc(50% - 20px); /* Two columns per row */
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

<div class="container">
  <div class="content-wrapper" style="padding-top: 20px;">
      <img src="/assets/images/b_kirt_dean.jpg" alt="Ben Kirtman">
      <div>
          <h1>Ben Kirtman, PhD</h1>
          <p>Professor of Atmospheric Sciences</p>
          <p>William R. Middelthon III Endowed Chair in Earth Sciences</p>
          <p style="margin-top: 10px;" class="lightgreen">
              <a href="https://cimas.earth.miami.edu/">Director: Cooperative Institute for Marine & Atmospheric Studies</a>
          </p>
          <p style="margin-top: 10px;" class="navy">
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
      <p class="navy">Associate Scientist</p>
      <p class="navy">University of Miami, Rosenstiel School</p>
      <p class="purple">Institute for Data Science & Computing</p>
      <p>My research interests include ENSO dynamics & predictability, Earth system model development, High-resolution global climate modeling and the role of ocean fronts and eddies in subseasonal to decadal prediction.</p>
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

<div class="new-container">
  <h2>Graduate Students</h2>

  <!-- Row 1 -->
  <div class="columns">
    <div class="column">
      <img src="/assets/images/caitmartinez.jpg" alt="Caitlin Martinez">
      <p class="name">Caitlin Martinez</p>
      <p class="navy">PhD Student</p>
      <p class="purple">Contact Email: <a href="mailto:caitmartinez@miami.edu">caitmartinez@miami.edu</a></p>
      <p>My research aims to disentangle the dual influences of deterministic dynamics and stochastic processes on ENSO evolution and predictability, and to enhance our understanding of the mechanisms limiting ENSO predictability in fully coupled models. My research interests include high-resolution global climate modeling, climate variability and predictability, and air-sea interactions. I balance my time with backpacking, skiing, and paddle boarding with my family.</p>
    </div>

  <div class="column">
      <img src="/assets/images/josiah.jpg" alt="Josiah Kaiser">
      <p class="name">Josiah Kaiser</p>
      <p class="navy">PhD Student</p>
      <p class="purple">Contact Email: <a href="mailto:jmk433@earth.miami.edu">jmk433@earth.miami.edu</a></p>
      <p>I am a graduate student working with Dr. Ben Kirtman and Dr. Emily Becker. I am most interested in researching climate change and developing long term differential models to predict, and hopefully inform policy on, climate change, especially in high impact areas. Outside of research I enjoy creating music and learning mathematics. I generally just like to try new things and meet new people!</p>
    </div>

  <div class="column">
      <img src="/assets/images/christina.jpg" alt="Christina Schuler">
      <p class="name">Christina Schuler</p>
      <p class="navy">PhD Student</p>
      <p class="purple">Contact Email: <a href="mailto:cts123@earth.miami.edu">cts123@earth.miami.edu</a></p>
      <p>My research interests include hurricanes, climate science, and coastal storm climatology. Some of my hobbies outside of school are playing violin, writing, and tracking storms across South Florida.</p>
    </div>
  </div>

  <!-- Row 2 -->
  <div class="columns">
    <div class="column">
      <img src="/assets/images/ian.jpg" alt="Ian Gifford">
      <p class="name">Ian Gifford</p>
      <p class="navy">PhD Student</p>
      <p class="purple">Contact Email: <a href="mailto:igifford@earth.miami.edu">igifford@earth.miami.edu</a></p>
      <p>I am a graduate student working with Dr. Ben Kirtman and Dr. Emily Becker. Anthropogenic climate change and its effects on the El Nino Southern Oscillation remains an open question. My research pertains to predictions of the impacts on terrestrial North America (temperature and precipitation) related to possible future ENSO changes.</p>
    </div>

  <div class="column">
      <img src="/assets/images/lily.jpg" alt="Lily Johnston">
      <p class="name">Lily Johnston</p>
      <p class="navy">PhD Student</p>
      <p class="purple">Contact Email: <a href="mailto:lilyjohnston@miami.edu">lilyjohnston@miami.edu</a></p>
      <p>I am interested in subseasonal to seasonal prediction and studying weather-climate interactions. I would like to improve forecast skill in the North American Multi-Model Ensemble (NMME) through model verification and use the model for seasonal climate prediction. In my free time I like running, crocheting and baking.</p>
    </div>

  <div class="column">
      <img src="/assets/images/theresia.jpg" alt="Theresia Phoa">
      <p class="name">Theresia Phoa</p>
      <p class="navy">PhD Student</p>
      <p class="purple">Contact Email: <a href="mailto:tbp32@miami.edu">tbp32@miami.edu</a></p>
      <p>I’m interested in analyzing downscaled climate model output, especially for tropical and subtropical regions. Outside of research, I enjoy hiking and watching basketball games.</p>
    </div>
  </div>

  <!-- Row 3 (Tori – image left, text right) -->
  <div class="content-wrapper" style="padding-top: 20px;">
    <img src="/assets/images/tori.png" alt="Tori Paige Sargent" class="smaller-image">

  <div>
      <p class="name">Tori Paige Sargent</p>
      <p class="navy">PhD Student</p>
      <p class="purple contact-email">
        Contact Email:
        <a href="mailto:t.sargent@miami.edu">t.sargent@miami.edu</a>
      </p>
      <p style="margin-top: 10px;">
        I am a first-year Ph.D. student focused on understanding how global climate dynamics drive local coastal impacts to better inform adaptation and resilience strategies. My research interests include coastal climate dynamics, downscaling climate models for regional applications, sub-seasonal predictions and exploring how sea level variability and extreme heat affect coastal communities. I am passionate about linking solution-driven climate research with regional adaptation, especially by integrating uncertainty into planning and improving communication with local officials. I grew up in Hollywood, Florida and have been a Miami Beach resident for over a decade, who loves spending time outdoors, rollerblading along the beachwalk, exploring local parks, trying the newest restaurants, practicing yoga, photographing nature, hosting daytime disco parties on sunny days, and enjoying life with my husband and our dog.
      </p>
    </div>
  </div>

</div>


<div class="new-container former-container">
  <h2>Former Undergraduate Members</h2>
  <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/daniel.jpg" alt="Daniel Perlin">
      <div>
          <h1>Daniel Perlin</h1>
          <p class="contact-email">Contact Email: <a href="mailto:dnlperlin@gmail.com">dnlperlin@gmail.com</a></p>
          <p class="italic" style="margin-top: 10px;">Graduated Spring 2021</p>
          <p style="margin-top: 10px;">Current Affiliation: Aeronautical Design Engineer, Skink Works, Lockheed Martin Advanced Development Programs</p>
          <p style="margin-top: 10px;">Undergraduate Research: With a personal interest in the application of machine learning to new fields, his undergraduate research focused on the development of a convolutional neural network model, using pattern recognition in climate model simulations to detect tropical cyclones.</p>
      </div>
  </div>
</div>

<div class="new-container former-container">
  <h2>Former Members</h2>
  <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/simge.jpg" alt="Dr. Simge Bilgen" style="width: 150px; height: auto;"> 
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Simge Bilgen</h1>
          <p class="contact-email" style="font-size: 14px;">Contact Email: <a href="mailto:sbilgen@rsmas.miami.edu">sbilgen@rsmas.miami.edu</a></p>
          <p style="margin-top: 10px; font-size: 14px;">PhD Work: My research focused on the role of ocean eddies in climate variability and change. I used climate models and observation to investigate the delayed warming of the Southern Ocean.</p>
      </div>
  </div>
  <hr style="border: 1px solid black; margin: 20px 0;">
  <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/kayla.jpg" alt="Dr. Kayla Besong" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Kayla Besong</h1>
          <p class="contact-email" style="font-size: 14px;">Contact Email: <a href="mailto:kayla.besong@noaa.gov">kayla.besong@noaa.gov</a></p>
          <p style="margin-top: 10px; font-size: 14px;">Current Affiliation: Pacific Tsunami Warning Center (PTWC)</p>
          <p style="margin-top: 10px; font-size: 14px;">PhD Work: My research focused on atmospheric blocking, with an emphasis on the North Atlantic region. I examined the effects of different blocking algorithms on data analysis, explored the relationship between atmospheric blocks and the North Atlantic Oscillation, and assessed how accurately blocks are represented in CESM.</p>
      </div>
  </div>
  <hr style="border: 1px solid black; margin: 20px 0;">
  <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/patrick.jpg" alt="Patrick Barrett" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Patrick Barrett</h1>
          <p class="contact-email" style="font-size: 14px;">Contact Email: <a href="mailto:pbarrett.business@gmail.com">pbarrett.business@gmail.com</a></p>
          <p style="margin-top: 10px; font-size: 14px;">Masters Work: looked at the impact of NAO, ENSO, and PDO on extreme precipitation across the North American region in observational data and climate forecast models.</p>
      </div>
  </div>
  <hr style="border: 1px solid black; margin: 20px 0;">
  <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/szandra.jpg" alt="Szandra Peter" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Szandra Peter</h1>
          <p style="margin-top: 10px; font-size: 14px;">Previous Work: Predictability of North American and European heat waves.</p>
      </div>
  </div>
    <hr style="border: 1px solid black; margin: 20px 0;">
    <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/kelsey.jpg" alt="Dr. Kelsey Malloy" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Kelsey Malloy</h1>
          <p class="contact-email" style="font-size: 14px;">Contact Email: <a href="mailto:kelsey.malloy@earth.miami.edu">kelsey.malloy@earth.miami.edu</a></p>
          <p style="margin-top: 10px; font-size: 14px;">Current Affiliation: Postdoctoral Research Scientist at Columbia University working with Dr. Mike Tippett on S2S predictability of severe convective storm risk and how that might be impacted by climate change.</p>
          <p style="margin-top: 10px; font-size: 14px;">PhD Work: My research focused on subseasonal-to-seasonal (S2S) predictability of U.S. summer hydroclimate through understanding large-scale dynamical influences on the Great Plains low-level jet.</p>
          <a href="https://kelseymalloy.github.io/" class="webpage-button">Webpage</a>

      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/natalie.jpg" alt="Dr. Natalie Perlin" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Natalie Perlin</h1>
          <p class="contact-email" style="font-size: 14px;">Contact Email: <a href="mailto:perlin.natalie@gmail.com">perlin.natalie@gmail.com</a></p>
          <p style="margin-top: 10px; font-size: 14px;">Current Affiliation: Sr. Systems Engineer, RedLine Performance Solutions, LLC. Working on NOAA's Earth Prediction Innovation Center (EPIC) project.</p>
          <p style="margin-top: 10px; font-size: 14px;">Natalie takes an active part in Unified Forecast System (UFS), UFS applications, and supporting software stack development, as well as computational systems support.</p>
          <p style="margin-top: 10px; font-size: 14px;">RSMAS Work: My research focused on climate studies with the Interactive Ensemble (IE) approach applications. Multi-century global simulations with the implemented IE allow highlighting the climate signal in the atmospheric teleconnections. Additionally, multiple realizations of the atmosphere coupled to a single ocean offer insights into the different possibilities of tropical waves and depressions developing over the identical ocean state.</p>
      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/kurt.jpg" alt="Dr. Kurt Hansen" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Kurt Hansen</h1>
          <p style="margin-top: 10px; font-size: 14px;">​​Current Affiliation: Postdoctoral Research Associate at the Naval Research Laboratory in Monterey, CA. He will be working on machine learning and subseasonal TC prediction under Matthew Janiga.</p>
          <p style="margin-top: 10px; font-size: 14px;">​​PhD work: explores sources of subseasonal predictability of Atlantic Tropical Cyclones.</p>
      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/marybeth.jpg" alt="Dr. Marybeth Arcodia" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Marybeth Arcodia</h1>
          <p style="margin-top: 10px; font-size: 14px;">​​Current Affiliation: Postdoctoral Research Associate at Colorado State University working with Dr. Libby Barnes, using explainable machine learning techniques to better understand the Earth's predictability on subseasonal to decadal timescales.</p>
          <p style="margin-top: 10px; font-size: 14px;">PhD work: using observations and a collection of climate models to study how MJO and ENSO teleconnections impact U.S. weather on subseasonal timescales, with a focus on extreme precipitation events.</p>
      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/wei.jpg" alt="Dr. Wei Zhang" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Wei Zhang</h1>
          <p style="margin-top: 10px; font-size: 14px;">​​Current Affiliation: Postdoctoral Research Associate at Princeton University/GFDL</p>
          <p style="margin-top: 10px; font-size: 14px;">PhD work: My research focused on using statistics and climate models to investigate the variability and predictability of the climate system over a decadal time scale.</p>
      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/sam.jpg" alt="Dr. Samantha Kramer" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Samantha Kramer</h1>
          <p style="margin-top: 10px; font-size: 14px;">Current Affiliation: Air Quality Data Scientist at Sonoma Technology in Petaluma, CA.</p>
          <p style="margin-top: 10px; font-size: 14px;">PhD work: My research focused on Saharan dust transport to Miami, Florida. </p>
      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/breanna.jpg" alt="Dr. Breanna Zavadoff" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Breanna Zavadoff</h1>
          <p class="contact-email" style="font-size: 14px;">Contact Email: <a href="mailto:b.zavadoff@gmail.com">b.zavadoff@gmail.com</a></p>
          <p style="margin-top: 10px; font-size: 14px;">Current Affiliation: Assistant Scientist at CIMAS</p>
          <p style="margin-top: 10px; font-size: 14px;">PhD work: One portion of my research encompassed studying the modulation of summertime North Atlantic anticyclonic Rossby wave breaking variability by the Pacific Decadal Oscillation. An additional part of my research focused on Atmospheric Rivers impacting Western Europe and how they are influenced dynamically through features such as anticyclonic Rossby wave breaking as well as thermodynamically in a changing climate.</p>
          <a href="https://bzavadoff.github.io/" class="webpage-button">Webpage</a>

      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/johnna.jpg" alt="Dr. Johnna Infanti" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Johnna Infanti</h1>
          <p style="margin-top: 10px; font-size: 14px;">Current Affiliation: Meteorologist in the Operational Prediction Branch at NOAAs Climate Prediction Center (CPC).</p>
      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/ray.jpg" alt="Dr. Ray Bell" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Ray Bell (Postdoc)</h1>
          <p style="margin-top: 10px; font-size: 14px;">Current Affiliation: Data Scientist Manager at DTN - leading a team working on weather data science products.</p>
      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/diane.jpg" alt="Dr. Diane Palko" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Diane Palko</h1>
          <p style="margin-top: 10px; font-size: 14px;">Current Affiliation: Info coming soon! </p>
      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/gino.jpg" alt="Dr. Gino Chen" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Gino Chen</h1>
          <p style="margin-top: 10px; font-size: 14px;">Current Affiliation: Working at Hewlett Packard Enterprise as a software developer. Also working on his own software company.</p>
      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/yu.jpg" alt="Dr. Yu Cheng" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr.​ Yu Cheng (PhD Student co-advised with Dr. Lisa Beal)</h1>
          <p style="margin-top: 10px; font-size: 14px;">Current Affiliation: Working as a Sr. Data Scientist with SFL Scientific - a consulting role, focusing on strategizing and implementing AI/ML solutions for clients.</p>
      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/sarah.jpg" alt="Dr. Sarah Larson" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Sarah Larson</h1>
          <p style="margin-top: 10px; font-size: 14px;">Current Affiliation: Assistant Professor Dept. of Marine, Earth, & Atmospheric Sciences​​, North Carolina State University</p>
          <a href="https://sarahmlarson.weebly.com/" class="webpage-button">Webpage</a>
      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/eunsil.jpg" alt="Dr. Eunsil Jung" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Eunsil Jung (Postdoc)</h1>
          <p style="margin-top: 10px; font-size: 14px;">Current Affiliation: Info coming soon!</p>
      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/dian.jpg" alt="Dr. Dian Putrasahan (Postdoc)" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Dian Putrasahan</h1>
          <p style="margin-top: 10px; font-size: 14px;">Current Affiliation: Research Scientist Max-Planck Institut für Meteorologie, Hamburg, Germany</p>
      </div>
  </div>
      <hr style="border: 1px solid black; margin: 20px 0;">
      <div class="content-wrapper" style="padding-top: 10px;">
      <img src="/assets/images/hosmay.jpg" alt="Dr. Hosmay Lopez" style="width: 150px; height: auto;">
      <div>
          <h1 style="font-size: 24px; font-weight: bold;">Dr. Hosmay Lopez</h1>
          <p style="margin-top: 10px; font-size: 14px;">Current Affiliation: Assistant Scientist Cooperative Institute for Marine and Atmospheric Studies, University of Miami NOAA/AOML/PHOD</p>
          <a href="https://www.aoml.noaa.gov/people/hosmay-lopez/" class="webpage-button">Webpage</a>
      </div>
  </div>
  
</div>
