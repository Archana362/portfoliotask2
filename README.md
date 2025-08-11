<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>G. Archana Portfolio</title>
  <style>
    :root {
      --bg-light: #ffffff;
      --text-light: #000000;
      --bg-dark: #121212;
      --text-dark: #ffffff;
      --accent: #4CAF50;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--bg-light);
      color: var(--text-light);
      transition: all 0.3s ease;
    }

    body.dark-mode {
      background-color: var(--bg-dark);
      color: var(--text-dark);
    }

    header {
      background-color: var(--accent);
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      color: white;
    }

    .container {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }

    h1, h2 {
      border-bottom: 2px solid var(--accent);
      padding-bottom: 5px;
    }

    ul {
      list-style: square;
      margin-left: 20px;
    }

    .toggle-btn {
      background: none;
      border: 2px solid white;
      color: white;
      padding: 5px 10px;
      border-radius: 5px;
      cursor: pointer;
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .section {
      margin-bottom: 30px;
    }
  </style>
</head>
<body>
  <header>
    <div>
      <h2>G. Archana</h2>
    </div>
    <button class="toggle-btn" onclick="toggleTheme()">Toggle Theme</button>
  </header>

  <div class="container">
    <div class="section">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:archanagandhi2004@gmail.com">archanagandhi2004@gmail.com</a></p>
      <p>Mobile: +91 63748 75655</p>
      <p>LinkedIn: <a href="http://www.linkedin.com/in/archana-gandhi-3892302a4" target="_blank">View Profile</a></p>
    </div>

    <div class="section">
      <h2>Objective</h2>
      <p>
        Driven and passionate college student seeking to leverage academic background and problem-solving skills in a challenging internship or entry-level position. 
        Enthusiastic about collaborating in team settings and gaining practical experience to enhance career growth. 
        Dedicated to contributing positively and learning from diverse professional environments.
      </p>
    </div>

    <div class="section">
      <h2>Education</h2>
      <ul>
        <li><strong>B.Tech in Computer Science and Business Systems</strong> – Kingston Engineering College (2022-2026) – CGPA: 8.58</li>
        <li><strong>Higher Secondary</strong> – Government Girls Higher Secondary School (2021-2022) – 74.1%</li>
        <li><strong>Secondary School</strong> – Seventh-Day Adventist Matric HR Sec School (2019-2020) – 89%</li>
      </ul>
    </div>

    <div class="section">
      <h2>Skills</h2>
      <ul>
        <li>Leadership</li>
        <li>Problem Solving</li>
      </ul>
    </div>

    <div class="section">
      <h2>Technical Skills</h2>
      <ul>
        <li>Python</li>
        <li>Java</li>
      </ul>
    </div>

    <div class="section">
      <h2>Projects</h2>
      <ul>
        <li>IoT Based Smart Traffic Diversion System for Road Congestion Management</li>
      </ul>
    </div>

    <div class="section">
      <h2>Internships</h2>
      <ul>
        <li>Full Stack Web Development</li>
      </ul>
    </div>

    <div class="section">
      <h2>Certificates</h2>
      <ul>
        <li>Full Stack Web Development</li>
        <li>Infosys Springboard – JavaScript</li>
        <li>Data Analytics</li>
      </ul>
    </div>

    <div class="section">
      <h2>Languages</h2>
      <ul>
        <li>Tamil</li>
        <li>English</li>
      </ul>
    </div>
  </div>

  <script>
    function toggleTheme() {
      document.body.classList.toggle('dark-mode');
    }
  </script>
</body>
</html>
