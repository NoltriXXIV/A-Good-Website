# A-Good-Website
**INDEX HTML**
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm a web developer who loves to build beautiful and functional websites.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    I Will make a good web 
    for my school project
    
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: Derekkamau2012@gmail.com
  </section>

  <footer>
    <p>© 2025 My Portfolio. All rights reserved.</p>
  </footer>
</body>
</html>

**STYLE CSS**
/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #f2f2f2;
  color: #333;
  line-height: 1.6;
}

/* Header styles */
header {
  background-color: #222;
  color: #fff;
  padding: 20px 0;
  text-align: center;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 20px;
  margin-top: 10px;
}

nav a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

/* Section styles */
section {
  padding: 40px 20px;
  max-width: 800px;
  margin: auto;
  background: #fff;
  margin-top: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
}

section h2 {
  margin-bottom: 15px;
  color: #222;
}

ul {
  padding-left: 20px;
}

a {
  color: #0077cc;
}

a:hover {
  text-decoration: underline;
}

/* Footer styles */
footer {
  text-align: center;
  padding: 20px;
  background-color: #222;
  color: #fff;
  margin-top: 30px;
}
