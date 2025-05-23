seu-repositorio/
│
├── index.html
├── style.css
└── img/
    └── avatar-perfil.png

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfólio de Rafael</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

<header>
  <!-- Foto do avatar -->
  <img src="img/avatar-perfil.png" alt="Avatar de Rafael" class="avatar" />
  <h1>Rafael - Desenvolvedor Web</h1>
</header>

<section>
  <h2>Sobre mim</h2>
  <p>Sou Rafael, professor e desenvolvedor web. Ensino programação e crio projetos usando HTML, CSS e JavaScript. Veja meus projetos abaixo!</p>
</section>

<section>
  <h2>Habilidades</h2>
  <ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
    <li>Scratch</li>
  </ul>
</section>

<!-- Você pode adicionar mais seções aqui -->

</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 20px;
  line-height: 1.6;
  background-color: #f4f4f4;
}

header {
  text-align: center;
  margin-bottom: 30px;
}

.avatar {
  border-radius: 50%;
  width: 150px;
  height: 150px;
  object-fit: cover; /* Garante que a imagem fique redonda e ajustada */
}

h1 {
  color: #333;
}

section {
  background-color: #fff;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 8px;
}

h2 {
  margin-top: 0;
}

ul {
  list-style-type: square;
}

@@ -381,14 +381,6 @@ <h1 class="display-4 titulos">Contatos</h1>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>
    <script src="js/bootstrap/bootstrap.bundle.min.js"></script>
    <script src="js/jquery-3.5.1.min.js"></script>
    <script>
        var $doc = $('html, body');
            $('a[href*="#"]:not([href="#"])').click(function () {
                $doc.animate({
                    scrollTop: $($.attr(this, 'href')).offset().top
                }, 500);
                return false;
            });
    </script>
    <script src="js/scroll.js"></script>
</body>
</html>

@@ -0,0 +1,17 @@
/**
 * @file: scroll.js
 * @author: Paulo Alves
 * @description: script responsável pela configuração de uso do scroll nos links internos da página index. 
 * @version 1.0.1 (07/06/2020)
 */

var $doc = $("html, body");
$('a[href*="#"]:not([href="#"])').click(function () {
  $doc.animate(
    {
      scrollTop: $($.attr(this, "href")).offset().top,
    },
    500
  );
  return false;
});


@@ -0,0 +1,17 @@
/**
 * @file: scroll.js
 * @author: Paulo Alves
 * @description: script responsável pela configuração de uso do scroll nos links internos da página index. 
 * @version 1.0.1 (07/06/2020)
 */

var $doc = $("html, body");
$('a[href*="#"]:not([href="#"])').click(function () {
  $doc.animate(
    {
      scrollTop: $($.attr(this, "href")).offset().top,
    },
    500
  );
  return false;
});

git init
git add .
git commit -m "Atualização do portfólio com foto"
git branch -M main
git remote add origin https://github.com/seu-usuario/seu-repositorio.git
git push -u origin main
