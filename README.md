<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Magthum | Engineering Student</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #0b0f19;
      color: white;
      line-height: 1.6;
    }

    nav {
      position: fixed;
      top: 0;
      width: 100%;
      padding: 20px 8%;
      background: #0b0f19ee;
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 1000;
    }

    .logo {
      font-size: 25px;
      font-weight: bold;
    }

    .logo span {
      color: #00d9ff;
    }

    nav ul {
      display: flex;
      list-style: none;
      gap: 25px;
    }

    nav a {
      color: white;
      text-decoration: none;
    }

    nav a:hover {
      color: #00d9ff;
    }

    section {
      padding: 100px 8%;
      min-height: 100vh;
    }

    #home {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: flex-start;
    }

    .hello {
      color: #00d9ff;
      font-size: 20px;
    }

    h1 {
      font-size: clamp(45px, 8vw, 80px);
      margin: 10px 0;
    }

    h1 span {
      color: #00d9ff;
    }

    .hero-text {
      max-width: 650px;
      font-size: 20px;
      color: #b8c0cc;
    }

    .btn {
      display: inline-block;
      margin-top: 30px;
      padding: 13px 25px;
      background: #00d9ff;
      color: #061018;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
    }

    .title {
      font-size: 40px;
      margin-bottom: 30px;
    }

    .title span {
      color: #00d9ff;
    }

    .about {
      max-width: 750px;
      color: #c5ccd6;
      font-size: 18px;
    }

    .skills,
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .card {
      background: #151b29;
      padding: 25px;
      border-radius: 15px;
      border: 1px solid #252e40;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-8px);
      border-color: #00d9ff;
    }

    .card h3 {
      color: #00d9ff;
      margin-bottom: 10px;
    }

    .card p {
      color: #b8c0cc;
    }

    .contact {
      text-align: center;
    }

    .contact p {
      color: #b8c0cc;
      font-size: 18px;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #070a11;
      color: #888;
    }

    @media (max-width: 650px) {
      nav ul {
        gap: 10px;
        font-size: 13px;
      }

      section {
        padding: 90px 6%;
      }
    }
  </style>
</head>

<body>

  <!-- Navigation -->
  <nav>
    <div class="logo">MAG<span>THUM</span></div>

    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>


  <!-- Home -->
  <section id="home">

    <p class="hello">Hello, I'm</p>

    <h1>Magthum<span>.</span></h1>

    <p class="hero-text">
      I'm a First-Year Engineering Student passionate about
      technology, programming and building creative projects.
    </p>

    <a href="#projects" class="btn">
      View My Projects
    </a>

  </section>


  <!-- About -->
  <section id="about">

    <h2 class="title">About <span>Me</span></h2>

    <p class="about">
      I'm Magthum, a first-year engineering student who is
      interested in technology and innovation. I'm currently
      developing my technical skills, learning programming,
      and exploring new ideas through personal projects.
      
      My goal is to continuously learn, improve my skills,
      and create useful technology-based solutions.
    </p>

  </section>


  <!-- Skills -->
  <section id="skills">

    <h2 class="title">My <span>Skills</span></h2>

    <div class="skills">

      <div class="card">
        <h3>HTML & CSS</h3>
        <p>Creating responsive and attractive websites.</p>
      </div>

      <div class="card">
        <h3>JavaScript</h3>
        <p>Learning interactive web development.</p>
      </div>

      <div class="card">
        <h3>Python</h3>
        <p>Learning programming and problem solving.</p>
      </div>

      <div class="card">
        <h3>Problem Solving</h3>
        <p>Developing logical thinking and technical skills.</p>
      </div>

    </div>

  </section>


  <!-- Projects -->
  <section id="projects">

    <h2 class="title">My <span>Projects</span></h2>

    <div class="projects">

      <div class="card">
        <h3>Portfolio Website</h3>
        <p>
          A personal portfolio website created using
          HTML and CSS.
        </p>
      </div>

      <div class="card">
        <h3>Student Project</h3>
        <p>
          My upcoming engineering project will be
          displayed here.
        </p>
      </div>

      <div class="card">
        <h3>Future Project</h3>
        <p>
          More interesting technology projects coming soon.
        </p>
      </div>

    </div>

  </section>


  <!-- Contact -->
  <section id="contact" class="contact">

    <h2 class="title">Contact <span>Me</span></h2>

    <p>
      Let's connect and build something amazing!
    </p>

    <a class="btn" href="mailto:yourmail@example.com">
      Email Me
    </a>

  </section>


  <footer>
    © 2026 Magthum. All Rights Reserved.
  </footer>

</body>
</html>
