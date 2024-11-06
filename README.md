<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anaflix - Assista aos Melhores Filmes</title>
  <style>
    /* Estilos gerais */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #2b0a3d;
      color: #ffffff;
      text-align: center;
    }

    /* Cabeçalho */
    header {
      padding: 20px;
      background-color: #4b0082;
      color: #e6e6fa;
    }

    h1 {
      font-size: 2.5em;
      margin: 0;
    }

    /* Grid de Filmes */
    .catalogo {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      padding: 20px;
    }

    /* Estilo dos cartões de filmes */
    .filme-card {
      background-color: #5d3c6e;
      border-radius: 8px;
      width: 320px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
    }

    .filme-card iframe {
      width: 100%;
      height: 180px;
    }

    .filme-info {
      padding: 15px;
    }

    .filme-titulo {
      font-size: 18px;
      font-weight: bold;
      color: #dda0dd;
      margin: 0 0 10px;
    }

    .filme-descricao {
      font-size: 14px;
      color: #e0bee0;
    }
  </style>
</head>
<body>

  <!-- Cabeçalho do Site -->
  <header>
    <h1>Anaflix</h1>
    <p>Assista aos melhores filmes e trailers na sua plataforma favorita!</p>
  </header>

  <!-- Catálogo de Filmes -->
  <div class="catalogo">

    <!-- Card do Filme 1 -->
    <div class="filme-card">
      <iframe src="https://www.youtube.com/embed/5PSNL1qE6VY" title="Avatar" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="filme-info">
        <h2 class="filme-titulo">Avatar</h2>
        <p class="filme-descricao">Em um planeta alienígena, um ex-soldado é enviado para infiltrar-se em uma tribo nativa.</p>
      </div>
    </div>

    <!-- Card do Filme 2 -->
    <div class="filme-card">
      <iframe src="https://www.youtube.com/embed/bLvqoHBptjg" title="Forrest Gump" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="filme-info">
        <h2 class="filme-titulo">Forrest Gump</h2>
        <p class="filme-descricao">Forrest Gump, um homem simples, faz história nos EUA, vivendo eventos significativos da história moderna.</p>
      </div>
    </div>

    <!-- Card do Filme 3 -->
    <div class="filme-card">
      <iframe src="https://www.youtube.com/embed/ol67qo3WhJk" title="Gladiador" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="filme-info">
        <h2 class="filme-titulo">Gladiador</h2>
        <p class="filme-descricao">Maximus é um general romano que se torna gladiador após a morte de sua família e luta por vingança.</p>
      </div>
    </div>

    <!-- Card do Filme 4 -->
    <div class="filme-card">
      <iframe src="https://www.youtube.com/embed/Lm8p5rlrSkY" title="Interstellar" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="filme-info">
        <h2 class="filme-titulo">Interstellar</h2>
        <p class="filme-descricao">Uma missão espacial é lançada para salvar a humanidade, enquanto exploram buracos negros e viagens no tempo.</p>
      </div>
    </div>

    <!-- Card do Filme 5 -->
    <div class="filme-card">
      <iframe src="https://www.youtube.com/embed/rPln5eNfFzQ" title="O Poderoso Chefão" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="filme-info">
        <h2 class="filme-titulo">O Poderoso Chefão</h2>
        <p class="filme-descricao">A saga da família mafiosa Corleone, que enfrenta desafios enquanto lida com lealdade e traição.</p>
      </div>
    </div>

  </div>

</body>
</html>
