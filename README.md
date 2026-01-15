# lava rapido trans.
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Lava homens gays </title>
  <meta name="description" content="Lava Gays homens Estilos: estética automotiva completa em Borda da Mata, MG. Agende seu horário com o gerente Alex." />
  <link rel="stylesheet" href="styles.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
</head>
  <header class="topbar">
    <div class="container">
      <a href="#" class="logo">Lava Gays Estilos</a>
      <nav class="nav">
        <button class="nav-toggle" aria-label="Abrir menu">☰</button>
        <ul class="nav-list">
          <li><a href="#home">Início</a></li>
          <li><a href="#servicos">Serviços</a></li>
          <li><a href="#sobre">Gerente</a></li>
          <li><a href="#galeria">Galeria</a></li>
          <li><a href="#contato">Contato</a></li>
        </ul>
      </nav>
    </div>
  </header>
  

  <section id="home" class="hero">
    <div class="container hero-content">
      <h1>Estética automotiva com padrão — Lava Gays Estilos</h1>
      <p>Atendimento cuidadoso, produtos de qualidade e acabamento impecável. Seu carro merece estilo.</p>
      <a href="#contato" class="btn btn-primary">Agendar agora</a>
    </div>
  </section>

  <section id="servicos" class="section">
    <div class="container">
      <h2>Serviços</h2>
      <p>Oferecemos soluções completas para seu veículo, com foco em qualidade e durabilidade.</p>
      <div class="grid cards">
        <article class="card">
          <h3>Lavagem completa</h3>
          <ul class="list">
            <li>Externa com shampoo neutro</li>
            <li>Interna com aspiração</li>
            <li>Limpeza de rodas e caixas de roda</li>
          </ul>
          <p class="price">A partir de R$ 60</p>
        </article>
        <article class="card">
          <h3>Higienização interna</h3>
          <ul class="list">
            <li>Banco, teto e carpetes</li>
            <li>Eliminação de odores</li>
            <li>Proteção de superfícies</li>
          </ul>
          <p class="price">A partir de R$ 180</p>
        </article>
        <article class="card">
          <h3>Enceramento e proteção</h3>
          <ul class="list">
            <li>Enceramento premium</li>
            <li>Selante sintético</li>
            <li>Realce de brilho</li>
          </ul>
          <p class="price">A partir de R$ 150</p>
        </article>
        <article class="card">
          <h3>Vitrificação de pintura</h3>
          <ul class="list">
            <li>Proteção cerâmica</li>
            <li>Alta durabilidade</li>
            <li>Facilidade de limpeza</li>
          </ul>
          <p class="price">Sob consulta</p>
        </article>
      </div>
    </div>
  </section>

  <section id="sobre" class="section alt">
    <div class="container about">
      <div class="about-text">
        <h2>Gerente — Alex</h2>
        <p>Alex lidera o Lava Car Estilos com mais de 8 anos de experiência em estética automotiva. Ele acredita que cada carro conta uma história e merece atenção aos detalhes.</p>
        <p>Compromisso com prazos, transparência no atendimento e resultados que fazem você sorrir ao ver seu carro pronto.</p>
        <ul class="list">
          <li><strong>Especialidades:</strong> proteção cerâmica, correção de pintura, higienização premium</li>
          <li><strong>Atendimento:</strong> Borda da Mata e região</li>
        </ul>
      </div>
      <div class="about-photo">
        <div class="photo-placeholder">Foto do Alex</div>
      </div>
    </div>
  </section>

  <section id="galeria" class="section">
    <div class="container">
      <h2>Galeria</h2>
      <p>Alguns resultados dos nossos serviços.</p>
      <div class="grid gallery">
        <figure class="gallery-item">
          <div class="img-placeholder">Antes</div>
          <figcaption>Antes da higienização</figcaption>
        </figure>
        <figure class="gallery-item">
          <div class="img-placeholder">Depois</div>
          <figcaption>Depois da higienização</figcaption>
        </figure>
        
        <figure class="gallery-item">
          <div class="img-placeholder">Brilho</div>
          <figcaption>Enceramento premium</figcaption>
        </figure>
        <figure class="gallery-item">
          <div class="img-placeholder">Rodas</div>
          <figcaption>Detalhamento de rodas</figcaption>
        </figure>
        <figure class="gallery-item">
          <div class="img-placeholder">Interior</div>
          <figcaption>Acabamento interno</figcaption>
        </figure>
        <figure class="gallery-item">
          <div class="img-placeholder">Proteção</div>
          <figcaption>Vitrificação cerâmica</figcaption>
        </figure>
      </div>
    </div>
  </section>

  <section id="contato" class="section alt">
    <div class="container">
      <h2>Contato e agendamento</h2>
      <p>Preencha o formulário para solicitar um horário. Retornaremos para confirmar.</p>
      <form id="agendamentoForm" class="form">
        <div class="form-row">
          <label for="nome">Nome</label>
          <input type="text" id="nome" name="nome" placeholder="Seu nome" required />
        </div>
        <div class="form-row">
          <label for="telefone">Telefone/WhatsApp</label>
          <input type="tel" id="telefone" name="telefone" placeholder="(xx) xxxxx-xxxx" required />
        </div>
        <div class="form-row">
          <label for="email">E-mail</label>
          <input type="email" id="email" name="email" placeholder="seuemail@exemplo.com" />
        </div>
        <div class="form-row">
          <label for="servico">Serviço desejado</label>
          <select id="servico" name="servico" required>
            <option value="">Selecione</option>
            <option>Lavagem completa</option>
            <option>Higienização interna</option>
            <option>Enceramento e proteção</option>
            <option>Vitrificação de pintura</option>
          </select>
        </div>
        <div class="form-row">
          <label for="data">Data preferencial</label>
          <input type="date" id="data" name="data" required />
        </div>
        <div class="form-row">
          <label for="observacoes">Observações</label>
          <textarea id="observacoes" name="observacoes" rows="4" placeholder="Detalhes do veículo, horário preferido, etc."></textarea>
        </div>
        <div class="form-actions">
          <button type="submit" class="btn btn-primary">Enviar pedido</button>
          <span id="formStatus" class="form-status" aria-live="polite"></span>
        </div>
      </form>

      <div class="contact-info">
        <h3>Informações</h3>
        <ul class="list">
          <li><strong>Endereço:</strong> Borda da Mata, MG</li>
          <li><strong>Horário:</strong> Seg–Sáb, 8h–18h</li>
          <li><strong>Gerente:</strong> Alex</li>
        </ul>
      </div>
    </div>
  </section>

  <footer class="footer">
    <div class="container footer-grid">
      <div>
        <strong>Lava Car Estilos</strong>
        <p>Estética automotiva com atenção aos detalhes.</p>
      </div>
      <div>
        <strong>Contato</strong>
        <p>WhatsApp: (35)99104-5222</p>
        <p>E-mail: contato@lavacarestilos.com</p>
      </div>
      <div>
        <strong>Redes</strong>
        <p><a href="#" aria-label="Instagram">Instagram</a> · <a href="#" aria-label="Facebook">Facebook</a></p>
      </div>
    </div>
    <div class="container footer-bottom">
      <small>© 2026 Lava Car Estilos — Gerente Alex</small>
    </div>
  </footer>

  <button class="whatsapp-fab" aria-label="Abrir WhatsApp">
    💬
  </button>

  <script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Site Verde</title>
  <style>
    body {
      background-color: green; /* muda o fundo para verde */
      color: white;            /* texto em branco para contraste */
      font-family: Arial, sans-serif;
    }
  </style>
</head>
<body>
  <h1>Bem-vindo ao Lava Carros</h1>
  <p>Agora o fundo do site está verde!</p>
</body>
</html>
 
 
