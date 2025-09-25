<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Laços Angolanos</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #d80027; /* vermelho da bandeira */
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #000;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      padding: 14px 20px;
      display: block;
    }
    nav a:hover {
      background: #444;
    }
    section {
      padding: 40px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #d80027;
      margin-bottom: 20px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: #fff;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .card img {
      width: 100%;
      height: 160px;
      object-fit: cover;
    }
    .card div {
      padding: 15px;
    }
    footer {
      background: #000;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Laços Angolanos</h1>
    <p>Unindo cultura, paisagens e encontros em Angola</p>
  </header>

  <nav>
    <a href="#cultura">Cultura</a>
    <a href="#paisagens">Paisagens</a>
    <a href="#turismo">Turismo</a>
    <a href="#eventos">Eventos</a>
    <a href="#conversas">Conversas</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="cultura">
    <h2>Cultura Angolana</h2>
    <div class="grid">
      <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Angolan_Dance.jpg" alt="Dança tradicional">
        <div>
          <h3>Dança Tradicional</h3>
          <p>Expressões culturais que refletem a identidade angolana.</p>
        </div>
      </div>
      <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Angolan_Music.jpg" alt="Música">
        <div>
          <h3>Música</h3>
          <p>Kizomba, semba e outros ritmos que encantam o mundo.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="paisagens">
    <h2>Paisagens de Angola</h2>
    <div class="grid">
      <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/7/79/Kalandula_Falls_2.jpg" alt="Quedas de Kalandula">
        <div>
          <h3>Quedas de Kalandula</h3>
          <p>Uma das maiores quedas de água de África.</p>
        </div>
      </div>
      <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/Miradouro_da_Lua.jpg" alt="Miradouro da Lua">
        <div>
          <h3>Miradouro da Lua</h3>
          <p>Formações geológicas únicas e impressionantes.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="turismo">
    <h2>Locais Turísticos</h2>
    <div class="grid">
      <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Ilha_do_Mussulo.jpg" alt="Ilha do Mussulo">
        <div>
          <h3>Ilha do Mussulo</h3>
          <p>Praias paradisíacas perto de Luanda.</p>
        </div>
      </div>
      <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Fortaleza_de_S%C3%A3o_Miguel.jpg" alt="Fortaleza de São Miguel">
        <div>
          <h3>Fortaleza de São Miguel</h3>
          <p>Património histórico que conta a história do país.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="eventos">
    <h2>Próximos Eventos</h2>
    <ul>
      <li><strong>Festival de Música Kizomba</strong> - Luanda, 15 de Outubro 2025</li>
      <li><strong>Feira de Artesanato</strong> - Benguela, 22 de Novembro 2025</li>
      <li><strong>Encontro Cultural</strong> - Huambo, 10 de Dezembro 2025</li>
    </ul>
  </section>

  <section id="conversas">
    <h2>Espaço de Conversas</h2>
    <p>Em breve, um espaço interativo para trocar ideias e marcar encontros.</p>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>Email: <a href="mailto:info@lacosangolanos.com">info@lacosangolanos.com</a></p>
    <p>WhatsApp: +244 900 000 000</p>
  </section>

  <footer>
    <p>&copy; 2025 Laços Angolanos - Comunidade e Cultura</p>
  </footer>
</body>
</html>
