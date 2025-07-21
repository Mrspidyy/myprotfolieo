//HTML CODE;
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Student Portfolio</title>
  <link rel="stylesheet" href="spidyy.css" />
</head>
<body img src="">

  <header>
    <div class="container">
      <h1>Hi, [I'm Varun]</h1>
      <p>Web Developer & Student</p>
      <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <section id="about">
    <div class="container about-container">
      <img src="C:\Users\91834\Desktop\spidyy011\spiderman.jpg" alt="Student Photo" class="profile-pic" />
      <div class="about-text">
        <h2>About Me</h2>
        <p>
          I'm currently a student passionate about web development, learning HTML, CSS, and JavaScript.
          I enjoy building projects and learning by doing.
        </p>
      </div>
    </div>
  </section>

  <section id="projects">
    <div class="container">
      <h2>My Projects</h2>
      <div class="project-grid">
        <div class="project-card">
          <h3>Portfolio Website</h3>
          <p>A personal website made using HTML & CSS.</p>
        </div>
        <div class="project-card">
          <h3>Wheather-App</h3>
          <p>Whearther app made with React JS.</p>
        </div>
      </div>
    </div>
</section>

  <section id="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <p>Email: <a href="link">arshamvarun4@gmail.com</a></p>
      <p>Instagram: <a href="">__mr__spidyy__</a> </p>
      <p>phone No;<a href="">6303279704</a></p>
      <p>GitHub: <a href="https://github.com/yourusername" target="_blank">mrspidyy</a></p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Your Name</p>
  </footer>

</body>
</html
//CSS CODE:
/* Reset and body styling */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', sans-serif;
}

body {
  line-height: 1.6;
  color: #333;
  background: url('') no-repeat center center fixed;
  background-size: cover;
  backdrop-filter: brightness(0.9);
}

/* Container */
.container {
  width: 90%;
  max-width: 1000px;
  margin: auto;
  padding: 20px 0;
}

/* Header */
header {
  background-color: rgba(0, 122, 204, 0.85);
  color: white;
  padding: 40px 0;
  text-align: center;
}

header nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}

/* About Section */
.about-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.profile-pic {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid #007acc;
  margin-bottom: 20px;
}

.about-text {
  max-width: 600px;
}

/* Projects */
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.project-card {
  background-color: white;
  padding: 20px;
  border: 1px solid #ccc;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

/* Contact */
section#contact a {
  color: #007acc;
}

/* Footer */
footer {
  text-align: center;
  background-color: #333;
  color: white;
  padding: 15px 0;
  margin-top: 40px;
}

  
