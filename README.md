# SamarM-web.github.io
Research and Academic works

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Samar Moussa</title>
  <meta name="description" content="Academic & Research Portfolio" />
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="container">
    <nav class="nav">
      <a class="brand" href="#">Samar Moussa</a>
      <div class="links">
        <a href="#about">About</a>
        <a href="#publications">Publications</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>

    <section class="hero">
      <div>
        <h1>Hi, I’m Samar.</h1>
        <p class="subtitle">Academic & Research Portfolio</p>
        <p class="meta">
          Statistics • Data Science • Quantitative Conflict Research
        </p>

        <div class="buttons">
          <a class="btn" href="#projects">View Projects</a>
          <a class="btn secondary" href="#publications">Publications</a>
        </div>

        <div class="social">
          <a href="https://github.com/SamarM-web" target="_blank" rel="noreferrer">GitHub</a>
          <span>•</span>
          <a href="#" target="_blank" rel="noreferrer">LinkedIn</a>
          <span>•</span>
          <a href="mailto:your@email.com">Email</a>
        </div>
      </div>

      <div class="card">
        <div class="avatar" aria-label="Profile photo placeholder"></div>
        <p class="small">Add your photo later (optional).</p>
      </div>
    </section>
  </header>

  <main class="container">
    <section id="about" class="section">
      <h2>About</h2>
      <p>
        Write 4–6 lines here about your background and interests.
        Keep it concise and academic.
      </p>
    </section>

    <section id="publications" class="section">
      <h2>Publications</h2>
      <ul class="list">
        <li>
          <strong>Paper title here</strong><br />
          Authors • Venue/Year • <a href="#">PDF</a> • <a href="#">Code</a>
        </li>
      </ul>
      <p class="small">We’ll add a nice format next.</p>
    </section>

    <section id="projects" class="section">
      <h2>Projects</h2>
      <div class="grid">
        <article class="tile">
          <h3>Project title</h3>
          <p>1–2 lines describing what you built and why it matters.</p>
          <div class="tags"><span>Python</span><span>Stats</span></div>
          <a class="arrow" href="#">Read more →</a>
        </article>

        <article class="tile">
          <h3>Project title</h3>
          <p>Short description. Add links later.</p>
          <div class="tags"><span>Research</span><span>Data</span></div>
          <a class="arrow" href="#">Read more →</a>
        </article>
      </div>
    </section>

    <section id="contact" class="section">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:your@email.com">your@email.com</a></p>
    </section>
  </main>

  <footer class="footer">
    <div class="container small">© <span id="y"></span> Samar Moussa</div>
  </footer>

  <script>
    document.getElementById("y").textContent = new Date().getFullYear();
  </script>
</body>
</html>

