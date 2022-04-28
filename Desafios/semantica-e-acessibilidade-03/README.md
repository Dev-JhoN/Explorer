<p align="center">
	<img src="https://img.shields.io/github/stars/Hallssss/Explorer?color=49AA26&labelColor=000000&style=flat-square" alt="Stars">
	<img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
	<img alt="Forks" src="https://img.shields.io/github/forks/Hallssss/Explorer?color=49AA26&labelColor=000000&style=flat-square">
<p>

<h1>🖥️ Preview</h1>

<p>
  	<img align="center" alt="Rocketseat Explorer" src="./github/banner_desafio_02.png">
</p>

---

<h1>📕 Sobre o desafio</h1>
<p>
Este foi um desafio desenvolvido durante o stage 02 do explorer.

Neste desafio foi entregue o código do projeto 02 que foi desenvolvido durante as aulas da fase 2  do stage 02, porem o código sofreu algumas alterações ele não apresenta a semântica correta, Como você pode ver na imagem acima, a página <s>(exceto o botão)</s> continua funcionando normalmente mas, quando você abrir o código, vai se deparar com os elementos do HTML todos bagunçados. Minha missão foi corrigir os problemas apresentados na imagem acima e devolver o layout a sua forma original deixando o site mais acessível.

</p>

<h1>💡 Código do desafio</h1>
<p>
Abaixo você terá o código <s>(quebrado)</s> do desafio.

<details>
<summary>Código do Desafio</summary>

<p>index.html</p>

```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Treine me</title>

    <link href="https://fonts.googleapis.com/css2?family=Mulish:wght@400;700&family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="style.css">

  </head>
  <body>
    <div class="page">
        <div class="nav">
          <a id="logo" href="#">
            <img src="images/logo.svg" alt="Treine.me" />
          </a>
          <div class="list">
            <div class="item"><a href="#">Home</a></div>
            <div class="item"><a href="#">Sobre</a></div>
            <div class="item"><a href="#">Treinar</a></div>
          </div>
        </div class="nav">
    
      <div class="main">
        <div>
          <div class="title">Treinos <span>exclusivos</span> para você!</div>

          <div class="subtitle">
            Nós criamos treinos <strong>exclusivos e únicos para você.</strong></br>
            Invista no seu corpo e <strong>tenha muito mais performance</strong> e qualidade de vida.
          </div>

          <div class="button">
              <img src="images/whats.svg" alt="Ícone do whatsapp">
              Comece já
          </div>

        </div>

        <img src="images/img.png" alt="Desenho de uma mulher pulando corta numa academia.">
      </div>
      <div class="footer">
          fale conosco no instagram <a href="https://instagram.com/treineme" target="_blank">@treine.me</a>
      </div>
    </div>

    <img id="balls" src="images/balls.svg" alt="Bolinhas decorativas verdes no canto inferior direito da página.">

  </body>
</html>
```

<p>style.css</p>

```css
body {
body {
  margin: 0;

  font-family: "Open Sans", sans-serif;

  background: linear-gradient(180deg, rgb(227, 255, 248, 0) 82.08%, rgb(227, 255, 248, 0.38) 100%);

  min-height: 100vh;
}

.page {
  width: 1000px;
  margin: 0 auto;
  padding-top: 65px;
}

.nav {
  display: flex;
  justify-content: space-between;
  align-items: center;

  margin-bottom: 55px;
}

.list {
  display: flex;
  gap: 48px;
  list-style: none;
  margin: 0;
  padding: 0;
}

a {
  color: #1f1534;
  text-decoration: none;
}

.list .item a {
    opacity: 0.5;
}

.list .item a:hover {
  font-weight: bold;
  opacity: 1;
}

.list,
.title {
  font-family: "Mulish", sans-serif;
}

.main {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.title {
  font-size: 49px;
  line-height: 56px;
  color: #1f1534;

  font-weight: normal;

  width: 490px;
}

.title span {
  color: #89c5cc;
  font-weight: bold;
}

.subtitle {
  font-size: 14px;
  line-height: 28px;
  color: #7d7987;

  margin: 40px 0;
}

.button {
  color: white;
  text-transform: uppercase;
  font-family: "Open Sans", sans-serif;

  background: #69B99D;
  border: 0;
  padding: 14px 32px 15px;

  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;

  border-radius: 4px;

  cursor: pointer;
}

.footer {
  font-size: 14px;
  line-height: 28px;

  text-align: center;

  margin-top: 80px;
}

.footer a {
  font-weight: bold;
}

#balls {
    position: fixed;
    bottom: 0;
    right: 0;
}
```

</details>
</p>

---

<h1>🚀 Tecnologias</h1>

<p>
Aplicação desenvolvida usando as seguintes tecnologias:
</p>

<ul>
  <li>HTML</li>
  <li>CSS</li>
</ul>

---

<h1>✨ Compreendido</h1>

<ul>
  <li>Ferramentas dev do navegador</li>
  <li>Interpretação de layouts (Figma)</li>
  <li>Reforçado os conceitos de Semântica e acessibilidade</li>
  <li>Reforçado os conceitos de refatoração e melhoria</li>
  <li>Reforçado todos os conceitos estudados no projeto 02</li>
</ul>

---

<h1>🔓 Licença</h1>
<p>
Este projeto está sob licença MIT.  <a href="./.github/LICENSE">Clique aqui</a> para mais detalhes.
</p>
