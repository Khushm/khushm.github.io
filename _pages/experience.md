---
layout: archive
permalink: experience/
title: "My Work in Action"
author_profile: true
---
 
<div class="timeline-container">
  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <h3 class="timeline-title">Student Research Assistant</h3>
      <p class="timeline-duration">Rehabilitation Engineering Design Laboratory, OSU | Sep 2024 – Present</p>
      <p class="timeline-description">Spearheaded the automation of critical surveillance processes, cutting manual efforts by 80% and enabling real-time truck detection and tracking using PP-Yolo and Byte-Tracker models. Enhanced security operations by automating CCTV monitoring with OpenCV, implementing features to detect video blur, scene changes, time mismatches, video loss, and hard disk health issues, improving system reliability by 40%. Developed an OCR system with PaddleOCR, boosting skewed text recognition accuracy by 25%, and built predictive models for age, gender, and emotion detection, increasing image analysis accuracy by 30%.
      Designed and deployed an end-to-end data processing pipeline integrating a ReactJS UI, FastAPI backend, MongoDB for data retrieval, RabbitMQ for efficient messaging, and Docker for containerization, accelerating data processing speeds by 50%. These innovations significantly improved operational efficiency, ensuring faster alerts and greater reliability in real-time tracking and security monitoring. This project reinforced my expertise in computer vision and automation while delivering measurable business impact and showcasing my ability to create scalable, high-performing solutions.</p>
    </div>
  </div>
  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <h3 class="timeline-title">Student Teaching Assistant</h3>
      <p class="timeline-duration">Department of Computer Science and Engineering, OSU | Jan 2024 – May 2024</p>
      <p class="timeline-description">Led lab sessions and assisted in the preparation and delivery of course materials for undergraduate students. Facilitated learning through direct instruction, workshops, and one-on-one mentoring, ensuring students understood complex concepts in rehabilitation engineering. Collaborated with professors to evaluate student projects and provided feedback to help enhance the quality of research and development in the field. Managed the coordination of lab schedules, demonstrations, and hands-on sessions for various experimental setups. Supported ongoing research projects related to assistive technologies and rehabilitation tools, contributing to both theoretical and applied research that has the potential to improve the quality of life for individuals with disabilities.</p>
    </div>
  </div>
  <p style="text-align: center; font-size: 14px; color: #555; margin-top: 20px;">
    Click or tap a role to read more details.
  </p>
</div>

<style>
  .timeline-container {
    position: relative;
    padding: 20px 0;
  }

  .timeline-item {
    display: flex;
    align-items: flex-start;
    margin-bottom: 30px;
  }

  .timeline-dot {
    width: 12px;
    height: 12px;
    background-color: #ba0c2f;
    border-radius: 50%;
    margin-right: 15px;
    position: relative;
    top: 5px;
  }

  .timeline-content {
    background: #f4f4f9;
    border-left: 4px solid #ba0c2f;
    padding: 10px 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    flex: 1;
  }

  .timeline-title {
    font-size: 18px;
    font-weight: bold;
    color: #333;
    margin: 0;
    cursor: pointer;
    position: relative;
  }

  .timeline-title:after {
    content: " ▸";
    font-size: 14px;
    transition: transform 0.2s;
  }

  .timeline-item.open .timeline-title:after {
    content: " ▾";
    transform: rotate(90deg);
  }

  .timeline-duration {
    font-size: 14px;
    color: #555;
    margin: 5px 0 10px;
  }

  .timeline-description {
    display: none;
    font-size: 14px;
    color: #333;
    line-height: 1.6;
    margin-top: 10px;
  }

  .timeline-item.open .timeline-description {
    display: block;
  }
</style>
