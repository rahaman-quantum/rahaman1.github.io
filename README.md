<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Personal Website</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #0d1117;
      color: #fff;
      padding: 2rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background: #161b22;
      padding: 1rem;
    }
    nav a {
      color: #c9d1d9;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #58a6ff;
    }
    .container {
      max-width: 900px;
      margin: 2rem auto;
      padding: 1rem;
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #0d1117;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <h1>Your Name</h1>
    <p>Researcher | Quantum Computing | AI</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#research">Research</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container" id="about">
    <h2>About Me</h2>
    <p>Write a short introduction about yourself here.</p>
  </div>

  <div class="container" id="research">
    <h2>Research</h2>
    <p>Describe your research interests and publications.</p>
  </div>

  <div class="container" id="projects">
    <h2>Selected Projects</h2>
    <ul>
      <li>Project 1 — description...</li>
      <li>Project 2 — description...</li>
      <li>Project 3 — description...</li>
    </ul>
  </div>

  <div class="container" id="contact">
    <h2>Contact</h2>
    <p>Email: your.email@example.com</p>
    <p>GitHub: github.com/your-username</p>
  </div>

  <footer>
    <p>© 2025 Your Name — Built with GitHub Pages</p>
  </footer>
</body>
</html>

