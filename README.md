# Kenzo-DarkWeb
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kenzo | Ethical Hacker</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
  <style>
    body {
      background-color: #0c0c1d;
      color: #00fff7;
      font-family: 'Courier New', monospace;
      text-align: center;
    }
    h1 {
      background: linear-gradient(90deg, #00fff7, #ff00ff, #00fff7);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: glow 3s linear infinite;
    }
    @keyframes glow {
      0%, 100% { text-shadow: 0 0 5px #00fff7, 0 0 10px #ff00ff; }
      50% { text-shadow: 0 0 20px #00fff7, 0 0 30px #ff00ff; }
    }
    .card {
      border: 2px solid transparent;
      border-radius: 0.75rem;
      padding: 1rem;
      background: #111122;
      background-clip: padding-box;
      position: relative;
      transition: transform 0.4s ease, box-shadow 0.4s ease;
    }
    .card::before {
      content: '';
      position: absolute;
      top: -2px; left: -2px; right: -2px; bottom: -2px;
      background: linear-gradient(270deg, #00fff7, #ff00ff, #00fff7);
      border-radius: inherit;
      z-index: -1;
      background-size: 400% 400%;
      animation: borderMove 8s ease infinite;
    }
    @keyframes borderMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    .card:hover {
      transform: rotate3d(1, 1, 0, 10deg) scale(1.05);
      box-shadow: 0 0 25px #00fff7;
    }
    .stars {
      color: gold;
      letter-spacing: 2px;
    }
    .typing {
      border-right: 2px solid #00fff7;
      white-space: nowrap;
      overflow: hidden;
      display: inline-block;
      animation: typing 3s steps(30, end), blink 0.75s step-end infinite;
    }
    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }
    @keyframes blink {
      from, to { border-color: transparent }
      50% { border-color: #00fff7; }
    }
    .container {
      max-width: 420px;
      margin: auto;
      padding: 1rem;
    }
  </style>
</head>
<body>
  <div class="container" data-aos="fade-up">
    <h1 class="text-2xl font-bold mb-2">Kenzo | Ethical Hacker</h1>
    <p class="typing text-sm mb-6">Security Researcher & Pentester</p>

    <section class="card mb-6" data-aos="zoom-in">
      <h2 class="text-lg font-bold mb-2">About Me</h2>
      <p class="text-sm text-cyan-200">Saya Kenzo, fokus dalam keamanan siber & ethical hacking. Tujuan saya adalah mengamankan sistem & berbagi pengetahuan.</p>
    </section>

    <section class="card mb-6" data-aos="fade-up">
      <h2 class="text-lg font-bold mb-2">Skills</h2>
      <p>Programming <span class="stars">★★★★☆</span></p>
      <p>Penetration Testing <span class="stars">★★★★★</span></p>
      <p>Network Security <span class="stars">★★★★☆</span></p>
      <p>Reverse Engineering <span class="stars">★★★☆☆</span></p>
      <p>OSINT & Threat Intel <span class="stars">★★★★★</span></p>
    </section>

    <section class="card mb-6" data-aos="fade-up">
      <h2 class="text-lg font-bold mb-2">Projects</h2>
      <p>AutoRecon <span class="stars">★★★★☆</span></p>
      <p>XSS Detector <span class="stars">★★★★★</span></p>
      <p>Enterprise Audit <span class="stars">★★★★★</span></p>
      <p>Cloud Infra Review <span class="stars">★★★★☆</span></p>
    </section>

    <section class="card mb-6" data-aos="zoom-in">
      <h2 class="text-lg font-bold mb-2">Contact</h2>
      <p><a href="mailto:pykcyber@gmail.com" class="underline">pykcyber@gmail.com</a></p>
      <p><a href="https://wa.me/6283143490913" class="underline">+62 831-4349-0913</a></p>
    </section>

    <footer class="text-xs text-cyan-400 mt-6">
      <p>Website ini dibuat oleh <strong>Kenzo</strong></p>
      <p>© 2025 Kenzo. Semua hak cipta dilindungi.</p>
    </footer>
  </div>

  <script>AOS.init();</script>
</body>
</html>
