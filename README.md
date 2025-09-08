# Musfiras-portfolio.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Musfira | Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #1e1e2e;
      color: #f3f4f6;
      line-height: 1.6;
      overflow-x: hidden;
    }

    header {
      background: #2a2a3b;
      padding: 20px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 2px 6px rgba(0,0,0,0.4);
    }

    header h1 {
      font-size: 2rem;
      color: #4fd1c5;
      letter-spacing: 2px;
    }

    nav ul {
      list-style: none;
      margin-top: 10px;
    }

    nav ul li {
      display: inline-block;
      margin: 0 12px;
    }

    nav ul li a {
      text-decoration: none;
      color: #f3f4f6;
      font-weight: 500;
      transition: 0.3s;
    }

    nav ul li a:hover {
      color: #a78bfa;
    }

    /* Hero Section */
    .hero {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      background: linear-gradient(135deg, #1e1e2e, #2a2a3b);
      padding: 20px;
    }

    .hero h2 {
      font-size: 2.5rem;
      color: #4fd1c5;
      margin-bottom: 10px;
    }

    .typing {
      font-size: 1.2rem;
      color: #a78bfa;
      height: 30px;
    }

    .btn {
      margin-top: 20px;
      padding: 12px 25px;
      border: none;
      background: #fbbf24;
      color: #1e1e2e;
      font-weight: bold;
      border-radius: 25px;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: #facc15;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2.section-title {
      text-align: center;
      margin-bottom: 40px;
      font-size: 1.8rem;
      color: #a78bfa;
    }

    /* About */
    .about p {
      text-align: center;
      font-size: 1.05rem;
      max-width: 700px;
      margin: auto;
    }

    /* Skills */
    .skills .skill {
      margin-bottom: 20px;
    }

    .skill-bar {
      background: #2a2a3b;
      border-radius: 20px;
      overflow: hidden;
    }

    .skill-bar-fill {
      display: block;
      height: 14px;
      background: #4fd1c5;
      width: 0;
      transition: width 2s ease-in-out;
    }

    /* Projects */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .project {
      background: #2a2a3b;
      padding: 20px;
      border-radius: 12px;
      transition: 0.3s;
    }

    .project:hover {
      transform: translateY(-5px);
      background: #35354a;
    }

    .project img {
      width: 100%;
      border-radius: 8px;
      margin-bottom: 12px;
    }

    /* Contact */
    .contact form {
      display: grid;
      gap: 15px;
      max-width: 500px;
      margin: auto;
    }

    .contact input, .contact textarea {
      padding: 12px;
      border: none;
      border-radius: 6px;
      outline: none;
      background: #2a2a3b;
      color: #f3f4f6;
    }

    .contact button {
      background: #4fd1c5;
      color: #1e1e2e;
      padding: 12px;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      font-weight: bold;
      transition: 0.3s;
    }

    .contact button:hover {
      background: #38b2ac;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #2a2a3b;
      margin-top: 40px;
      color: #aaa;
    }
  </style>
</head>
<body>

  <header>
    <h1>Musfira</h1>
    <nav>
      <ul>
        <li><a href="#hero">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero" id="hero">
    <h2>Hello, I'm Musfira</h2>
    <p class="typing"></p>
    <button class="btn">Download CV</button>
  </section>

  <!-- About -->
  <section class="about" id="about">
    <h2 class="section-title">About Me</h2>
    <p>
      I am Musfira, a passionate hacker and web developer.  
      I love exploring cyber security, creating modern web designs, and coding powerful projects.  
      My aim is to merge creativity with technology to build impactful solutions.
    </p>
  </section>

  <!-- Skills -->
  <section class="skills" id="skills">
    <h2 class="section-title">Skills</h2>
    <div class="skill">
      <p>HTML</p>
      <div class="skill-bar"><span class="skill-bar-fill" data-width="95%"></span></div>
    </div>
    <div class="skill">
      <p>CSS</p>
      <div class="skill-bar"><span class="skill-bar-fill" data-width="90%"></span></div>
    </div>
    <div class="skill">
      <p>JavaScript</p>
      <div class="skill-bar"><span class="skill-bar-fill" data-width="80%"></span></div>
    </div>
    <div class="skill">
      <p>Ethical Hacking</p>
      <div class="skill-bar"><span class="skill-bar-fill" data-width="70%"></span></div>
    </div>
  </section>

  <!-- Projects -->
  <section class="projects" id="projects">
    <h2 class="section-title">Projects</h2>
    <div class="project">
      <img src="https://picsum.photos/id/1043/400/250" alt="Project 1">
      <h3>Portfolio Website</h3>
      <p>A personal portfolio with subtle pastel theme.</p>
    </div>
    <div class="project">
      <img src="https://picsum.photos/id/1050/400/250" alt="Project 2">
      <h3>Cyber Security Tool</h3>
      <p>A tool for basic penetration testing and analysis.</p>
    </div>
    <div class="project">
      <img src="https://picsum.photos/id/1062/400/250" alt="Project 3">
      <h3>Web Development Project</h3>
      <p>A modern, responsive web application with clean UI.</p>
    </div>
  </section>

  <!-- Contact -->
  <section class="contact" id="contact">
    <h2 class="section-title">Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Musfira. All Rights Reserved.</p>
  </footer>

  <!-- JS for typing effect & skills animation -->
  <script>
    // Typing effect
    const texts = ["Hacker", "Web Developer", "Coder"];
    let count = 0;
    let index = 0;
    let currentText = "";
    let letter = "";
    function type() {
      if (count === texts.length) {
        count = 0;
      }
      currentText = texts[count];
      letter = currentText.slice(0, ++index);
      document.querySelector(".typing").textContent = letter;
      if (letter.length === currentText.length) {
        count++;
        index = 0;
        setTimeout(type, 1000);
      } else {
        setTimeout(type, 150);
      }
    }
    type();

    // Animate skill bars
    const skills = document.querySelectorAll('.skill-bar-fill');
    window.addEventListener('scroll', () => {
      skills.forEach(skill => {
        const rect = skill.getBoundingClientRect();
        if (rect.top < window.innerHeight && skill.style.width === "") {
          skill.style.width = skill.dataset.width;
        }
      });
    });
  </script>
</body>
</html>
