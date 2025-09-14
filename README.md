<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Green Advocacy Environmental care</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container">
      <h1 class="logo">Green Advocacy</h1>
      <nav>
        <ul class="nav">
          <li><a href="#">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <h2>Welcome!</h2>
      <p>This is a simple static site template you can deploy to GitHub Pages.</p>
      <button id="cta">Click me</button>
    </section>

    <section id="about" class="card">
      <h3>About this template</h3>
      <p>Minimal HTML, CSS, and JavaScript. Easy to customize.</p>
    </section>

    <section id="contact" class="card">
      <h3>Contact</h3>
      <form id="contactForm">
        <label>
          Your name
          <input name="name" type="text" required />
        </label>
        <label>
          Message
          <textarea name="message" required></textarea>
        </label>
        <button type="submit">Send</button>
      </form>
      <div id="formResult" aria-live="polite"></div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">© <span id="year"></span> My Website</div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
