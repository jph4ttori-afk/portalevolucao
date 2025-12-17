<header>
  <div class="header-container">
    <h1>Portal <span>Evolução</span></h1>
    <p class="subtitle">Site oficial do Portal Evolução – Conhecimento que transforma sua vida!</p>
    <nav class="header-buttons">
      <a href="#vollpilates" class="btn">Cursos de Pilates</a>
      <a href="#outroscursos" class="btn">Outros Cursos</a>
      <a href="#contato" class="btn">Contato</a>
    </nav>
  </div>
</header>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

  /* Estilo do Cabeçalho */
  header {
    background: linear-gradient(135deg, #2e8b57, #1c6e3f); /* Gradiente verde */
    padding: 50px 20px;
    text-align: center;
    box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
    position: relative;
    overflow: hidden;
    animation: fadeInHeader 1s ease-out; /* Animação do cabeçalho */
  }

  /* Estilo do título */
  .header-container h1 {
    font-family: 'Roboto', sans-serif;
    font-size: 36px;
    color: #fff;
    margin: 0;
    text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.5);
    transition: color 0.3s ease, transform 0.3s ease;
  }

  /* Estilo do texto destacado no título */
  .header-container h1 span {
    color: #27ae60; /* Verde brilhante */
  }

  /* Efeito de Hover no Título */
  .header-container h1:hover {
    transform: translateY(-10px);
    color: #2ecc71; /* Cor mais brilhante ao passar o mouse */
  }

  /* Estilo do subtítulo */
  .subtitle {
    font-size: 18px;
    color: #ccc;
    margin-top: 10px;
    transition: color 0.3s ease;
  }

  /* Efeito de Hover no Subtítulo */
  .subtitle:hover {
    color: #27ae60; /* Cor ao passar o mouse */
  }

  /* Estilo dos botões do cabeçalho */
  .header-buttons {
    margin-top: 30px;
  }

  .header-buttons .btn {
    display: inline-block;
    margin: 10px 12px;
    padding: 12px 28px;
    background-color: #ff6b6b; /* Cor de fundo dos botões */
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    font-size: 16px;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
    transition: all 0.3s ease;
    position: relative;
  }

  /* Efeito de Hover nos Botões */
  .header-buttons .btn:hover {
    transform: translateY(-8px);
    box-shadow: 0 8px 18px rgba(0, 0, 0, 0.6);
    background-color: #e55050; /* Cor do botão ao passar o mouse */
  }

  /* Animação de entrada suave do cabeçalho */
  @keyframes fadeInHeader {
    from {
      opacity: 0;
      transform: translateY(-30px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  /* Responsividade para dispositivos pequenos */
  @media (max-width: 600px) {
    .header-container h1 {
      font-size: 28px;
    }

    .subtitle {
      font-size: 16px;
    }

    .header-buttons .btn {
      font-size: 14px;
      padding: 10px 22px;
    }
  }
</style>
