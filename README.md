<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nipson K C | GitHub Space Theme</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: white;
      background: radial-gradient(ellipse at bottom, #1b2735 0%, #090a0f 100%);
      overflow: hidden;
    }
    .stars {
      width: 2px;
      height: 2px;
      background: white;
      box-shadow: 0 0 1px #fff;
      position: absolute;
      animation: twinkle 1s infinite alternate;
    }
    @keyframes twinkle {
      from { opacity: 0.2; }
      to { opacity: 1; }
    }
    .container {
      text-align: center;
      padding: 100px 20px;
    }
    h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }
    p {
      font-size: 1.2em;
      max-width: 700px;
      margin: 0 auto 40px;
    }
    .badges img {
      margin: 5px;
    }
  </style>
</head>
<body>
  <div id="stars-container"></div>
  <div class="container">
    <h1>🚀 Nipson K C</h1>
    <p>An adaptive, innovative Developer & Project Manager thriving in the ever-evolving world of technology. Always learning, building, and pushing boundaries in Android, web, AI/ML, and cloud solutions.</p>
    <div class="badges">
      <img src="https://img.shields.io/badge/Java-00008B?style=flat-square&logo=openjdk&logoColor=white" />
      <img src="https://img.shields.io/badge/C%23-00008B?style=flat-square&logo=c-sharp&logoColor=white" />
      <img src="https://img.shields.io/badge/PHP-00008B?style=flat-square&logo=php&logoColor=white" />
      <img src="https://img.shields.io/badge/React-00008B?style=flat-square&logo=react&logoColor=white" />
      <img src="https://img.shields.io/badge/Laravel-00008B?style=flat-square&logo=laravel&logoColor=white" />
      <img src="https://img.shields.io/badge/ASP.NET_Core-00008B?style=flat-square&logo=dotnet&logoColor=white" />
      <img src="https://img.shields.io/badge/Python-00008B?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/SQL-00008B?style=flat-square&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/Django-00008B?style=flat-square&logo=django&logoColor=white" />
    </div>
  </div>

  <script>
    const numStars = 200;
    const container = document.getElementById('stars-container');
    for (let i = 0; i < numStars; i++) {
      let star = document.createElement('div');
      star.className = 'stars';
      star.style.top = Math.random() * window.innerHeight + 'px';
      star.style.left = Math.random() * window.innerWidth + 'px';
      container.appendChild(star);
    }
  </script>
</body>
</html>
