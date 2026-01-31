<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu Site</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #111;
      color: #fff;
    }

    /* Menu Superior */
    nav {
      background: #1b1b1b;
      padding: 15px 25px;
      display: flex;
      justify-content: flex-end;
      gap: 25px;
      position: sticky;
      top: 0;
      z-index: 10;
      border-bottom: 1px solid #333;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-size: 18px;
      font-weight: bold;
      transition: 0.2s;
    }

    nav a:hover {
      color: #00aaff;
    }

    /* Conteúdo da Página */
    .container {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
      text-align: center;
    }

    h1 {
      font-size: 42px;
      margin-bottom: 10px;
    }

    p {
      font-size: 18px;
      color: #dddddd;
      line-height: 1.7;
    }
  </style>
</head>

<body>

  <!-- Menu -->
  <nav>
    <a href="anime.html">Anime</a>
    <a href="jogos.html">Jogos</a>
    <a href="opiniao.html">Opinião</a>
  </nav>

  <!-- Página Principal -->
  <div class="container">
    <h1>Bem-vindo ao meu site!</h1>
    <p>Escolha uma categoria no menu acima.</p>
    <p>Aqui eu posto sobre jogos, animes e minhas opiniões.</p>
  </div>

</body>
</html>
