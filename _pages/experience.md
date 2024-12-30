---
layout: archive
permalink: experience/
title: "My Work in Action"
author_profile: true
---
 
<div class="experience-item">
  <input type="checkbox" id="toggle1" class="toggle" />
  <label for="toggle1" class="experience-title">
    <strong>Student Research Assistant</strong>  
    <span><a href="https://red.osu.edu/team/" target="_blank">Rehabilitation Engineering Design Laboratory, OSU</a> | Sep 2024 – Present</span>
  </label>
  
  <div class="experience-description">
    <p class="preview">
      Spearheaded the automation of critical surveillance processes, cutting manual efforts by 80% and enabling real-time truck detection...
    </p>
    <p class="full-description">
      Spearheaded the automation of critical surveillance processes, cutting manual efforts by 80% and enabling real-time truck detection and tracking using PP-Yolo and Byte-Tracker models. Enhanced security operations by automating CCTV monitoring with OpenCV, implementing features to detect video blur, scene changes, time mismatches, video loss, and hard disk health issues, improving system reliability by 40%. Developed an OCR system with PaddleOCR, boosting skewed text recognition accuracy by 25%, and built predictive models for age, gender, and emotion detection, increasing image analysis accuracy by 30%.<br>Designed and deployed an end-to-end data processing pipeline integrating a ReactJS UI, FastAPI backend, MongoDB for data retrieval, RabbitMQ for efficient messaging, and Docker for containerization, accelerating data processing speeds by 50%. These innovations significantly improved operational efficiency, ensuring faster alerts and greater reliability in real-time tracking and security monitoring. This project reinforced my expertise in computer vision and automation while delivering measurable business impact and showcasing my ability to create scalable, high-performing solutions.
    </p>
  </div>
</div>

<style>
  /* Container for each experience item */
  .experience-item {
    margin-bottom: 20px;
  }

  /* Hidden checkbox for toggling */
  .toggle {
    display: none;
  }

  /* Styling the title label */
  .experience-title {
    cursor: pointer;
    font-size: 16px;
    font-weight: bold;
    color: #333;
    margin-bottom: 8px;
    display: inline-block;
  }

  .experience-title span {
    display: block;
    font-size: 14px;
    color: #555;
    margin-top: 4px;
  }

  /* Description styling */
  .experience-description {
    background-color: #f9f9f9;
    padding: 10px 15px;
    border-left: 5px solid #ba0c2f; /* Accent color */
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    margin-top: 10px;
  }

  /* Initially show only the preview text */
  .experience-description .preview {
    font-size: 15px;
    line-height: 1.6;
    color: #333;
    margin-bottom: 0;
    display: block;
  }

  /* Full description hidden initially */
  .experience-description .full-description {
    display: none;
    font-size: 15px;
    line-height: 1.6;
    color: #333;
    margin-top: 5px;
  }

  /* When checkbox is checked, toggle visibility */
  .toggle:checked ~ .experience-description .preview {
    display: none;
  }

  .toggle:checked ~ .experience-description .full-description {
    display: block;
  }

  /* Link styling */
  .experience-title a {
    text-decoration: none;
    color: #ba0c2f;
    font-weight: normal;
  }

  .experience-title a:hover {
    text-decoration: underline;
  }

  /* Professional color scheme */
  .experience-title, .experience-description p {
    color: #333;
  }
</style>
