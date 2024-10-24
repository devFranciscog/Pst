<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="shortcut icon" href="htmlico.ico" type="image/x-icon" />
    <title>Meu Primeiro Site - Lista de Leitura</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
        color: #333;
        margin: 0;
        padding: 0;
      }

      header {
        background-color: #333;
        color: #fff;
        padding: 10px;
        text-align: center;
      }

      h1,
      h2,
      h3,
      h4 {
        color: #444;
      }

      nav {
        background-color: #555;
        padding: 10px;
        text-align: center;
        position: sticky;
        top: 0;
        z-index: 1000;
      }

      nav a {
        color: #fff;
        text-decoration: none;
        padding: 10px 20px;
        display: inline-block;
      }

      nav a:hover {
        background-color: #444;
        border-radius: 5px;
      }

      .container {
        width: 80%;
        margin: auto;
        overflow: hidden;
        padding: 20px;
      }

      img {
        border-radius: 5px;
        box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        margin: 10px 0;
        width: 200px;
        height: auto;
      }

      p {
        line-height: 1.6;
      }

      details {
        background-color: #eee;
        padding: 10px;
        margin: 10px 0;
        border-radius: 5px;
      }

      summary {
        cursor: pointer;
        font-weight: bold;
      }

      hr {
        border: none;
        height: 1px;
        background-color: #ccc;
        margin: 20px 0;
      }

      .book-section {
        margin-bottom: 40px;
      }

      @media (max-width: 768px) {
        .container {
          width: 95%;
        }

        nav a {
          padding: 5px 10px;
        }

        img {
          width: 150px;
        }
      }
    </style>
  </head>
  <body>
    <header>
      <h1>Lista de Leitura</h1>
      <h4>Por Dev Gilvan</h4>
    </header>

    <nav>
      <a href="#titulo-1">O Senhor dos Anéis</a>
      <a href="#titulo-2">Percy Jackson</a>
    </nav>

    <div class="container">
      <div class="book-section" id="titulo-1">
        <h2>Saga Senhor dos Anéis (J.R.R. Tolkien)</h2>
        <h3>O Senhor dos Anéis: A Sociedade do Anel</h3>
        <img
          src="7sdRZv8qBftYaWQyp3eHDa5TGzzU8hXSXN16yh6X (1).webp"
          alt="Capa do livro A Sociedade do Anel"
        />
        <p>
          O Senhor dos Anéis: <i> Sociedade do Anel</i> escrito por
          <strong>J.J.R. Tolkien</strong> é o primeiro volume da trilogia que
          narra a jornada épica na Terra-média,
          a história começa no Condado, onde Frodo Bolseiro, um hobbit, recebe
          de seu tio Bilbo um anel mágico, que na verdade é o Um Anel, criado
          pelo Senhor do Escuro,
          Sauron, para dominar todos os outros anéis de poder.<br />
          Ao descobrir que Sauron está em busca do anel para recuperar seu
          poder, Gandalf, o mago, aconselha Frodo a deixar o Condado,
          acompanhado de seus amigos Sam, Merry e Pippin, eles partem em uma
          perigosa jornada,
          no caminho, encontram Aragorn (ou Passolargo), um guerreiro que os
          protege até Rivendell, onde uma reunião é convocada para decidir o
          destino do anel.<br />
          Lá, é formada uma sociedade composta por nove membros: Frodo, Sam,
          Merry, Pippin, Aragorn, Gandalf, Legolas (um elfo), Gimli (um anão) e
          Boromir (um homem),
          a missão deles é levar o anel até a Montanha da Perdição, em Mordor, e
          destruí-lo para impedir que Sauron recupere seu poder.<br />
          Durante a jornada, enfrentam vários perigos, incluindo os Nazgûl,
          criaturas sombrias a serviço de Sauron, e são perseguidos por inimigos
          letais,
          no final do livro, a sociedade é desfeita após a morte de Boromir, que
          tenta tomar o anel de Frodo, e a captura de Merry e Pippin por
          orcs.<br />
          Frodo decide seguir sozinho para Mordor, mas Sam o acompanha, jurando
          lealdade.<br />
          A história explora temas de amizade, coragem e a luta entre o bem e o
          mal, estabelecendo um universo rico e detalhado que influenciou a
          literatura de fantasia moderna.
        </p>

        <a
          href="https://youtu.be/0i86oM1nHjM?si=EBlTySCOaoCLzQ2P"
          target="_blank"
          >Ver trailer</a
        >
        <details>
          <summary>Comentário</summary>
          <i>
            A Sociedade do Anel é uma verdadeira obra-prima da fantasia.<br> Tolkien
            nos transporta para a Terra-média, um mundo rico e detalhado, cheio de
            criaturas fascinantes e paisagens deslumbrantes. A narrativa equilibra
            ação, suspense e momentos de tranquilidade, com personagens cativantes
            e uma trama envolvente que explora temas de amizade e coragem. A
            jornada de Frodo e seus companheiros é cheia de desafios, e o livro é
            uma leitura que encanta do início ao fim. É um clássico que todo fã de
            fantasia deveria conhecer.</i
          >
        </details>
        <hr />

        <h3>Senhor dos Anéis: As Duas Torres</h3>
        <img
          src="xMYJG4Iip3LBjeLEVjgQRtUppH3WZ8GgW9FVHPqa.jpg"
          alt="Capa do livro As Duas Torres"
        />
        <p>
          O segundo volume de O Senhor dos Anéis continua após a separação da
          Sociedade do Anel...
        </p>
        <a
          href="https://youtu.be/Al5iC4CnhYc?si=WRbwcfMptP6MsUwj"
          target="_blank"
          >Ver trailer</a
        >
        <details>
          <summary>Comentário</summary>
          <i>Duas Torres é uma sequência intensa e envolvente...</i>
        </details>
        <hr />

        <h3>O Senhor dos Anéis: O Retorno do Rei</h3>
        <img
          src="Li76xJuboh01z3Py31IsfSxxrZzoVhQJBUE0Mt5x.png"
          alt="Capa do livro O Retorno do Rei"
        />
        <p>O Retorno do Rei culmina a épica jornada pela Terra-média...</p>
        <a
          href="https://youtu.be/LiKeQrChkTY?si=EPtNvy77sANyZYPG"
          target="_blank"
          >Ver trailer</a
        >
        <details>
          <summary>Comentário</summary>
          <i>O Retorno do Rei é uma conclusão emocionante para a trilogia...</i>
        </details>
      </div>

      <div class="book-section" id="titulo-2">
        <h2>Saga Percy Jackson e os Olimpianos (Rick Riordan)</h2>
        <h3>O Ladrão de Raios</h3>
        <img
          src="B5COvb0LJLreMBsNiPiaub4oIiru3y6TvqIjwus9.jpg"
          alt="Capa do livro O Ladrão de Raios"
        />
        <p>
          Sinopse: Percy descobre que é um semideus e embarca em uma missão para
          recuperar o raio de Zeus...
        </p>
        <hr />

        <!-- Outros livros da série Percy Jackson... -->
      </div>
    </div>
  </body>
</html>
