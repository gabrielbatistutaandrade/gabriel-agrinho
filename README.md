# gabriel-agrinhoModelo 2 
Estrutura html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Festejando a Conexão do Campo e da Cidade</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom, #f0f8ff, #e0ffe0);
      color: #333;
    }

    header {
      background-color: #4CAF50;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }Estrutura html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Festejando a Conexão do Campo e da Cidade</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom, #f0f8ff, #e0ffe0);
      color: #333;
    }

    header {
      background-color: #4CAF50;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }

    header h1 {
      margin: 0;

    nav {
      background-color: #3e8e41;
      text-align: center;
      padding: 0.5rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    .container {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }

    .section {
      margin-bottom: 2rem;
    }

    .section h2 {
      color: #2c6e3c;
      margin-bottom: 1rem;
    }

    .section p {
      line-height: 1.6;
    }

    .image-box {
      text-align: center;
      margin-top: 2rem;
    }

    .image-box img {
      max-width: 100%;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    footer {
      background-color: #2e7031;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Festejando a Conexão do Campo e da Cidade</h1>
  </header>

  <nav>
    <a href="#objetivo">Objetivo</a>
    <a href="#atividades">Atividades</a>
    <a href="#galeria">Galeria</a>
  </nav>

  <div class="container">

    <section id="objetivo" class="section">
      <h2>Objetivo do Projeto</h2>
      <p>Este projeto tem como foco celebrar e fortalecer a conexão entre o campo e a cidade, destacando a importância da agricultura, do comércio, da cultura e da cooperação mútua para um desenvolvimento sustentável e justo.</p>
    </section>

    <section id="atividades" class="section">
      <h2>Atividades Desenvolvidas</h2>
      <ul>
        <li>Feira de produtos locais: “Do Campo à Mesa”.</li>
        <li>Entrevistas com agricultores e comerciantes urbanos.</li>
        <li>Oficinas de culinária e sustentabilidade.</li>
        <li>Exposição de artes com materiais recicláveis.</li>
      </ul>
    </section>

    <section id="galeria" class="section">
      <h2>Galeria de Imagens</h2>
      <div class="image-box">
        <img src="https://via.placeholder.com/800x400.png?text=Campo+e+Cidade&quot; alt="Conexão do Campo e Cidade">
      </div>
    </section>

  </div>

  <footer>
    <p>&copy; 2025 Projeto Agrinho – Todos os direitos reservados.</p>
  </footer>

</body>
</html>

Estrutura CSS:
/* Estilo geral */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f2fbe0;
  color: #333;
}

/* Cabeçalho */
header {
  background-color: #4CAF50;
  color: white;
  padding: 2rem 1rem;
  text-align: center;
}

/* Navegação */
nav {
  background-color: #388e3c;
  text-align: center;
  padding: 1rem;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 0 15px;
  font-weight: bold;
}

/* Conteúdo principal */
.container {
  padding: 2rem;
  max-width: 900px;
  margin: auto;
}

/* Seções */
.section {
  margin-bottom: 2rem;
}

.section h2 {
  color: #2e7d32;
  margin-bottom: 1rem;
}

.section p {
  line-height: 1.6;
}

/* Espaço do aluno */
.custom-area {
  background-color: #ffffff;
  border: 2px dashed #ccc;
  padding: 1rem;
  text-align: center;
  color: #777;
  margin-top: 1rem;
}

/* Rodapé */
footer {
  background-color: #2e7031;
  color: white;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}

