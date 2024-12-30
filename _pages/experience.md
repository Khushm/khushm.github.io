---
layout: archive
permalink: experience/
title: "My Work in Action"
author_profile: true
---

<input type="checkbox" id="section1" class="collapse-toggle">
<label for="section1" class="collapse-label">Click to expand</label>
<div class="collapse-content">
  <p>Your long content goes here.</p>
</div>


<div class="experience-item">
  <div class="experience-title">
    <strong>Student Research Assistant</strong>  
    <span><a href="https://red.osu.edu/team/" target="_blank">Rehabilitation Engineering Design Laboratory, OSU</a> | Sep 2024 – Present</span>
  </div>
  
  <div class="experience-description">
    <p>
      Spearheaded the automation of critical surveillance processes, cutting manual efforts by 80% and enabling real-time truck detection and tracking using PP-Yolo and Byte-Tracker models. Enhanced security operations by automating CCTV monitoring with OpenCV, implementing features to detect video blur, scene changes, time mismatches, video loss, and hard disk health issues, improving system reliability by 40%. Developed an OCR system with PaddleOCR, boosting skewed text recognition accuracy by 25%, and built predictive models for age, gender, and emotion detection, increasing image analysis accuracy by 30%.
    </p>
    <p>
      Designed and deployed an end-to-end data processing pipeline integrating a ReactJS UI, FastAPI backend, MongoDB for data retrieval, RabbitMQ for efficient messaging, and Docker for containerization, accelerating data processing speeds by 50%. These innovations significantly improved operational efficiency, ensuring faster alerts and greater reliability in real-time tracking and security monitoring. This project reinforced my expertise in computer vision and automation while delivering measurable business impact and showcasing my ability to create scalable, high-performing solutions.
    </p>
  </div>
</div>

<div class="experience-item">
  <div class="experience-title">
    <strong>Student Teaching Assistant</strong>  
    <span><a href="https://cse.osu.edu/" target="_blank">Rehabilitation Engineering Design Laboratory, OSU</a> | Sep 2024 – Present</span>
  </div>
  
  <div class="experience-description">
    <p>
      Led lab sessions and assisted in the preparation and delivery of course materials for undergraduate students. Facilitated learning through direct instruction, workshops, and one-on-one mentoring, ensuring students understood complex concepts in rehabilitation engineering. Collaborated with professors to evaluate student projects and provided feedback to help enhance the quality of research and development in the field.
    </p>
    <p>
      Managed the coordination of lab schedules, demonstrations, and hands-on sessions for various experimental setups. Supported ongoing research projects related to assistive technologies and rehabilitation tools, contributing to both theoretical and applied research that has the potential to improve the quality of life for individuals with disabilities.
    </p>
  </div>
</div>

<style>
  .collapse-content {
  display: none;
}

.collapse-toggle:checked + .collapse-label + .collapse-content {
  display: block;
}

.collapse-label {
  cursor: pointer;
  font-weight: bold;
  color: #007acc;
}

.collapse-label:hover {
  text-decoration: underline;
}

  
  /* Container for each experience item */
  .experience-item {
    margin-bottom: 40px; /* Space between experience entries */
  }

  /* Title of the experience with job role and organization */
  .experience-title {
    font-size: 16px;
    font-weight: bold;
    color: #333;
    margin-bottom: 8px;
  }

  .experience-title span {
    display: block;
    font-size: 14px;
    color: #555;
    margin-top: 4px;
  }

  /* Styling the experience description */
  .experience-description {
    background-color: #f9f9f9; /* Light background for readability */
    padding: 15px;
    border-left: 5px solid #007acc; /* Accent color for visual interest */
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }

  /* Paragraph styling inside description */
  .experience-description p {
    font-size: 15px;
    line-height: 1.6;
    color: #333;
    margin-bottom: 12px; /* Space between paragraphs */
  }

  .experience-description p:last-child {
    margin-bottom: 0; /* No margin on last paragraph */
  }

  /* Link styling */
  .experience-title a {
    text-decoration: none;
    color: #007acc;
    font-weight: normal;
  }

  .experience-title a:hover {
    text-decoration: underline;
  }
</style>
