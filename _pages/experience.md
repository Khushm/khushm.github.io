---
layout: archive
permalink: experience/
title: "My Work in Action"
author_profile: true
---


# My Work Experience

**Student Research Assistant**  
*[Rehabilitation Engineering Design Laboratory, OSU](https://red.osu.edu/team/)* | **Sep 2024 – Present**  

<div class="experience-description">
  This is a brief summary of the job. For more details, click below to expand and read the full description.
</div>

<button class="read-more-btn">Read More</button>
<div class="full-description">
  I work with a team of engineers to design and prototype assistive devices, leveraging my knowledge in rehabilitation engineering and data analysis. Additionally, I collaborate with healthcare professionals to ensure the designs meet practical needs and are accessible to a wider audience.
  <br><br>
  My role also involves conducting user testing, analyzing feedback, and iterating on the designs to ensure continuous improvement. I have gained hands-on experience with designing prototypes and working with interdisciplinary teams to bring research ideas to life.
</div>

---

**Student Teaching Assistant**  
*[Rehabilitation Engineering Design Laboratory, OSU](https://cse.osu.edu/)* | **Sep 2024 – Present**  

<div class="experience-description">
  This is a brief summary of the job. For more details, click below to expand and read the full description.
</div>

<button class="read-more-btn">Read More</button>
<div class="full-description">
  I assist in organizing course material, conducting lab sessions, and providing hands-on guidance to students in projects related to assistive technologies. My responsibilities include grading assignments, helping with student queries, and ensuring smooth functioning of the course materials.
  <br><br>
  Additionally, I have worked with the professor to integrate new technologies into the curriculum, offering students the opportunity to work on cutting-edge projects related to rehabilitation engineering.
</div>

---

<style>
  .experience-description {
    font-size: 16px;
    margin-bottom: 10px;
  }

  .read-more-btn {
    background-color: #007acc;
    color: white;
    padding: 8px 15px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-bottom: 10px;
  }

  .read-more-btn:hover {
    background-color: #005fa3;
  }

  .full-description {
    display: none;
    font-size: 15px;
    margin-top: 10px;
    background-color: #f9f9f9;
    padding: 10px;
    border-left: 3px solid #ddd;
  }
</style>

<script>
  // Get all "Read More" buttons
  const buttons = document.querySelectorAll(".read-more-btn");

  // Add event listener to each "Read More" button
  buttons.forEach((button) => {
    button.addEventListener("click", () => {
      const fullDescription = button.nextElementSibling;
      if (fullDescription.style.display === "block") {
        fullDescription.style.display = "none";
        button.textContent = "Read More";
      } else {
        fullDescription.style.display = "block";
        button.textContent = "Read Less";
      }
    });
  });
</script>
