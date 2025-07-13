<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mohiddeen Thamsheer | Personal Website</title>
  <style>
    :root {
      --main-bg: #fdfaf6;
      --accent: #4c4b63;
      --highlight: #937b63;
      --text-color: #1f1f1f;
      --light-gray: #888;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Georgia', serif;
      background-color: var(--main-bg);
      color: var(--text-color);
      line-height: 1.8;
      padding: 20px;
    }

    header {
      text-align: center;
      padding: 40px 20px;
    }

    header h1 {
      font-size: 2.5rem;
      color: var(--accent);
      font-family: 'Cambria', serif;
      letter-spacing: 1px;
    }

    header p {
      font-style: italic;
      color: var(--highlight);
      margin-top: 10px;
    }

    nav {
      margin-top: 30px;
      text-align: center;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: var(--accent);
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--highlight);
    }

    section {
      max-width: 800px;
      margin: 50px auto;
      padding: 0 20px;
    }

    h2 {
      color: var(--accent);
      border-left: 5px solid var(--highlight);
      padding-left: 10px;
      margin-bottom: 20px;
    }

    .bio p, .education p {
      margin-bottom: 15px;
      font-size: 1.05rem;
    }

    ul.works {
      list-style: none;
      padding-left: 0;
    }

    ul.works li {
      margin-bottom: 10px;
    }

    ul.works a {
      color: var(--highlight);
      text-decoration: none;
      font-weight: bold;
    }

    ul.works a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 30px 10px;
      color: var(--light-gray);
      font-size: 0.9rem;
      border-top: 1px solid #ddd;
    }

    .arabic {
      font-family: 'Scheherazade', serif;
      font-size: 1.2rem;
      color: var(--highlight);
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Mohiddeen Thamsheer</h1>
    <p>Writer • Translator • Islamic Scholar</p>
    <nav>
      <a href="#about">About</a>
      <a href="#education">Education</a>
      <a href="#works">Works</a>
    </nav>
  </header>

  <section id="about" class="bio">
    <h2>About</h2>
    <p>Mohiddeen Thamsheer is a respected writer, translator, and Islamic scholar. His writings reflect a deep engagement with Islamic philosophy, contemporary society, and literary expression. He currently serves as a translator at <strong>Thijori Web Magazine</strong>.</p>
    <p>His scholarly and literary works, ranging from Islamic studies to cultural history, have been widely appreciated for their clarity, depth, and spiritual insight.</p>
  </section>

  <section id="education" class="education">
    <h2>Education</h2>
    <p><strong>Secular Education:</strong> Completed graduation in <em>History, Economics, and Political Science</em> from <strong>Mangalore University</strong>.</p>
    <p><strong>Islamic Studies:</strong> Completed Islamic graduation in <em>Theology and Jurisprudence</em> from <strong>KGN Islamic Science Dawa College, Mithur</strong>.</p>
    <p><strong>Postgraduate:</strong> Currently pursuing Master's in <em>Islamic Science</em> at <strong>Madin Kulliya of Islamic Science College</strong>.</p>
  </section>

  <section id="works" class="works">
    <h2>Selected Works</h2>
    <ul class="works">
      <li><a href="https://thijori.in/what-is-islamic-university-part-1/" target="_blank">What is Islamic University – Part 1</a></li>
      <li><a href="https://thijori.in/turbon-a-religious-symbol/" target="_blank">Turban: A Religious Symbol</a></li>
      <li><a href="https://thijori.in/lively-hisotry-ofkalpattanam/" target="_blank">Lively History of Kayalpattinam</a></li>
      <li><em>...and many more articles on culture, religion, and history on Thijori.</em></li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 Mohiddeen Thamsheer | Designed in Ainjmal Style</p>
  </footer>

  <script>
    // Smooth fade-in animation
    document.addEventListener("DOMContentLoaded", () => {
      document.body.style.opacity = 0;
      document.body.style.transition = "opacity 1.5s ease-in-out";
      setTimeout(() => {
        document.body.style.opacity = 1;
      }, 100);
    });
  </script>
</body>
</html>
