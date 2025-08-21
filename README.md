<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Painel Drip Client</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f0f0f0;
      color: #333;
    }

    header {
      background: #111;
      color: #fff;
      padding: 15px 20px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 {
      margin: 0;
      font-size: 22px;
      letter-spacing: 1px;
    }

    nav {
      margin-top: 8px;
    }

    nav a {
      color: #fff;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ff6600;
    }

    section {
      padding: 40px 20px;
      text-align: center;
    }

    h2 {
      margin-bottom: 20px;
      font-size: 28px;
    }

    /* Produtos */
    .product-card {
      background: #fff;
      padding: 25px;
      margin: auto;
      border-radius: 12px;
      box-shadow: 0 0 12px rgba(0,0,0,0.1);
      max-width: 1000px;
    }

    .badge {
      background: #ff6600;
      color: #fff;
      padding: 6px 12px;
      border-radius: 6px;
      font-size: 14px;
      font-weight: bold;
    }

    .product-card h3 {
      margin: 15px 0;
    }

    .product-card ul {
      list-style: none;
      padding: 0;
      margin: 20px 0;
      text-align: left;
    }

    .product-card ul li {
      margin: 6px 0;
    }

    .price-box {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      margin-top: 15px;
    }

    .plan {
      background: #f9f9f9;
      border-radius: 12px;
      padding: 15px;
      text-align: center;
      margin: 10px;
      min-width: 180px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
    }

    .btn-red, .btn-yellow, .btn-green {
      display: inline-block;
      margin-top: 8px;
      padding: 10px 20px;
      border-radius: 20px;
      font-weight: bold;
      color: #fff;
      text-decoration: none;
      transition: 0.3s;
    }

    .btn-red {
      background: #e60000;
      box-shadow: 0 0 10px #e60000;
    }
    .btn-red:hover {
      background: #ff1a1a;
      box-shadow: 0 0 20px #ff1a1a;
    }

    .btn-yellow {
      background: #e6b800;
      box-shadow: 0 0 10px #e6b800;
      color: #000;
    }
    .btn-yellow:hover {
      background: #ffd11a;
      box-shadow: 0 0 20px #ffd11a;
    }

    .btn-green {
      background: #009933;
      box-shadow: 0 0 10px #009933;
    }
    .btn-green:hover {
      background: #00cc44;
      box-shadow: 0 0 20px #00cc44;
    }

    footer {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <!-- Cabeçalho -->
  <header>
    <h1>🔥 Painel Drip Client 🔥</h1>
    <nav>
      <a href="#inicio">Início</a>
      <a href="#produtos">Produtos</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <!-- Início -->
  <section id="inicio">
    <h2>Bem-vindo ao Drip Client</h2>
    <p>O melhor painel mobile com funções avançadas e suporte dedicado 🚀</p>
  </section>

  <!-- Produtos -->
  <section id="produtos">
    <h2>Nossos Produtos</h2>
    <div class="product-card">
      <span class="badge">OFERTA ESPECIAL</span>
      <h3>Drip Client Mobile</h3>
      <ul>
        <li>✔ AIMKILL - COVER - UP PLAYER</li>
        <li>✔ TELEKILL - SPEED - GHOST</li>
        <li>✔ Maior probabilidade de acerto</li>
        <li>✔ Painel completo com todas as funções</li>
        <li>✔ Compatível com todos Android</li>
        <li>✔ Suporte prioritário</li>
      </ul>

      <div class="price-box">
        <div class="plan">
          <p><b>1 Dia - R$15,90</b></p>
          <a href="https://link-1dia.com" target="_blank" class="btn-red">🛒 Adquirir</a>
        </div>

        <div class="plan">
          <p><b>7 Dias - R$32,90</b></p>
          <a href="https://link-7dias.com" target="_blank" class="btn-yellow">🛒 Adquirir</a>
        </div>

        <div class="plan">
          <p><b>15 Dias - R$57,90</b></p>
          <a href="https://link-15dias.com" target="_blank" class="btn-green">🛒 Adquirir</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato">
    <h2>Contato</h2>
    <p>📩 Entre em contato pelo WhatsApp: <b>(00) 00000-0000</b></p>
    <p>📧 Email: bcabeluda00@gmail.com</p>
  </section>

  <!-- Rodapé -->
  <footer>
    <p>© 2025 Drip Client - Todos os direitos reservados</p>
  </footer>

</body>
</html>
