<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Albin Abey</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      color: #333;
    }

    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #333;
      padding: 15px 20px;
      color: white;
    }

    .logo {
      font-size: 1.5em;
      font-weight: bold;
    }

    .nav-links {
      list-style: none;
      display: flex;
      gap: 15px;
      margin: 0;
      padding: 0;
    }

    .nav-links a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      text-align: center;
    }

    h1, h2, h3 {
      color: #222;
    }

    .project {
      margin: 20px 0;
    }

    .footer {
      background-color: black;
      color: white;
      padding: 30px 20px;
      text-align: center;
    }

    .footer-content {
      display: flex;
      flex-direction: column;
      gap: 20px;
      margin-bottom: 20px;
    }

    .footer-section h3, .footer-section h4 {
      margin-bottom: 5px;
    }

    .footer-bottom {
      font-size: 0.9em;
      color: #aaa;
      border-top: 1px solid #444;
      padding-top: 10px;
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <header class="navbar">
    <div class="logo">Albin Abey</div>
    <nav>
      <ul class="nav-links">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Work</a></li>
        <li><a href="#">Portfolio</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Intro Section -->
  <section>
    <h1>Hi, I am Albin</h1>
    <p>I am a first-year B.Tech Computer Science student at Amal Jyothi College of Engineering.</p>
    <p>I enjoy creating websites and exploring the world of software development and technology.</p>
  </section>

  <!-- About Section -->
  <section>
    <h2>About</h2>
    <p>Passionate about coding, I love experimenting with HTML, CSS, and JavaScript. I’m also learning Python and exploring AI and data science.</p>
    <p>In my free time, I enjoy gaming, learning new tech tools, and reading about innovations in software engineering.</p>
  </section>

  <!-- Work Section -->
  <section>
    <h2>Work</h2>
    <div class="project">
      <h3>Simple Portfolio</h3>
      <p>This was one of my first projects — a clean and responsive HTML page to introduce myself online.</p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="footer-content">
      <div class="footer-section">
        <h3>Albin Abey</h3>
        <p>Aspiring software developer from Kerala, India.</p>
      </div>
      <div class="footer-section">
        <h4>About</h4>
        <p>Student at Amal Jyothi College of Engineering, learning full-stack web development.</p>
      </div>
      <div class="footer-section">
        <h4>Self Profile</h4>
        <p>Web Developer | Tech Explorer | Gamer | Innovator</p>
      </div>
    </div>
    <p class="footer-bottom">© 2025 Albin Abey</p>
  </footer>

</body>
</html>
