index.html
<!DOCTYPE html>
<img>
<img src="imagens/minha-foto.jpg" alt="Dowloads portifolio" />
">
<img src="imagens/minha-foto.jpg" alt="Minha foto" width="200" height="200" />
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Meu Portfólio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 20px;
    }
    h2 {
      color: #333;
    }
    .projeto {
      background-color: #fff;
      margin-bottom: 15px;
      padding: 15px;
      border-radius: 8px;
    }
    a {
      color: #0066cc;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Meu Portfólio</h1>
    <p>Desenvolvido por [Rafael Praxedes Rodrigues]</p>
  </header>

  <section id="sobre">
    <img src="imagens/minha-foto.jpg" alt="Minha Foto">
    <h2>Sobre Mim</h2>
    <p>Sou um desenvolvedor apaixonado por criar soluções web. Aqui estão alguns dos meus projetos.</p>
  </section>

  <section id="projetos">
    <h2>Projetos</h2>
    <div class="projeto">
      <h3>Projeto 1: Site Pessoal</h3>
      <p>Descrição do projeto. Tecnologias usadas: HTML, CSS, JavaScript.</p>
      <a href="https://github.com/seuusuario/projeto1" target="_blank">Ver no GitHub</a>
    </div>
    <div class="projeto">
      <h3>Projeto 2: App de Tarefas</h3>
      <p>Descrição do projeto. Programação: React, Node.js.</p>
      <a href="https://github.com/seuusuario/projeto2" target="_blank">Ver no GitHub</a>
    </div>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>Entre em contato comigo pelo email: seu rpraxedes@prof.educacao.sp.gov.br</p>
  </section>
</body>
</html>
