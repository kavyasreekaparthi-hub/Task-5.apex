<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dynamic Portfolio</title>
  <meta name="description" content="A performant, responsive, cross-browser portfolio web app with dynamic features." />
  <link rel="preload" href="style.css" as="style" />
  <link rel="stylesheet" href="style.css" />
  <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>⚡</text></svg>">
</head>
<body>
  <header class="site-header">
    <div class="container">
      <h1 class="logo">My Portfolio</h1>
      <nav class="nav">
        <button class="nav-toggle" aria-label="Toggle navigation">☰</button>
        <ul class="nav-links">
          <li><a href="#about">About</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main>
    <section id="hero" class="hero">
      <div class="container">
        <h2>Hi, I'm <span id="name-placeholder">Developer</span></h2>
        <p class="lead">I build fast, responsive, and compatible web experiences.</p>
        <button id="theme-toggle" aria-label="Toggle dark/light theme">Toggle Theme</button>
      </div>
    </section>

    <section id="about" class="section">
      <div class="container">
        <h2>About Me</h2>
        <p>I’m a web developer focused on building performant and responsive applications. This portfolio demonstrates dynamic loading, lazy images, theme toggling, and offline support.</p>
      </div>
    </section>

    <section id="projects" class="section">
      <div class="container">
        <h2>Projects</h2>
        <div id="project-grid" class="grid">
          <!-- Projects injected by JavaScript -->
        </div>
        <button id="load-more" class="btn">Load More</button>
      </div>
    </section>

    <section id="contact" class="section">
      <div class="container">
        <h2>Contact</h2>
        <form id="contact-form" novalidate>
          <div class="form-row">
            <label for="email">Email</label>
            <input type="email" id="email" required placeholder="you@example.com" />
          </div>
          <div class="form-row">
            <label for="message">Message</label>
            <textarea id="message" required placeholder="Your message"></textarea>
          </div>
          <button type="submit" class="btn">Send</button>
          <p id="form-status" aria-live="polite"></p>
        </form>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>&copy; <span id="year"></span> My Portfolio. Built with vanilla JS. <small>Works offline & optimized.</small></p>
    </div>
  </footer>

  <script type="module" src="script.js" defer></script>
  <noscript><p style="text-align:center;">This site works best with JavaScript enabled.</p></noscript>
</body>
</htm
