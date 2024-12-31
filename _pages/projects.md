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
    <h3>Exploratory Data Analysis</h3>
    <p>Analyzed a modified version of the Pima Indians Diabetes Database to predict diabetes risk, employing techniques like EDA, data cleaning, and logistic regression. Built and evaluated a predictive model to classify patients’ likelihood of diabetes, ensuring the model’s accuracy through various performance metrics.</p>
    <p><small>Python, Pandas, Matplotlib, Scikit-learn, Seaborn</small></p>
    <a href="https://github.com/Khushm/eda" target="_blank"><i class="fab fa-github"></i></a>
  </div>

<div class="project-card">
    <h3>Vitarana Drone</h3>
    <p>Designed drone navigation algorithms using Python and ROS Melodic with the Bug2 algorithm for real-time obstacle avoidance. Presented technical progress and collaborated with cross-functional teams during the Eyantra Robotic Competition (eYRC) hosted by IIT Bombay.</p>
    <p><small>Python, ROS Melodic, Bug2 Algorithm, Robotics</small></p>
  </div>

<div class="project-card">
    <h3>A* Graph Search Implementation</h3>
    <p>Implemented the A* graph search algorithm, first using the default heuristic, followed by a more efficient "tighter" heuristic. Compared the two heuristics based on efficiency, number of paths explored, and frontier management.</p>
    <p><small>Python, A* Algorithm, Data Structures</small></p>
    <a href="" target="_blank"><i class="fab fa-github"></i></a>
  </div>
  
<div class="project-card">
    <h3>Heart Disease Prediction Classifier</h3>
    <p>Developed and optimized classifiers (KNN, Logistic Regression, Random Forest) to predict heart health status and recommend interventions. Achieved the highest NET_BENEFIT by fine-tuning models based on intervention costs and benefits.</p>
    <p><small>Python, scikit-learn, Pandas, Matplotlib</small></p>
    <a href="https://github.com/Khushm/classification" target="_blank"><i class="fab fa-github"></i></a>
  </div>

  <div class="project-card">
    <h3>2-Layer Feed-Forward Neural Network for Image Classification</h3>
    <p>Developed a 2-layer feed-forward neural network to classify cat vs non-cat images. Implemented key functions including linear activation forward, cost computation, backward propagation, and parameter updates to complete the neural network model.</p>
    <p><small>Python, NumPy, Neural Networks, Machine Learning</small></p>
    <a href="" target="_blank"><i class="fab fa-github"></i></a>
  </div>
  
  <div class="project-card">
    <h3>Autonomous Car for Indian Terrain</h3>
    <p>Led a project addressing Indian-specific road challenges, including pothole detection and obscured road signs, using Computer Vision and Neural Networks. Developed real-time solutions leveraging OpenCV and Deep Reinforcement Learning for autonomous navigation.</p>
    <p><small>OpenCV, Deep Reinforcement Learning, Neural Networks, Python</small></p>
  </div>

  <div class="project-card">
    <h3>Clustering Analysis on Multiple Datasets</h3>
    <p>Applied and evaluated clustering algorithms (K-Means, DBSCAN, Agglomerative Clustering) on three diverse datasets to assess performance and cluster accuracy. Fine-tuned algorithms for optimal results, achieving high cluster alignment with true labels.</p>
    <p><small>Python, scikit-learn, Pandas, Matplotlib</small></p>
    <a href="https://github.com/Khushm/clustering" target="_blank"><i class="fab fa-github"></i></a>
  </div>

  <div class="project-card">
    <h3>Concurrent Transactions in Database Systems</h3>
    <p>Implemented two paradigms for concurrency control in a simplified in-memory database: strict two-phase locking for serializability and pipelined execution for parallel transaction handling. Evaluated both techniques in a multi-threaded environment to optimize performance and maintain isolation.</p>
    <p><small>Java, Multi-threading, Database Transaction Management, Concurrency Control</small></p>
    <a href="" target="_blank"><i class="fab fa-github"></i></a>
  </div>
  
  <div class="project-card">
    <h3>SRIP IITGN 2022: Advancing Bayesian ML with JAX</h3>
    <p>Developed neural network classifiers, Bayesian linear regression models, and sampling methods for multivariate normal distributions using JAX, Google's high-performance ML library. Enhanced probabilistic modeling for MNIST classification and Bayesian analysis from scratch, solidifying understanding of advanced ML techniques.</p>
    <p><small>JAX, Python, NumPy, SciPy, Matplotlib</small></p>
    <a href="https://github.com/Khushm/SRIP-IITGN-2022" target="_blank"><i class="fab fa-github"></i></a>
  </div>

<div class="project-card">
    <h3>Market Basket Analysis for Association Rule Mining</h3>
    <p>Performed association rule mining on a market basket dataset with 50 transactions to uncover item relationships and customer purchase patterns. Used the Apriori algorithm and visualized the results with relevant metrics like support, confidence, and lift.</p>
    <p><small>Python, Pandas, mlxtend, Matplotlib</small></p>
    <a href="https://github.com/Khushm/associationrules" target="_blank"><i class="fab fa-github"></i></a>
  </div>

  <div class="project-card">
    <h3>Character Recognition System</h3>
    <p>Developed a character recognition system where users draw characters, which are then processed into images for recognition. Utilized the EMNIST dataset for training a k-NN classifier, enabling the system to predict labels of newly drawn characters with high accuracy.</p>
    <p><small>Python, EMNIST Dataset, k-NN Classifier, Image Processing, Machine Learning</small></p>
    <a href="https://github.com/Khushm/Code_Twisto" target="_blank"><i class="fab fa-github"></i></a>
  </div>

  
  <div class="project-card">
    <h3>Socials Website</h3>
    <p>Designed and implemented the official dynamic website, streamlining committee updates and engagement. Enhanced accessibility and increased user interaction, driving a 30% growth in participation.</p>
    <p><small>HTML, CSS, JavaScript, PHP, Bootstrap</small></p>
    <a href="https://github.com/Khushm/SWD" target="_blank"><i class="fab fa-github"></i></a>
  </div>

  <div class="project-card">
    <h3>Taste As Home - E-Commerce Platform for Nutritious Food Delivery</h3>
    <p>Developed an easy-to-use platform that connects food providers with quarantined individuals and customers seeking nutritious meals. The website allows providers to offer services like breakfast, lunch, and dinner at affordable prices and ensures quick delivery. The system empowers women and individuals who lost jobs during the pandemic to become financially independent while promoting health and convenience.</p>
    <p><small>PHP, HTML, CSS, JavaScript, MySQL, AJAX, Bootstrap</small></p>
    <a href="https://github.com/Khushm/TasteAsHome" target="_blank"><i class="fab fa-github"></i></a>
  </div>

  <div class="project-card">
    <h3>At Your Service - Volunteer Platform for Essential Delivery Services</h3>
    <p>Developed a platform connecting volunteers with quarantined individuals to provide nutritious food, sanitizers, and medical information, ensuring quick, affordable deliveries. Empowered women volunteers to earn independently, while improving service efficiency and cost-effectiveness.</p>
    <p><small>PHP, HTML, CSS, JavaScript, MySQL, Bootstrap</small></p>
    <a href="https://github.com/Khushm/TasteAsHome" target="_blank"><i class="fab fa-github"></i></a>
  </div>

  <!-- Add more project cards here -->
</div>
