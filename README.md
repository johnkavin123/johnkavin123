<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Programmer Profile</title>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Fira Code', monospace;
      background-color: #0d1117;
      color: #c9d1d9;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 900px;
      margin: auto;
      padding: 2rem;
    }
    .header {
      text-align: center;
    }
    .header img {
      width: 120px;
      border-radius: 50%;
      margin-bottom: 1rem;
    }
    h1 {
      margin: 0.5rem 0;
      color: #58a6ff;
    }
    h2 {
      border-bottom: 1px solid #30363d;
      padding-bottom: 0.3rem;
      margin-top: 2rem;
      color: #79c0ff;
    }
    .bio {
      font-size: 1rem;
      color: #8b949e;
    }
    .skills, .projects, .socials {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem 1rem;
    }
    .skill, .project, .social {
      background-color: #161b22;
      padding: 0.5rem 1rem;
      border-radius: 8px;
      font-size: 0.9rem;
      transition: background-color 0.2s;
      text-decoration: none;
      color: inherit;
    }
    .skill:hover, .project:hover, .social:hover {
      background-color: #21262d;
    }
    .stats img {
      margin: 0.5rem 0.5rem 0.5rem 0;
      border-radius: 8px;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <img src="https://github.com/yourusername.png" alt="Profile Picture">
      <h1>Your Name</h1>
      <p class="bio">Full-stack developer | Open-source enthusiast | Passionate about clean code and automation</p>
    </div>

    <h2>💻 Skills</h2>
    <div class="skills">
      <div class="skill">JavaScript</div>
      <div class="skill">Python</div>
      <div class="skill">React</div>
      <div class="skill">Node.js</div>
      <div class="skill">HTML & CSS</div>
      <div class="skill">Git & GitHub</div>
    </div>

    <h2>📊 GitHub Stats</h2>
    <div class="stats">
      <img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=dark" alt="GitHub Stats">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=dark" alt="GitHub Streak">
    </div>

    <h2>🛠 Projects</h2>
    <div class="projects">
      <a href="#" class="project">Project One</a>
      <a href="#" class="project">Project Two</a>
      <a href="#" class="project">Project Three</a>
    </div>

    <h2>📫 Connect with Me</h2>
    <div class="socials">
      <a href="https://linkedin.com/in/yourusername" class="social">LinkedIn</a>
      <a href="https://twitter.com/yourusername" class="social">Twitter</a>
      <a href="https://dev.to/yourusername" class="social">Dev.to</a>
      <a href="mailto:youremail@example.com" class="social">Email</a>
    </div>
  </div>
</body>
</html>
