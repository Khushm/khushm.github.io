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
    margin-bottom: 6px;
    margin-top: 6px;
    font-size: 14px;
  }

  .project-card p {
    font-size: 12px;  /* Smaller text for the summary */
    margin: 5px 0;
  }

  .project-card a {
    color: #181717;
    text-decoration: none;
    font-weight: bold;
    display: inline-block;
    justify-content: center;
    align-items: center;
    gap: 5px;
  }

  .project-card a:hover {
    color: #2F7F93;
  }

  .project-card i {
    font-size: 20px; /* Adjust size for the GitHub icon */
    transition: color 0.3s ease;
  }
  .project-card a:focus, .project-card a:hover {
  outline: none;  /* Remove the focus outline for a cleaner look */
}
</style>

<div class="projects-container">
  <div class="project-card">
    <h3>SRIP IITGN 2022: Advancing Bayesian ML with JAX</h3>
    <p>Developed neural network classifiers, Bayesian linear regression models, and sampling methods for multivariate normal distributions using JAX, Google's high-performance ML library. Enhanced probabilistic modeling for MNIST classification and Bayesian analysis from scratch, solidifying understanding of advanced ML techniques.</p>
    <p><small>JAX, Python, NumPy, SciPy, Matplotlib</small></p>
    <a href="https://github.com/Khushm/SRIP-IITGN-2022" target="_blank"><i class="fab fa-github"></i></a>
  </div>

  <div class="project-card">
    <h3>Socials Website</h3>
    <p>Designed and implemented the official dynamic website, streamlining committee updates and engagement. Enhanced accessibility and increased user interaction, driving a 30% growth in participation.</p>
    <p><small>HTML, CSS, JavaScript, PHP, Bootstrap</small></p>
    <a href="https://github.com/Khushm/SWD" target="_blank"><i class="fab fa-github"></i></a>
  </div>

  <div class="project-card">
    <h3>Exploratory Data Analysis</h3>
    <p>Analyzed a modified version of the Pima Indians Diabetes Database to predict diabetes risk, employing techniques like EDA, data cleaning, and logistic regression. Built and evaluated a predictive model to classify patients’ likelihood of diabetes, ensuring the model’s accuracy through various performance metrics.</p>
    <p><small>Python, Pandas, Matplotlib, Scikit-learn, Seaborn</small></p>
    <a href="https://github.com/Khushm/eda" target="_blank"><i class="fab fa-github"></i></a>
  </div>

  <!-- Add more project cards here -->
</div>
