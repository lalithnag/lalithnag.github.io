---
layout: page
title: Talks
permalink: /talks/
order: 2
---

<style>
/* Tooltip container */
.image-tooltip-container {
    position: relative;
    display: inline-block;
    cursor: pointer;
}

/* Tooltip image */
.image-tooltip {
    visibility: hidden;
    max-width: 300px; /* Set a max-width for the tooltip container */
    max-height: 300px; /* Set a max-height to avoid overflow */
    background-color: #fff;
    border: 1px solid #ccc;
    border-radius: 5px;
    padding: 5px;
    position: absolute;
    z-index: 1;
    bottom: 125%; /* Position above the text */
    left: 50%;
    transform: translate(-50%, -10px); /* Center the tooltip horizontally and adjust vertical position */
    opacity: 0;
    transition: opacity 0.3s;
    overflow: hidden; /* Ensure image doesn't overflow the tooltip */
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Optional: Add shadow for better visibility */
}

.image-tooltip img {
    width: 100%; /* Make image fit within the tooltip container */
    height: auto; /* Maintain aspect ratio */
    display: block; /* Remove extra space below the image */
}

/* Tooltip visibility on hover */
.image-tooltip-container:hover .image-tooltip {
    visibility: visible;
    opacity: 1;
}

/* Arrow below the tooltip */
.image-tooltip::after {
    content: "";
    position: absolute;
    top: 100%; /* Arrow below the tooltip */
    left: 50%;
    margin-left: -5px;
    border-width: 5px;
    border-style: solid;
    border-color: #fff transparent transparent transparent;
}

/* Adjust tooltip for small screens */
@media (max-width: 600px) {
    .image-tooltip {
        max-width: 80vw; /* Set a maximum width relative to viewport width */
        max-height: 80vh; /* Set a maximum height relative to viewport height */
        left: 50%; /* Center tooltip horizontally */
        transform: translate(-50%, -10px); /* Adjust vertical position */
        margin: 0 auto; /* Center the tooltip horizontally */
        right: 0;
    }
}
</style>

#### Science slams <span title="A science slam is a ten-minute talk to a general audience (kids, older people, people from completely different fields, etc.), where you are expected to present your research in the most engaging and humorous way possible. Originating from poetry slams, popular in Germany, you can think of it as 'TED-talk meets standup'." style="color: #808080; margin-top: 10px; font-size: 14px;"> (?) </span>

<p style="font-size: 14px;">
I stumbled upon this unique format a few years ago, and since then I have come to love it as a great tool for scientific dissemination. It is inspiring everytime, to get on-stage to a huge crowd that is eager to learn about how your research impacts their life. Over the last years, I have had the chance to <i>slam</i> across many beautiful locations in Germany, and in the process meet brilliant fellow researchers who are working on interesting topics. I can only recommend for you to go attend one in your city if you can!
</p>

<figure>
    <img src="/assets/science_slam_collage.png" alt="Alt text">
    <figcaption style="font-size: 12px;"> 
        <small> Impressions from my slams in the past year. Picture credits go to Science and Stories GmbH, and Naturkundemuseum Stuttgart. </small>
    </figcaption>
</figure>

<p style="color: #808080; font-size: 14px;"> Oct 2024 - Stuttgart, 
<a href="https://www.science-slam.com/termine/stuttgart/theaterhaus-stuttgart-10-oktober-2024/" target="_blank" style="color: #808080; text-decoration: underline;" dec> Vorentschied Süd - Deutsche Science Slam Meisterschaft 2024 </a> (Wish me luck!) 
<br> <span style="color: black;"> Here's one of my recent slams in Heidelberg, which won first place: </span> </p>

<div style="margin-bottom: 20px;"></div>

  <iframe width="560" height="315" 
          src="https://www.youtube.com/embed/turNa25TbqI?si=gGKsS0yBqfS4qnHq" 
          title="YouTube video player" frameborder="0" 
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
          referrerpolicy="strict-origin-when-cross-origin"
          allowfullscreen>
  </iframe>


<div style="margin-bottom: 20px;"></div>
<p style="font-size: 14px;"> Get in touch with me, if you would like to engage me as a speaker. Anyway, back to academics, here's a selected list of my scientific/invited talks :) </p>

#### Selected talks

<ol style="font-size: 14px;">
  <li style="color: #808080">
    <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Burger, L., Wang, C., Grizelj, A., Karl, R., Chen, J., Fischer, S., Brand, J., Marx, J., Romano, G., Karck, M., De Simone, R., Engelhardt, S. <span style="color: black;">AI and AR support for minimally invasive Mitral Valve Repair.</span> Poster and talk at Informatics for Life annual meeting in Heidelberg, Germany, 2022.
    <span class="image-tooltip-container">
      <span style="color: black; text-decoration: underline;"> Winner, Best Poster Award</span>
        <span class="image-tooltip">
            <img src="/assets/IFL2022_2.jpeg">
        </span>
    </span>
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Burger, L., Wang, C., Grizelj, A., Karl, R., Chen, J., Fischer, S., Brand, J., Marx, J., Romano, G., Karck, M., De Simone, R., Engelhardt, S. <span style="color: black;">AI and AR based computational support for minimally invasive Mitral Valve Repair.</span> Talk at Informatics for Life annual meeting in 
    <span class="image-tooltip-container">
      <span> Heidelberg, Germany, 2023. </span>
        <span class="image-tooltip">
            <img src="/assets/IFL2023.jpeg">
        </span>
    </span>
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Burger, L., Wang, C., Grizelj, A., Kapusta, M., Karl, R., Chen, J., Fischer, S., Brand, J., Marx, J., Romano, G., Karck, M., De Simone, R., Engelhardt, S. <span style="color: black;">AI and AR based computational support for minimally invasive Mitral Valve Repair.</span> Talk at 26th International Conference on Medical Image Computing and Computer Assisted Intervention,
    <span class="image-tooltip-container">
      Vancouver, Canada 2023.
        <span class="image-tooltip">
            <img src="/assets/MICCAI2023.jpeg">
        </span>
    </span>
    <div style="margin-bottom: 12px;"></div>

    You can also view this short talk online 
    <div style="margin-bottom: 12px;"></div>

    <iframe width="560" height="315" src="https://www.youtube.com/embed/Gxmc3UokrKU?si=lK1fEZEre7yf6cgQ" 
    title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; 
    encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen> 
    </iframe>

    
  </li>

</ol>  