<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ra站</title>
  <link href="https://fonts.googleapis.com/css2?family=Zen+Maru+Gothic&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Zen Maru Gothic', sans-serif;
      background-color: #ffeaf4;
      overflow-x: hidden;
    }
    header {
      background-color: #ffc7e3;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);；
    }
    header h1 {
      font-size: 2rem;
      color: #fff;
      text-shadow: 1px 1px 2px #ff8dc1;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #fff;
      font-weight: bold;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #ffe1f0;
    }
    .hero {
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      padding: 4rem 1rem;
      background: linear-gradient(to bottom, #ffeaf4, #fff);
      position: relative;
      z-index: 1;
    }
    .hero h2 {
      font-size: 2.5rem;
      color: #ff88b7;
      margin-bottom: 1rem;
      text-shadow: 1px 1px #fff;
    }
    .hero p {
      font-size: 1.2rem;
      color: #6e6e6e;
      max-width: 600px;
      text-align: center;
    }
    .section {
      padding: 3rem 2rem;
      background-color: #fff;
    }
    .section h3 {
      font-size: 2rem;
      color: #ff78a1;
      margin-bottom: 2rem;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .card {
      background-color: #fff0f6;
      border-radius: 16px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.1);
      padding: 1.5rem;
      transition: transform 0.3s ease;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card h4 {
      font-size: 1.2rem;
      color: #ff4081;
    }
    .card p {
      font-size: 0.95rem;
      color: #555;
    }
    footer {
      background-color: #ffc7e3;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #fff;
    }
    #particles-js {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: 0;
    }
  </style>
</head>
<body>
  <div id="particles-js"></div>
  <header>
    <h1>Ra站</h1>
    <nav>
      <a href="#anime">动漫</a>
      <a href="#galgame">GALGAME</a>
      <a href="#games">3A游戏</a>
      <a href="#movies">电影</a>
      <a href="#bands">乐队</a>
    </nav>
  </header>

  <section class="hero">
    <h2>欢迎来到 Ra站！</h2>
    <p>一个只属于二次元爱好者的梦幻角落，在这里你可以发现最棒的作品，也可以展现自己的风格！</p>
  </section>

  <section class="section" id="anime">
    <h3>🎀 动漫推荐</h3>
    <div class="cards">
      <div class="card">
        <h4>天使降临到我身边</h4>
        <p>日常系顶级萌番，百看不厌。</p>
      </div>
      <div class="card">
        <h4>CLANNAD</h4>
        <p>经典催泪神作，Key社代表作之一。</p>
      </div>
    </div>
  </section>

  <!-- 更多推荐可以按照这个结构扩展 -->

  <footer>
    © 2025 Ra站 | 制作：你最可爱的自己 ✨
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
  <script>
    particlesJS("particles-js", {
      "particles": {
        "number": {"value": 50},
        "color": {"value": "#ffc0cb"},
        "shape": {"type": "circle"},
        "opacity": {"value": 0.5},
        "size": {"value": 4},
        "line_linked": {"enable": false},
        "move": {"speed": 1}
      }
    });
  </script>
</body>
</html>
