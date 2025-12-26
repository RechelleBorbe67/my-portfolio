<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rechelle Borbe | Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- NAVBAR -->
  <nav>
    <h2 class="logo">RB</h2>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="pages/contact.html">Contact</a></li>
    </ul>
  </nav>

  <!-- HERO -->
  <section class="hero">
    <img src="assets/images/profile.jpg" alt="Profile Photo" class="profile-img">
    <h1>Hi, I'm Rechelle 👋</h1>
    <p>Web Systems Developer | IT Student</p>
  </section>

  <!-- ABOUT -->
  <section id="about" class="section">
    <h2>About Me</h2>
    <p>
      I am an IT student specializing in web systems development.
      I build inventory, e-commerce, and reservation systems with
      a focus on functionality, data accuracy, and user experience.
    </p>
  </section>

  <!-- PROJECTS -->
  <section id="projects" class="section">
    <h2>Projects</h2>

    <div class="projects-grid">

      <div class="project-card">
        <img src="assets/images/project1.png" alt="Inventory System">
        <h3>Inventory Management System</h3>
        <p>Data-driven system for inventory tracking and BI analysis.</p>
        <a href="pages/projects.html">View Details →</a>
      </div>

      <div class="project-card">
        <img src="assets/images/project2.png" alt="E-commerce System">
        <h3>Simple E-commerce System</h3>
        <p>Online beauty product store with admin management.</p>
        <a href="pages/projects.html">View Details →</a>
      </div>

      <div class="project-card">
        <img src="assets/images/project3.png" alt="Salon System">
        <h3>Salon Reservation System</h3>
        <p>Real-time booking system with analytics dashboard.</p>
        <a href="pages/projects.html">View Details →</a>
      </div>

    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>© 2025 Rechelle Borbe</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
