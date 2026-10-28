HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Personal Introduction Page</title>
</head>
<body>

  <!-- Header Section -->
  <div id="header-section" class="container header-container" data-category="navigation">
    <h1 id="main-title" class="title">Welcome to My Portfolio</h1>
    <p id="tagline" class="subtitle">Full-Stack Web Developer & Learning Enthusiast</p>
  </div>

  <!-- About Section -->
  <div id="about-section" class="container content-card" data-section-type="bio">
    <h2 id="about-title" class="section-heading">About Me</h2>
    <p id="about-text" class="description-text">
      Hello! I am a passionate computer science student dedicated to building clean, accessible, and user-friendly web applications.
    </p>
  </div>

  <!-- Education Section -->
  <div id="education-section" class="container content-card" data-section-type="academic">
    <h2 id="education-title" class="section-heading">Education</h2>
    <div id="degree-info" class="sub-card">
      <h3 class="card-title">Bachelor of Science in Computer Science</h3>
      <p class="institution-name">State University — Graduating 2026</p>
    </div>
  </div>

  <!-- Skills Section -->
  <div id="skills-section" class="container content-card" data-section-type="technical">
    <h2 id="skills-title" class="section-heading">Skills</h2>
    <ul id="skills-list" class="badge-list">
      <li class="list-item">HTML5 & CSS3</li>
      <li class="list-item">JavaScript (ES6+)</li>
      <li class="list-item">Git & GitHub</li>
      <li class="list-item">Responsive Web Design</li>
    </ul>
  </div>

  <!-- Contact Section -->
  <div id="contact-section" class="container footer-container" data-category="communication">
    <h2 id="contact-title" class="section-heading">Contact Me</h2>
    <p id="contact-email" class="contact-info">
      Email: <a href="mailto:student@example.com" class="link">student@example.com</a>
    </p>
    <p id="contact-location" class="contact-info">Location: New York, USA</p>
  </div>

</body>
</html>