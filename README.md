<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Grill Bar Dacha</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #111;
      color: #fff;
    }

    header {
      background: url('https://images.unsplash.com/photo-1555992336-03a23c7b20ee') center/cover;
      height: 60vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    header h1 {
      font-size: 48px;
      background: rgba(0,0,0,0.6);
      padding: 20px;
      border-radius: 10px;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background: #222;
      padding: 15px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px;
      max-width: 900px;
      margin: auto;
    }

    .card {
      background: #1c1c1c;
      padding: 20px;
      border-radius: 10px;
      margin-top: 20px;
    }

    .btn {
      display: inline-block;
      padding: 10px 20px;
      background: #e63946;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      margin-top: 10px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #000;
      margin-top: 40px;
    }
  </style>
</head>

<body>

<header>
  <h1>🔥 Grill Bar Dacha</h1>
</header>

<nav>
  <a href="#about">Про нас</a>
  <a href="#menu">Меню</a>
  <a href="#contact">Контакти</a>
</nav>

<section id="about">
  <h2>Про нас</h2>
  <div class="card">
    Grill Bar Dacha — це місце з атмосферою відпочинку, смачного грилю та домашнього затишку.  
    Ми готуємо страви з вогню, соковиті піци та улюблені закуски.
  </div>
</section>

<section id="menu">
  <h2>Меню</h2>
  <div class="card">
    🍕 Піца — класична та фірмова  
    🔥 Страви на грилі  
    🥗 Салати  
    🥤 Напої  

    <br><br>
    <a class="btn" href="#">Скачати повне меню</a>
  </div>
</section>

<section id="contact">
  <h2>Контакти</h2>
  <div class="card">
    📍 Славута, вул. Лісна 30В <br>
    📞 068 410 13 17 <br>
    📸 Instagram: @grill_bar_dacha_
  </div>
</section>

<footer>
  © 2026 Grill Bar Dacha. Всі права захищені.
</footer>

</body>
</html>
