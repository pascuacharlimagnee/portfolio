<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Portfolio</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial;
  background: #0f172a;
  color: white;
}

header {
  text-align: center;
  padding: 50px 20px;
  background: linear-gradient(135deg, #0f172a, #1e293b);
}

header h1 {
  font-size: 40px;
}

header p {
  color: #94a3b8;
}

.container {
  width: 90%;
  max-width: 1000px;
  margin: auto;
  padding: 20px;
}

h2 {
  margin-bottom: 15px;
  color: #38bdf8;
}

.card {
  background: #1e293b;
  padding: 20px;
  margin-bottom: 15px;
  border-radius: 12px;
  transition: 0.3s;
}

.card:hover {
  transform: scale(1.03);
  background: #334155;
}

.skills span {
  display: inline-block;
  background: #334155;
  padding: 8px 12px;
  margin: 5px;
  border-radius: 20px;
}

footer {
  text-align: center;
  padding: 20px;
  color: #94a3b8;
}
</style>

</head>
<body>

<header>
  <h1>Your Name</h1>
  <p>IT Support | Unity Game Developer | Arduino Enthusiast</p>
</header>

<div class="container">

  <section>
    <h2>About Me</h2>
    <div class="card">
      <p>
        Computer Science graduate with experience in game development using Unity, 
        Arduino projects, IT troubleshooting, and CCTV installation.
      </p>
    </div>
  </section>

  <section>
    <h2>Skills</h2>
    <div class="skills">
      <span>Unity (C#)</span>
      <span>Arduino</span>
      <span>Video Editing</span>
      <span>IT Support</span>
      <span>CCTV Installation</span>
    </div>
  </section>

  <section>
    <h2>Projects</h2>

    <div class="card">
      <h3>🎮 3D Unity Game</h3>
      <p>Developed a simple 3D game with player movement and camera system.</p>
    </div>

    <div class="card">
      <h3>🔌 Arduino Project</h3>
      <p>Created a sensor-based system using Arduino components.</p>
    </div>

    <div class="card">
      <h3>📷 CCTV Installation</h3>
      <p>Installed and configured CCTV systems with remote mobile viewing.</p>
    </div>

  </section>

  <section>
    <h2>Contact</h2>
    <div class="card">
      <p>Email: your@email.com</p>
    </div>
  </section>

</div>

<footer>
  <p>© 2026 Your Name</p>
</footer>

</body>
</html>
