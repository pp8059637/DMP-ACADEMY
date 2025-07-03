<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DMP ACADEMY - MOD STORE</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Share Tech Mono', monospace;
      background: black;
      color: #00ff00;
      overflow-x: hidden;
    }
    .hero {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      height: 100vh;
      text-align: center;
      background: linear-gradient(135deg, #000000 0%, #001f1f 100%);
      animation: bgPulse 5s infinite alternate;
    }
    @keyframes bgPulse {
      0% { background: #000000; }
      100% { background: #001a1a; }
    }
    h1 {
      font-size: 3em;
      text-shadow: 0 0 10px #00ff00, 0 0 20px #00ff00;
    }
    p {
      margin-top: 1em;
      font-size: 1.2em;
      max-width: 600px;
    }
    .button {
      margin-top: 2em;
      padding: 0.7em 2em;
      background: transparent;
      border: 2px solid #00ff00;
      color: #00ff00;
      text-decoration: none;
      transition: 0.3s;
    }
    .button:hover {
      background: #00ff00;
      color: black;
      box-shadow: 0 0 10px #00ff00;
    }
    .section {
      padding: 4em 2em;
      border-top: 1px solid #004d4d;
      background: #000000ee;
    }
    .section h2 {
      font-size: 2em;
      margin-bottom: 1em;
      color: #00ffff;
    }
    .features li {
      list-style: none;
      margin: 1em 0;
    }
    .contact a {
      color: #00ffff;
      text-decoration: underline;
    }
    .footer {
      text-align: center;
      padding: 2em;
      background: #001111;
      font-size: 0.9em;
      border-top: 1px solid #004d4d;
    }
  </style>
</head>
<body>
  <div class="hero">
    <h1>👾 DMP ACADEMY - MOD STORE</h1>
    <p>Elite Tools, Premium Mods, Hacker Vibes.<br />Cyber Themed. Mobile Optimized. Super Fast.</p>
    <a href="#features" class="button">Explore Features</a>
  </div>

  <div class="section" id="features">
    <h2>⚡ Features</h2>
    <ul class="features">
      <li>✅ Dark + Cyberpunk Style UI</li>
      <li>📱 Mobile First Responsive Design</li>
      <li>🧠 AI-Powered Tools (Coming Soon)</li>
      <li>🔐 Secure Mod Delivery</li>
      <li>🧨 Fast Loading with Clean UI</li>
    </ul>
  </div>

  <div class="section contact">
    <h2>📞 Contact</h2>
    <p>Email: <a href="mailto:kalharapathum831@gmail.com">kalharapathum831@gmail.com</a></p>
    <p>WhatsApp: <a href="https://wa.me/94712345678">+94 71 234 5678</a></p>
  </div>

  <div class="footer">
    <p>🛠️ Built with 💚 using HTML, CSS & JS | © DMP ACADEMY 2025</p>
  </div>

  <script>
    // JS Animation effect
    document.querySelector(".hero h1").addEventListener("mouseover", () => {
      document.body.style.background = "#001a00";
    });
    document.querySelector(".hero h1").addEventListener("mouseout", () => {
      document.body.style.background = "black";
    });
  </script>
</body>
</html>
