<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Cursor – AI Code Editor</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>

<!-- NAVBAR -->
<header class="navbar">
  <div class="nav-container">
    <div class="logo">Cursor</div>
    <ul class="nav-links">
      <li>Features</li>
      <li>Pricing</li>
      <li>Changelog</li>
      <li>Blog</li>
    </ul>
    <button class="primary-btn">Download</button>
  </div>
</header>

<!-- HERO -->
<section class="hero">
  <div class="hero-text">
    <h1>The AI Code Editor</h1>
    <p>Build software faster with an editor designed for AI-powered development.</p>
    <button class="primary-btn">Get Cursor</button>
  </div>
  <div class="hero-image">
    <img src="assets/images/hero.png" alt="Cursor Editor">
  </div>
</section>

<!-- TRUSTED BY -->
<section class="trusted">
  <p>Trusted by developers at</p>
  <div class="logos">
    <img src="assets/images/logo1.png">
    <img src="assets/images/logo2.png">
    <img src="assets/images/logo3.png">
    <img src="assets/images/logo4.png">
  </div>
</section>

<!-- FEATURES -->
<section class="feature">
  <div>
    <h2>Code with AI</h2>
    <p>Understand and modify large codebases instantly.</p>
  </div>
  <img src="assets/images/feature1.png">
</section>

<section class="feature reverse">
  <div>
    <h2>Edit at the speed of thought</h2>
    <p>Natural language instructions that just work.</p>
  </div>
  <img src="assets/images/feature2.png">
</section>

<section class="feature">
  <div>
    <h2>Built for professionals</h2>
    <p>Optimized for real-world development workflows.</p>
  </div>
  <img src="assets/images/feature3.png">
</section>

<!-- FEATURE CARDS -->
<section class="cards">
  <h2>Why developers choose Cursor</h2>
  <div class="card-grid">
    <div class="card">Fast AI edits</div>
    <div class="card">Context-aware</div>
    <div class="card">Secure by design</div>
    <div class="card">VS Code compatible</div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section class="testimonials">
  <div class="testimonial">
    <p>“Cursor feels like the future of coding.”</p>
    <span>— Alex, Software Engineer</span>
  </div>
  <div class="testimonial">
    <p>“It understands my codebase better than I do.”</p>
    <span>— Maya, Full Stack Dev</span>
  </div>
</section>

<!-- USE CASES -->
<section class="use-cases">
  <h2>Used by teams worldwide</h2>
  <div class="use-grid">
    <div class="use-card">
      <img src="assets/images/use1.png">
      <p>Startup engineering</p>
    </div>
    <div class="use-card">
      <img src="assets/images/use2.png">
      <p>Enterprise teams</p>
    </div>
    <div class="use-card">
      <img src="assets/images/use3.png">
      <p>Open source projects</p>
    </div>
  </div>
</section>

<!-- CHANGELOG -->
<section class="changelog">
  <h2>Changelog</h2>
  <ul>
    <li><strong>Jan 2026</strong> — Improved AI context handling</li>
    <li><strong>Dec 2025</strong> — Faster indexing engine</li>
    <li><strong>Nov 2025</strong> — UI performance updates</li>
  </ul>
</section>

<!-- TEAM -->
<section class="team">
  <img src="assets/images/team.png">
  <div>
    <h2>Built by developers</h2>
    <p>We’re building tools we wish we had.</p>
    <button class="primary-btn">Join Us</button>
  </div>
</section>

<!-- FINAL CTA -->
<section class="final-cta">
  <h2>Start coding with Cursor</h2>
  <button class="primary-btn">Download Now</button>
</section>

<!-- FOOTER -->
<footer class="footer">
  <div class="footer-grid">
    <div>
      <h4>Product</h4>
      <p>Features</p>
      <p>Pricing</p>
    </div>
    <div>
      <h4>Company</h4>
      <p>About</p>
      <p>Careers</p>
    </div>
    <div>
      <h4>Resources</h4>
      <p>Blog</p>
      <p>Changelog</p>
    </div>
    <div>
      <h4>Legal</h4>
      <p>Privacy</p>
      <p>Terms</p>
    </div>
  </div>
</footer>

</body>
</html>
:root {
  --bg-main: #050505;
  --bg-secondary: #0f0f0f;
  --border: #1f1f1f;
  --text-primary: #ffffff;
  --text-secondary: #a1a1aa;
  --accent: #4f46e5;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Inter, sans-serif;
  background: var(--bg-main);
  color: var(--text-primary);
}

/* NAV */
.navbar {
  background: var(--bg-secondary);
  border-bottom: 1px solid var(--border);
}
.nav-container {
  max-width: 1200px;
  margin: auto;
  height: 64px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.nav-links {
  display: flex;
  gap: 24px;
  list-style: none;
}

/* BUTTON */
.primary-btn {
  background: var(--accent);
  color: white;
  border: none;
  padding: 10px 18px;
  border-radius: 6px;
  cursor: pointer;
}

/* HERO */
.hero {
  max-width: 1200px;
  margin: 100px auto;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
}
.hero h1 {
  font-size: 56px;
}
.hero p {
  margin: 20px 0;
  color: var(--text-secondary);
}

/* TRUSTED */
.trusted {
  text-align: center;
  margin: 80px 0;
}
.logos {
  display: flex;
  justify-content: center;
  gap: 40px;
  opacity: 0.6;
}

/* FEATURES */
.feature {
  max-width: 1200px;
  margin: 100px auto;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
}
.feature.reverse {
  direction: rtl;
}

/* CARDS */
.cards {
  max-width: 1200px;
  margin: 100px auto;
}
.card-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
}
.card {
  background: var(--bg-secondary);
  padding: 24px;
  border-radius: 10px;
  border: 1px solid var(--border);
}

/* TESTIMONIALS */
.testimonials {
  max-width: 1200px;
  margin: 100px auto;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
}
.testimonial {
  background: var(--bg-secondary);
  padding: 24px;
  border-radius: 12px;
}

/* USE CASES */
.use-cases {
  max-width: 1200px;
  margin: 100px auto;
}
.use-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;
}
.use-card {
  background: var(--bg-secondary);
  padding: 20px;
  border-radius: 12px;
}

/* CHANGELOG */
.changelog {
  max-width: 1200px;
  margin: 100px auto;
}
.changelog ul {
  list-style: none;
}
.changelog li {
  padding: 12px 0;
  border-bottom: 1px solid var(--border);
}

/* TEAM */
.team {
  max-width: 1200px;
  margin: 100px auto;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
}

/* FINAL CTA */
.final-cta {
  text-align: center;
  padding: 120px 20px;
  background: var(--bg-secondary);
}

/* FOOTER */
.footer {
  border-top: 1px solid var(--border);
  padding: 60px 0;
}
.footer-grid {
  max-width: 1200px;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 40px;
}
