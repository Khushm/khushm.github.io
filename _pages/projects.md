---
layout: archive
permalink: projects/
title: "My Notable Projects"
author_profile: true
---

<head>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
</head>

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
    padding: 10px;  /* Reduced padding for smaller cards */
    width: 250px;  /* Reduced width for smaller cards */
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    text-align: center;
    transition: transform 0.3s ease;
  }

  .project-card:hover {
    transform: scale(1.05);
  }

  .project-card h3 {
    margin-bottom: 10px;
    font-size: 18px;
  }

  .project-card p {
    font-size: 12px;  /* Smaller text for the summary */
    margin: 5px 0;
  }

  .project-card a {
    color: #007acc;
    text-decoration: none;
    font-weight: bold;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 5px;
  }

  .project-card a:hover {
    text-decoration: underline;
  }

  .project-card i {
    font-size: 18px; /* Adjust size for the GitHub icon */
  }
</style>

<div class="projects-container">
  <div class="project-card">
    <h3>Project A</h3>
    <p><strong>Summary:</strong> Developed a RESTful API for managing tasks and scheduling automation.</p>
    <p><small><strong>Tech Stack:</strong> Python, Flask</small></p>
    <a href="https://github.com/your-project" target="_blank">
      <i class="fab fa-github"></i> View on GitHub
    </a>
  </div>

  <div class="project-card">
    <h3>Project B</h3>
    <p><strong>Summary:</strong> Built a collaborative task management app with real-time notifications.</p>
    <p><small><strong>Tech Stack:</strong> React, Node.js</small></p>
    <a href="https://github.com/your-project" target="_blank">
      <i class="fab fa-github"></i> View on GitHub
    </a>
  </div>

  <div class="project-card">
    <h3>Project C</h3>
    <p><strong>Summary:</strong> Android app for wheelchair users to log and track breakdown issues and repair history.</p>
    <p><small><strong>Tech Stack:</strong> Kotlin, Firebase</small></p>
    <a href="https://github.com/your-project" target="_blank">
      <i class="fab fa-github"></i> View on GitHub
    </a>
  </div>

  <!-- Add more project cards here -->
</div>
