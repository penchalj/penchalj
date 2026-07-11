<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Penchalaiah Jammula | Senior DevOps Engineer</title>
  <style>
    :root {
      --primary: #0A2540;
      --accent: #00D4FF;
    }
    body {
      font-family: 'Segoe UI', system-ui, sans-serif;
      margin: 0; padding: 0;
      background: linear-gradient(135deg, #0A2540 0%, #1a3a5f 100%);
      color: white;
      line-height: 1.6;
    }
    .container { max-width: 1100px; margin: 0 auto; padding: 20px; }
    header {
      text-align: center;
      padding: 60px 20px 40px;
      background: rgba(0,0,0,0.4);
      border-radius: 0 0 30px 30px;
    }
    .profile-img {
      width: 180px; height: 180px; border-radius: 50%;
      border: 6px solid var(--accent);
      margin-bottom: 20px;
    }
    h1 { font-size: 3rem; margin: 10px 0; }
    .tagline { font-size: 1.4rem; opacity: 0.9; }
    section { padding: 60px 0; }
    .card {
      background: rgba(255,255,255,0.1);
      border-radius: 16px;
      padding: 24px;
      margin: 16px 0;
      transition: transform 0.3s;
    }
    .card:hover { transform: translateY(-8px); }
    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    footer {
      text-align: center;
      padding: 40px;
      background: rgba(0,0,0,0.6);
    }
    a { color: var(--accent); text-decoration: none; }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <img src="https://via.placeholder.com/180" alt="Profile" class="profile-img">
      <h1>Penchalaiah Jammula</h1>
      <p class="tagline">Senior DevOps Engineer | CI/CD Architect | Embedded Systems Expert</p>
      <p>Tuttlingen, Germany • Immediate Availability</p>
    </header>

    <section>
      <h2>💼 Featured Projects</h2>
      <div class="skills-grid">
        <div class="card">
          <h3>BMS CI/CD Platform @ Marquardt</h3>
          <p>Designed full containerized CI/CD pipelines with Docker, Terraform, and Ansible. Automated build, test, and flashing processes.</p>
        </div>
        <div class="card">
          <h3>ADAS Test Automation</h3>
          <p>Built Python/CAPL frameworks integrated into Jenkins for HIL testing of camera and radar systems.</p>
        </div>
      </div>
    </section>

    <section>
      <h2>🛠️ Skills</h2>
      <div class="skills-grid">
        <div class="card"><strong>DevOps:</strong> Azure DevOps, Jenkins, GitLab, Docker, Kubernetes, Terraform</div>
        <div class="card"><strong>Automation:</strong> Python, PowerShell, CMake, Bash</div>
        <div class="card"><strong>Embedded:</strong> C/C++, AUTOSAR, CANoe, HIL Testing</div>
      </div>
    </section>

    <footer>
      <p>Connect with me: 
        <a href="https://linkedin.com/in/penchaljammula">LinkedIn</a> | 
        <a href="mailto:penchal.jammula@gmail.com">Email</a>
      </p>
      <p>© 2026 Penchalaiah Jammula • Built for impact</p>
    </footer>
  </div>
</body>
</html>
