# Pamonha
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Café D'Ouro</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Roboto&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      background-color: #fdfaf6;
      color: #3e2f24;
    }

    header {
      background-color: #3e2f24;
      color: white;
      padding: 20px 40px;
      text-align: center;
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2.5em;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
    }

    .hero {
      background-image: url('https://images.unsplash.com/photo-1509042239860-f550ce710b93');
      background-size: cover;
      background-position: center;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 1px 1px 5px #000;
    }

    .hero h2 {
      font-size: 3em;
      text-align: center;
      padding: 20px;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .section-title {
      font-family: 'Playfair Display', serif;
      font-size: 2em;
      margin-bottom: 20px;
      text-align: center;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }

    .product {
      width: 300px;
      border: 1px solid #ddd;
      border-radius: 8px;
      overflow: hidden;
      background: white;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .product h3 {
      font-size: 1.2em;
      margin: 10px;
    }

    .product p {
      font-size: 0.9em;
      margin: 0 10px 10px;
    }

    footer {
      background-color: #3e2f24;
      color: white;
      text-align: center;
      padding: 20px;
    }

    .social a {
      margin: 0 10px;
      color: white;
      text-decoration: none;
    }

    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25d366;
      color: white;
      padding: 10px 15px;
      border-radius: 50px;
      font-weight: bold;
      text-decoration: none;
      box-shadow: 0 2px 10px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>
  <header>
    <h1>Café D'Ouro</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#produtos">Produtos</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <div class="hero">
    <h2>Cinco razões para amar o café</h2>
  </div>

  <section id="sobre">
    <h2 class="section-title">Sobre Nós</h2>
    <p>No coração do sabor e da hospitaldade, a Café D'Ouro se destaca com um ponto de encontro para os amantes de café especial.
        Desde a nossa inauguração, temos como missão oferecer mais do que uma boa bebida: proporcionamos uma experiencia 
        sensorial completa, que valoriza os aromas, os métodos de preparo e a origem dos que celebram o terroir  a inovação na xícara.
    </p>
  </section>

  <section id="produtos">
    <h2 class="section-title">Nossos Produtos</h2>
    <div class="products">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1511920170033-f8396924c348" alt="Café em grãos">
        <h3>Café em Grãos</h3>
        <p>Graões 100% arábica, cultivados em altitudes elevadas e colhidos com rigoroso cuidado.
            Apresentam notas aromáticas complexas, acidez equilibrada e finalização suave. Um Café de origem
            controlada, torra artesanal e sabor marcante.
        </p>
      </div>
      <div class="product">
        <img src="img/pexels-enginakyurt-1552617.jpg" alt="">
        <h3>Meta alcançada com sabor de vitória</h3>
        <p>Com orgulho, celebramos a venda de 800 pacotes de café, alcançamos o lucro de R$ 6.080,00.
            Essa conquista reflete nosso compromisso com a qualidade e confinça dos nossos clientes. Seguimos firmes,
            prontos para ir ainda mais longe!
        </p>
      </div>
      <div class="product">
        <img src="img/fnc.jpg" alt="Funcionarios">
        <h3>Funcionários</h3>
        <p>Por trás de cada conquista da nossa empesa, existe uma equipe dedicada e comprometida pelo
            que faz. São eles que tornam possível levar a qualidade em cada detalhe do nosso trabalho.
            <p>Camila- Gestora financeira</p>
            <p>Gustavo- Gerente de atendimento</p>
            <p>Rodrigo- Encarregado de compras</p>
            <p>Gabrielly e Davi- Analista de Marketing</p>
        </p>
      </div>
    </div>
  </section>

  <section id="contato">
    <h2 class="section-title">Contato</h2>
    <p>📍 Endereço: Rua dos Aromas, 123 - Centro, São Paulo - SP</p>
    <p>📞 Telefone: (11) 91234-5678</p>
    <p>📸 Instagram: <a href="https://instagram.com/cafed'ouro" target="_blank">@cafed'ouro</a></p>
    <p>Entre em contato com a Café D'Ouro pelo WhatsApp ou siga nossas redes sociais para novidades e promoções.</p>
  </section>

  <footer>
    <p>&copy; 2025 Café D'Ouro. Todos os direitos reservados.</p>
    <div class="social">
      <a href="https://instagram.com/fivesolutionscafe" target="_blank">Instagram</a>
      <a href="#">Facebook</a>
      <a href="#">LinkedIn</a>
    </div>
  </footer>

  <a href="https://wa.me/5511912345678" class="whatsapp" target="_blank">Fale conosco</a>
</body>
</html>
