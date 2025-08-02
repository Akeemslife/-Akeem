<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>*Akeem | Music</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #111;
      color: #fff;
    }

    header {
      background: #000;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 20px;
      font-weight: bold;
    }

    .section {
      padding: 4rem 2rem;
      max-width: 800px;
      margin: auto;
    }

    .hero {
      text-align: center;
      padding-top: 5rem;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    .music-embed iframe {
      width: 100%;
      height: 200px;
      border: none;
      margin-top: 1rem;
    }

    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #aaa;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <div><strong>*Akeem</strong></div>
    <nav>
      <a href="#about">About</a>
      <a href="#music">Music</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero section">
    <h1>Welcome to *Akeem's World</h1>
    <p>Music made for fun — and for the ones who care.</p>
    <div class="music-embed">
      <!-- You can replace this embed with your track -->
      <iframe src="https://open.spotify.com/embed/track/2TpxZ7JUBn3uw46aR7qd6V" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    </div>
  </section>

  <section id="about" class="section">
    <h2>About *Akeem</h2>
    <p>Always had sum for music. I do this for fun and for people who care about me!</p>
  </section>

  <section id="music" class="section">
    <h2>More Music</h2>
    <p>Check out more tracks below:</p>
    <!-- Replace or duplicate for more embeds -->
    <div class="music-embed">
      <iframe src="https://open.spotify.com/embed/playlist/37i9dQZF1DXcBWIGoYBM5M" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"></iframe>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact</h2>
    <p>Hit me up on Instagram or email!</p>
    <ul>
      <li><a href="mailto:akeem@example.com" style="color: #1db954;">akeem@example.com</a></li>
      <li><a href="https://instagram.com/akeem" target="_blank" style="color: #1db954;">@akeem</a></li>
    </ul>
  </section>

  <footer>
    &copy; 2025 *Akeem. All rights reserved.
  </footer>

</body>
</html>
