<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bancy Wacuka | Front-End Developer</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      line-height: 1.6;
      background-color: #f9fafb;
      color: #1f2937;
    }

    header {
      background-color: #111827;
      color: white;
      padding: 1.5rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 1.5rem;
    }

    nav a {
      color: white;
      margin-left: 1rem;
      text-decoration: none;
      font-weight: 500;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      padding: 4rem 2rem;
      text-align: center;
      background: #e5e7eb;
    }

    .hero h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }

    .project, .skill-box {
      background-color: white;
      padding: 1rem;
      border-radius: 8px;
      margin-bottom: 1rem;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }

    .project h3 {
      margin-bottom: 0.5rem;
    }

    ul.skills-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 0.5rem;
      list-style: none;
      margin-top: 1rem;
    }

    .skills-list li {
      background: #f3f4f6;
      padding: 0.5rem;
      text-align: center;
      border-radius: 4px;
    }

    footer {
      background-color: #111827;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    a {
      color: #2563eb;
    }

    @media (max-width: 600px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }
      nav {
        margin-top: 1rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Bancy Wacuka</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Front-End Web Developer</h2>
    <p>I craft beautiful, responsive, and user-friendly websites. Let’s build something amazing!</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi! I'm Bancy Wacuka, a passionate front-end web developer with a love for clean code and beautiful design. I enjoy turning ideas into interactive web experiences, and I'm currently expanding my skills with ALX’s Software Engineering program.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>VirtualMatch KE</h3>
      <p>A platform that connects Kenyan Virtual Assistants with international clients. <br><strong>Tech used:</strong> HTML, CSS, JavaScript</p>
    </div>
    <!-- Add more projects here -->
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul class="skills-list">
      <li>HTML5</li>
      <li>CSS3</li>
      <li>JavaScript</li>
      <li>Responsive Design</li>
      <li>Git & GitHub</li>
      <li>Bootstrap</li>
      <li>React</li>
      <li>APIs</li>
      <li>Version Control</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:bancywacuka@gmail.com">bancywacuka@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/bancy-wacuka-wanjohi/" target="_blank">bancy-wacuka-wanjohi</a></p>
  </section>

  <footer>
    <p>© 2025 Bancy Wacuka | Front-End Developer</p>
  </footer>

</body>
</html>
