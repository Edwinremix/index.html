# index.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Edwin Daniel | Portfolio</title>
<style>
* { box-sizing: border-box; }
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #070914;
  color: white;
  text-align: center;
}
header { padding: 24px; }
nav a {
  color: #b6c9ff;
  margin: 8px;
  text-decoration: none;
}
.hero { padding: 70px 20px; }
.photo {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  border: 3px solid #64eaff;
  object-fit: cover;
}
.glow {
  background: linear-gradient(90deg,#64eaff,#a879ff);
  color: transparent;
  background-clip: text;
  -webkit-background-clip: text;
}
section {
  padding: 25px;
  max-width: 700px;
  margin: 20px auto;
}
.card {
  background: #11172a;
  border: 1px solid #33446f;
  border-radius: 15px;
  margin: 15px;
}
footer { padding: 25px; color: #9ba6c4; }
</style>
</head>
<body>
<header>
  <h2 class="glow">EDWIN DANIEL</h2>
  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>
  <div class="hero">
    <img class="photo" src="assets/edwin.jpg"
         alt="Edwin Daniel"
         onerror="this.style.display='none'">
    <h1>Hi, I'm <span class="glow">Edwin Daniel</span></h1>
    <p>Dream big. Learn every day. Build the future.</p>
  </div>

  <section id="about" class="card">
    <h2 class="glow">About Me</h2>
    <p>Hello! I'm Edwin Daniel. I love technology,
    creativity, and learning new skills.</p>
  </section>

  <section id="skills" class="card">
    <h2 class="glow">My Skills</h2>
    <p>Technology • Creative Design • Problem Solving</p>
  </section>

  <section id="projects" class="card">
    <h2 class="glow">My Projects</h2>
    <p>Personal Portfolio Website — my first project.</p>
    <p>More projects coming soon!</p>
  </section>

  <section id="contact" class="card">
    <h2 class="glow">Contact Me</h2>
    <p>Email: YOUR_EMAIL@example.com</p>
    <p>Replace this with your email address.</p>
  </section>
</main>

<footer>© 2026 Edwin Daniel | Built for the future 🚀</footer>
</body>
</html>
