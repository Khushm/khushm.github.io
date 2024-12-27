---
layout: archive
permalink: projects/
title: "My Notable Projects"
author_profile: true
---

<style>
  .projects-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: space-evenly;
  }

  .project-card {
    background: #f9f9f9;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 15px;
    width: 300px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    text-align: center;
    transition: transform 0.3s ease;
    height: 350px; /* Set fixed height to ensure consistency */
  }

  .project-card:hover {
    transform: scale(1.05);
  }

  .project-card h3 {
    font-size: 18px;
    margin-bottom: 10px;
    font-weight: bold;
  }

  .project-card p {
    font-size: 14px;
    margin: 5px 0;
    color: #333;
  }

  .tech-stack {
    font-size: 12px;
    color: #777;
    margin-bottom: 10px;
  }

  .project-card a {
    color: #007acc;
    text-decoration: none;
    font-size: 18px;
    margin-top: 10px;
  }

  .project-card a:hover {
    text-decoration: underline;
  }

  .github-icon {
    font-size: 22px;
    color: #333;
  }
</style>

<div class="projects-container">
  <div class="project-card">
    <h3>Project A</h3>
    <p>This project focuses on developing a RESTful API for task management.</p>
    <p class="tech-stack"><strong>Technologies:</strong> Python, Flask</p>
    <a href="https://github.com/your-project" target="_blank">
      <i class="github-icon">GitHub</i>
    </a>
  </div>

  <div class="project-card">
    <h3>Project B</h3>
    <p>Built a collaborative task management app with real-time notifications.</p>
    <p class="tech-stack"><strong>Technologies:</strong> React, Node.js</p>
    <a href="https://your-project-link.com" target="_blank">
      <i class="github-icon">GitHub</i>
    </a>
  </div>

  <div class="project-card">
    <h3>Project C</h3>
    <p>Developed an Android app for wheelchair users to log breakdowns.</p>
    <p class="tech-stack"><strong>Technologies:</strong> Kotlin, Firebase</p>
    <a href="https://github.com/your-project" target="_blank">
      <i class="github-icon">GitHub</i>
    </a>
  </div>

  <!-- Add more project cards here -->
</div>
