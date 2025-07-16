<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>B2B Rust Клан</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(135deg, #000000, #001f1f);
      color: #00ffcc;
      text-align: center;
      font-size: 18px;
      line-height: 1.6;
    }
    header {
      padding: 50px 20px;
    }
    h1 {
      font-size: 3.5rem;
      color: #00ffcc;
      text-shadow: 0 0 15px #00ffcc;
    }
    p.slogan {
      font-size: 1.5rem;
      color: #b0f0ff;
      margin-bottom: 40px;
    }
    .btn {
      background-color: #00ffcc;
      color: #000;
      padding: 18px 35px;
      font-size: 1.2rem;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      text-decoration: none;
      box-shadow: 0 0 20px #00ffcc;
      margin: 0 10px;
    }
    .btn:hover {
      background-color: #00ccaa;
    }
    section {
      padding: 50px 20px;
    }
    footer {
      margin-top: 60px;
      font-size: 1rem;
      color: #228877;
      padding: 20px;
    }
    form {
      max-width: 400px;
      margin: 20px auto;
      text-align: left;
      font-size: 1rem;
    }
    form label {
      display: block;
      margin-bottom: 5px;
      color: #b0f0ff;
    }
    form input, form textarea {
      width: 100%;
      padding: 8px;
      margin-bottom: 15px;
      border: none;
      border-radius: 6px;
      font-family: 'Orbitron', sans-serif;
      font-size: 1rem;
    }
    form button {
      width: 100%;
      background-color: #00ffcc;
      color: #000;
      padding: 12px;
      border: none;
      border-radius: 8px;
      font-size: 1.1rem;
      cursor: pointer;
      box-shadow: 0 0 15px #00ffcc;
    }
    form button:hover {
      background-color: #00ccaa;
    }
  </style>
</head>
<body>
  <header>
    <h1>B2B RUST КЛАН</h1>
    <p class="slogan">СИЛА, ДИСЦИПЛИНА И ЧЕСТЬ В МИРЕ RUST</p>
    <a href="https://discord.gg/vZJdW7nC5q" class="btn" target="_blank">Вступить в Discord</a>
    <button class="btn" onclick="document.getElementById('apply-form').scrollIntoView({behavior:'smooth'})">Подать заявку</button>
  </header>

  <section>
    <h2>Кто мы?</h2>
    <p>B2B — это командный подход, слаженная игра и чёткое распределение ролей. У нас нет места хаосу — каждый знает свою роль и действует на результат.</p>
  </section>

  <section>
    <h2>Кого мы ищем?</h2>
    <p>
      Ищем бойцов с опытом и пониманием командной игры:
      <br>✅ Возраст: <strong>15+ лет</strong>
      <br>✅ Часы в игре: <strong>1500+ часов</strong>
      <br>✅ Микрофон и Discord — ОБЯЗАТЕЛЬНО
      <br>✅ Терпимость к токсикам — <strong>низкая</strong>
      <br>❌ Спам в войсе и нарушение дисциплины не допускаются
    </p>
  </section>

  <section>
    <h2>Что мы предлагаем?</h2>
    <ul style="list-style: none; padding: 0; font-size: 1.2rem;">
      <li>🔰 Организованный Discord с графиками и ролями</li>
      <li>💣 Частые PvP и рейды — каждый день</li>
      <li>👥 Поддержка и уважение внутри команды</li>
      <li>🚀 Возможность карьерного роста — от бойца до офицера</li>
    </ul>
  </section>

  <section id="apply-form">
    <h2>Форма заявки</h2>
    <form onsubmit="alert('Заявка отправлена! Мы свяжемся с вами в Discord.'); return false;">
      <label for="username">Никнейм в Rust:</label>
      <input type="text" id="username" name="username" required>
      
      <label for="hours">Часы в Rust:</label>
      <input type="number" id="hours" name="hours" required min="1500">
      
      <label for="micro">Есть микрофон и Discord?</label>
      <input type="text" id="micro" name="micro" required placeholder="Да / Нет">
      
      <label for="message">Почему хотите в B2B?</label>
      <textarea id="message" name="message" rows="4" required></textarea>
      
      <button type="submit">Отправить заявку</button>
    </form>
  </section>

  <footer>
    <p><strong>B2B</strong> — это стиль, это уверенность, это сила. Мы привержены порядку, сплочённости и командному взаимодействию.</p>
    <p>&copy; 2025 B2B Rust Clan. Все права защищены.</p>
  </footer>
</body>
</html>
