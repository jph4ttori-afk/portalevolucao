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

header {
  background: linear-gradient(135deg, #1a1a1a, #121212);
  padding: 40px 20px;
  text-align: center;
  box-shadow: 0 6px 20px rgba(0,0,0,0.6);
  position: relative;
  overflow: hidden;
}

.header-container h1 {
  font-family: 'Roboto', sans-serif;
  font-size: 36px;
  color: #f0f0f0;
  margin: 0;
  text-shadow: 2px 2px 8px rgba(0,0,0,0.7);
}

.header-container h1 span {
  color: #27ae60;
}

.subtitle {
  font-size: 18px;
  color: #ccc;
  margin-top: 10px;
}

.header-buttons {
  margin-top: 25px;
}

.header-buttons .btn {
  display: inline-block;
  margin: 10px 8px;
  padding: 12px 28px;
  background-color: #ff6b6b;
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  font-size: 16px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.5);
  transition: all 0.3s ease;
  position: relative;
}

/* Animação sobe/desce */
.header-buttons .btn:hover {
  transform: translateY(-8px);
  box-shadow: 0 8px 18px rgba(0,0,0,0.7);
  background-color: #e55050;
}

/* Pequena animação para o título também */
.header-container h1 {
  transition: all 0.4s ease;
}

.header-container h1:hover {
  transform: translateY(-5px);
  color: #2ecc71;
}

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
