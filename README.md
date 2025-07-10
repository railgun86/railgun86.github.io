<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Ra站</title>
  <link href="https://fonts.googleapis.com/css2?family=Zen+Maru+Gothic&display=swap" rel="stylesheet">
  <style>
    body, h1, h2, h3, p, label, a, nav {
      margin:0; padding:0;
      font-family:'Zen Maru Gothic', sans-serif;
    }
    body {
      overflow-x:hidden;
      background-image:
        url('https://images.pexels.com/photos/62672/pexels-photo-62672.jpeg'),
        url('https://wallpapersok.com/wallpapers/anime-aesthetic-tram-in-city-6775tr7q0p0519mb.html'),
        url('https://stock.adobe.com/images/a-beautiful-japanese-tokyo-city-town-in-the-evening-houses-at-the-street-anime-cartoonish-artstyle-cozy-lofi-asian-architecture-16-9-4k-resolution-generative-ai/626035560'),
        url('https://in.pinterest.com/pin/319826011057338178/');
      background-size: cover, cover, cover, cover;
      background-position: center;
      background-attachment: fixed;
    }

    header {
      background-color:rgba(255,199,227,0.8);
      padding:1rem 2rem;
      display:flex;
      justify-content:space-between;
      align-items:center;
      box-shadow:0 4px 6px rgba(0,0,0,0.1);
      position:relative; z-index:3;
    }
    header h1 { font-size:2rem; color:#fff; text-shadow:1px 1px 2px #f78bc5 }
    nav a {
      margin: 0 1rem;
      text-decoration:none;
      color:#fff;
      font-weight:bold;
      transition:color .3s;
    }
    nav a:hover { color:#ffe1f0 }

    .hero {
      text-align:center;
      padding:4rem 1rem;
      background: rgba(255,234,244,0.8);
      position:relative; z-index:2;
    }
    .hero h2 { font-size:2.5rem; color:#ff88b7; text-shadow:1px 1px #fff; margin-bottom:.5rem }
    .hero p { color:#6e6e6e; font-size:1.2rem }

    .section {
      margin:2rem auto;
      max-width:800px;
      background:rgba(255,255,255,0.9);
      padding:2rem;
      border-radius:16px;
      box-shadow:0 8px 16px rgba(0,0,0,0.1);
      position:relative; z-index:2;
    }
    .section h3 { font-size:2rem; color:#ff78a1; margin-bottom:1rem }
    form input, form textarea {
      width:100%;
      padding:.5rem;
      margin:.5rem 0 1rem;
      border:1px solid #ffc7e3;
      border-radius:8px;
    }
    form button {
      background:#ff78a1;
      color:#fff;
      border:none;
      padding:.75rem 1.5rem;
      border-radius:12px;
      cursor:pointer;
      font-weight:bold;
    }
    form button:hover { background:#ff5e90 }

    footer {
      text-align:center;
      padding:1rem;
      background:rgba(255,199,227,0.8);
      color:#fff;
      position:relative; z-index:2;
    }

    /* 粒子保留，取消遮挡 */
    #particles-js {
      position:fixed;
      top:0; left:0;
      width:100%; height:100%;
      z-index:1;
      pointer-events:none;
    }
  </style>
</head>
<body>

  <div id="particles-js"></div>

  <header>
    <h1>Ra站</h1>
    <nav>
      <a href="#galgame">GALGAME</a>
    </nav>
  </header>

  <section class="hero">
    <h2>  Ra站！</h2>
    <p>此処は幻想郷</p>
  </section>

  <section class="section" id="message">
    <h3>📬 给 Ra站 留言</h3>
    <form action="https://formspree.io/f/xblyylwd" method="POST">
      <label>君の名字：<input type="text" name="name" required></label>
      <label>留言の内容：<textarea name="message" rows="5" required></textarea></label>
      <button type="submit">发射</button>
    </form>
  </section>

  <footer>
    © 2025 Ra站 | 制作：Furandoru_
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
  <script>
    particlesJS("particles-js", {
      particles: {
        number: { value: 50 },
        color: { value: "#ffc0cb" },
        shape: { type: "circle" },
        opacity: { value: 0.5 },
        size: { value: 4 },
        line_linked: { enable: false },
        move: { speed: 1 }
      }
    });
  </script>

</body>
</html>
