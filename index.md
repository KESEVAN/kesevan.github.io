---
layout: default
---

# Hello, I'm Kesevan
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name - AI Specialist</title>
  <style>
    /* 
    *  Simple, Modern CSS Reset
    */
    *, *::before, *::after {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    /*
    *  Basic Styling 
    */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      background: #f4f4f4;
      color: #333;
    }

    .container {
      max-width: 800px;
      margin: auto;
      padding: 2rem;
    }

    h1, h2, h3 {
      color: #222;
    }

    h1 {
      font-size: 2.5rem;
    }

    h2 {
      font-size: 2rem;
      margin-top: 2rem;
    }

    a {
      color: #3498db; 
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    img {
      max-width: 100%;
      height: auto;
    }

    /* 
    *  Navigation
    */
    nav {
      background: #fff;
      padding: 1rem;
      border-bottom: 1px solid #ddd;
      display: flex;
      justify-content: space-between;
      align-items: center; 
    }

    nav ul {
      list-style: none;
    }

    nav li {
      display: inline-block;
      margin-left: 20px; 
    }

    /* 
    *  Sections (Hero, About, Projects, etc.)
    */
    section {
      padding: 3rem 0; 
    }

    .hero {
      background: #3498db; /* Example background color */
      color: #fff;
      text-align: center;
      padding: 6rem 0; 
    }

    .hero h1 {
      font-size: 3rem; 
    }

    .hero p {
      margin-bottom: 2rem; 
    }

    .project {
      background: #fff;
      padding: 2rem;
      margin-bottom: 2rem;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }
  </style>
</head>
<body>

<nav>
  <a href="#" class="logo">Your Name</a>
  <ul>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<section class="hero">
  <div class="container">
    <h1>Building Intelligent Systems</h1>
    <p>AI enthusiast passionate about autonomous systems, computer vision, and deep learning.</p>
    <a href="#projects" class="btn">View Projects</a> </div>
</section>

<section id="projects" class="projects">
  <div class="container">
    <h2>Featured Projects</h2>
    
    <div class="project">
      <h3>Project Title 1</h3>
      <p>Short description of Project 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      <a href="#">Learn More</a> </div>

    </div>
</section>

<section id="about" class="about">
  <div class="container">
    <h2>About Me</h2>
    <p>Write a brief and engaging about section here. Talk about your skills, interests, and career aspirations.</p>
  </div>
</section>

<section id="contact" class="contact">
  <div class="container">
    <h2>Get in Touch</h2>
    <p>Add your contact information here (email, links to LinkedIn, Github, etc.).</p>
  </div>
</section>

<footer>
  <div class="container">
    © 2023 Your Name </div>
</footer>

</body>
</html>
---
layout: default
title:  Your Name - AI Specialist
---

<style>
/* Basic Styling - Customize to match your brand */
.profile-img {
  width: 200px;
  height: 200px;
  border-radius: 50%; 
  object-fit: cover; 
  margin: 2rem auto;
  display: block;
}

.project-card {
  background: white;
  border-radius: 10px;
  padding: 2rem;
  margin-bottom: 2rem;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  transition: transform 0.2s ease; /* Add a hover effect */
}

.project-card:hover {
  transform: translateY(-5px); 
}
</style>

<div class="container"> 
  <div style="text-align: center;">
    <img src="your-profile-pic.jpg" alt="Your Name" class="profile-img">
    <h1>Hi, I'm [Your Name] 👋</h1>
    <p>AI Enthusiast | Passionate about [Your Key Interests] | Building the future with code.</p>
    <a href="https://github.com/your-github-username" target="_blank">GitHub</a> | 
    <a href="https://linkedin.com/in/your-linkedin-username" target="_blank">LinkedIn</a> 
  </div>

  ## 🚀 Featured Projects

  <div class="project-card">
    <h3>🧠 Project Title 1</h3>
    <p>Short, engaging description of Project 1. Highlight the problem, your solution, and key technologies used.</p>
    <a href="project1-link" target="_blank">Learn More</a>
  </div>

  <div class="project-card">
    <h3>🤖 Project Title 2</h3>
    <p>Short, engaging description of Project 2. Again, focus on what's interesting and relevant.</p>
    <a href="project2-link" target="_blank">Learn More</a>
  </div>

  <!-- Add more projects as needed -->

  ## ✨ Skills

  <p>
  **Languages:** Python, JavaScript, C++ <br>
  **Frameworks/Libraries:** TensorFlow, PyTorch, React, Node.js <br>
  **Tools:** Git, Docker, AWS, GCP <br>
  **Other:** Agile Development, Machine Learning, Deep Learning, Computer Vision
  </p>

  ## 🌱  Currently Learning

  <p>Always eager to expand my knowledge! Currently exploring [List your current learning areas]. </p>

  ## 📬 Get in Touch

  <p>Feel free to reach out! I'm always open to connecting and collaborating.</p>
</div> 

