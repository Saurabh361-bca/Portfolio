<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Saurabh Kumar Mehra – Frontend Developer</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #fff;
      color: #000;
    }

    header {
      padding: 20px 50px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #000;
      color: white;
      position: sticky;
      top: 0;
    }

    nav a {
      margin-left: 15px;
      color: white;
      text-decoration: none;
    }

    nav a:hover {
      color: #7c3aed;
    }

    .search-box input {
      padding: 6px 12px;
      border-radius: 20px;
      border: none;
    }

    .nav-right {
      display: flex;
      gap: 20px;
      align-items: center;
    }

    .hero {
      display: flex;
      padding: 60px 50px;
      align-items: center;
      gap: 40px;
    }

    .hero-left h2 {
      font-size: 40px;
    }

    .hero-left p {
      margin-top: 10px;
      color: #444;
    }

    .hero-left a {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 20px;
      background: #7c3aed;
      color: white;
      border-radius: 6px;
      text-decoration: none;
    }

    .hero-right img {
      max-width: 300px;
      border-radius: 10px;
    }

    section {
      padding: 50px;
    }

    h2 {
      margin-bottom: 20px;
      border-left: 5px solid #7c3aed;
      padding-left: 10px;
    }

    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
    }

    .skill-box {
      background: #f3f3f3;
      padding: 15px;
      text-align: center;
      border-radius: 8px;
    }

    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }

    .project-box {
      border: 1px solid #ccc;
      border-radius: 10px;
      overflow: hidden;
    }

    .project-box img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }

    .project-box p {
      padding: 10px;
      font-weight: bold;
    }

    form input, form textarea {
      width: 100%;
      margin-top: 10px;
      padding: 10px;
      border: 1px solid #000;
      border-radius: 5px;
    }

    form button {
      margin-top: 10px;
      padding: 10px;
      background: #000;
      color: white;
      border: none;
      cursor: pointer;
    }

    .whatsapp-btn {
      position: fixed;
      bottom: 20px;
      left: 20px;
      background: #25D366;
      color: white;
      padding: 10px 15px;
      border-radius: 50px;
      text-decoration: none;
    }

    .contact-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #7c3aed;
      color: white;
      padding: 12px;
      border-radius: 50%;
      text-decoration: none;
    }

    @media(max-width:768px){
      .hero {
        flex-direction: column;
        text-align: center;
      }
    }
  </style>
</head>

<body>

<header>
  <h1>Saurabh</h1>

  <div class="nav-right">
    <div class="search-box">
      <input type="text" placeholder="Search...">
    </div>

    <nav>
      <a href="#hero">Home</a>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
      <a href="https://www.linkedin.com/in/mr-saurabh" target="_blank">LinkedIn</a>
    </nav>
  </div>
</header>

<!-- HERO -->
<section class="hero" id="hero">
  <div class="hero-left">
    <h2>Hello, I'm Saurabh Kumar Mehra</h2>
    <p>
      Frontend Developer & MCA Student passionate about building modern, responsive web applications and UI/UX experiences.
    </p>

    <a href="https://github.com/Saurabh361-bca" target="_blank">View GitHub</a>
  </div>

  <div class="hero-right">
    <img src="./IMG_20230704_062034.jpg" alt="Profile">
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <h2>About Me</h2>
  <p>
    I am an MCA student and Frontend Developer with experience in building real-time applications and modern interfaces.
  </p>
</section>

<!-- SKILLS -->
<section id="skills">
  <h2>Skills</h2>
  <div class="skills-grid">
    <div class="skill-box">HTML</div>
    <div class="skill-box">CSS</div>
    <div class="skill-box">JavaScript</div>
    <div class="skill-box">React</div>
    <div class="skill-box">Tailwind</div>
    <div class="skill-box">GitHub</div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects">
  <h2>Projects</h2>
  <div class="projects-grid">

    <a href="https://github.com/Saurabh361-bca" target="_blank" class="project-box">
      <img src="https://images.unsplash.com/photo-1551033406-611cf9a28f67">
      <p>Realtime Chat App</p>
    </a>

    <a href="https://github.com/Saurabh361-bca" target="_blank" class="project-box">
      <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085">
      <p>SEO Blog Platform</p>
    </a>

    <a href="https://github.com/Saurabh361-bca" target="_blank" class="project-box">
      <img src="https://images.unsplash.com/photo-1505685296765-3a2736de412f">
      <p>Portfolio Website</p>
    </a>

  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <h2>Contact Me</h2>

  <form>
    <input type="text" placeholder="Your Name">
    <input type="email" placeholder="Your Email">
    <textarea placeholder="Message"></textarea>
    <button>Send</button>
  </form>

  <div style="margin-top:20px;">
    <p>Email: <a href="mailto:skmehracse@gmail.com">skmehracse@gmail.com</a></p>
    <p>Phone: <a href="tel:6395318722">+91 6395318722</a></p>
    <p>Location: Panipat, Haryana</p>
    <p>GitHub: <a href="https://github.com/Saurabh361-bca" target="_blank">github.com/Saurabh361-bca</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/mr-saurabh" target="_blank">linkedin.com/in/mr-saurabh</a></p>
  </div>
</section>

<a class="whatsapp-btn" href="https://wa.me/916395318722" target="_blank">Chat</a>
<a href="#contact" class="contact-float">☎</a>

</body>
</html>
