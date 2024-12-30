---
layout: archive
permalink: experience/
title: "My Work in Action"
author_profile: true
---

/* Collapsible button */
.collapsible {
  background-color: #f1f1f1;
  color: #444;
  cursor: pointer;
  padding: 10px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
  border-radius: 5px;
  margin: 10px 0;
}

.collapsible:hover {
  background-color: #ddd;
}

/* The content (hidden by default) */
.content {
  padding: 0 10px;
  display: none;
  overflow: hidden;
  background-color: #f9f9f9;
  border-left: 3px solid #ddd;
}

/* Add some margin and padding to job descriptions */
.job p {
  margin: 0;
  padding: 5px 0;
}


<div class="job">
  <h3>Student Research Assistant</h3>
  <p><em><a href="https://red.osu.edu/team/">Rehabilitation Engineering Design Laboratory, OSU</a></em> | Sep 2024 – Present</p>
  <p><strong>Summary:</strong> I am currently involved in researching rehabilitation engineering solutions for individuals with disabilities...</p>
  
  <button class="collapsible">Key Responsibilities</button>
  <div class="content">
    <p>I collaborate with a team of engineers and healthcare professionals to develop assistive technologies that improve mobility for wheelchair users...</p>
  </div>
  
  <button class="collapsible">Challenges and Impact</button>
  <div class="content">
    <p>One major challenge was overcoming the design constraints of low-cost, portable devices, which we successfully addressed through innovative material usage...</p>
  </div>
  
  <button class="collapsible">Technologies and Skills Used</button>
  <div class="content">
    <p>The project involved using various technologies such as Python, TensorFlow, and MATLAB for data analysis and device prototyping...</p>
  </div>
</div>

// Get all collapsible buttons
var coll = document.getElementsByClassName("collapsible");

// Add event listener for each collapsible button
for (var i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  });
}


