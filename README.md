
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="NEXO Agência Digital: pacotes para Instagram com seguidores, métricas e materiais estratégicos de conteúdo.">
  <title>NEXO Agência Digital | Pacotes para Instagram</title>
  <style>
    :root {
      --bg: #070a11;
      --panel: #101624;
      --panel-2: #0c1220;
      --text: #f5f7fb;
      --muted: #aab4c6;
      --blue: #3478f6;
      --blue-bright: #5ca0ff;
      --line: rgba(255,255,255,.11);
    }
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0; background: radial-gradient(ellipse at top right, rgba(52,120,246,.16), transparent 35%), var(--bg);
      color: var(--text); font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      line-height: 1.6;
    }
    a { color: inherit; text-decoration: none; }
    .wrap { width: min(1120px, calc(100% - 40px)); margin: 0 auto; }
    header { border-bottom: 1px solid var(--line); position: sticky; top: 0; z-index: 10; background: rgba(7,10,17,.88); backdrop-filter: blur(14px); }
    .nav { min-height: 76px; display: flex; align-items: center; justify-content: space-between; gap: 24px; }
    .brand { font-size: 1.45rem; letter-spacing: .16em; font-weight: 900; }
    .brand span { color: var(--blue-bright); }
    nav { display: flex; align-items: center; gap: 26px; color: var(--muted); font-size: .92rem; }
    nav a:hover { color: white; }
    .btn { display: inline-flex; align-items: center; justify-content: center; padding: 12px 18px; border-radius: 10px; background: var(--blue); color: white; font-weight: 750; border: 1px solid transparent; transition: .2s ease; }
    .btn:hover { transform: translateY(-2px); background: #2467e8; }
    .btn.secondary { background: transparent; border-color: var(--line); }
    .hero { padding: 92px 0 76px; }
    .eyebrow { color: var(--blue-bright); font-size: .78rem; font-weight: 800; letter-spacing: .17em; text-transform: uppercase; }
    h1 { font-size: clamp(2.5rem, 6vw, 4.8rem); line-height: 1.04; letter-spacing: -.045em; max-width: 850px; margin: 18px 0; }
    h1 em { color: var(--blue-bright); font-style: normal; }
    .hero p { color: var(--muted); max-width: 680px; font-size: 1.1rem; }
    .hero-actions { display: flex; gap: 12px; flex-wrap: wrap; margin-top: 28px; }
    .proof { display: flex; flex-wrap: wrap; gap: 20px; color: var(--muted); margin-top: 36px; font-size: .9rem; }
    .proof span::before { content: "✓"; color: var(--blue-bright); font-weight: 900; margin-right: 8px; }
    section { padding: 68px 0; }
    .section-head { max-width: 720px; margin-bottom: 30px; }
    h2 { font-size: clamp(1.9rem, 4vw, 3rem); line-height: 1.12; letter-spacing: -.03em; margin: 10px 0 14px; }
    .section-head p, .muted { color: var(--muted); }
    .packages { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 18px; }
    .tier { border: 1px solid var(--line); border-radius: 18px; overflow: hidden; background: var(--panel-2); }
    .tier-head { padding: 22px 22px 18px; border-bottom: 1px solid var(--line); background: linear-gradient(140deg, rgba(52,120,246,.13), transparent 75%); }
    .tier-label { font-size: .76rem; letter-spacing: .13em; text-transform: uppercase; color: var(--blue-bright); font-weight: 850; }
    .tier h3 { margin: 7px 0 4px; font-size: 1.45rem; }
    .tier-head p { color: var(--muted); margin: 0; font-size: .92rem; }
    .package { padding: 22px; border-bottom: 1px solid var(--line); }
    .package:last-child { border-bottom: 0; }
    .package h4 { margin: 0 0 8px; font-size: 1.08rem; }
    .price { font-size: 1.25rem; font-weight: 850; margin: 8px 0 16px; }
    .price small { display: block; color: var(--muted); font-size: .76rem; font-weight: 500; }
    ul.features { list-style: none; padding: 0; margin: 0 0 18px; }
    ul.features li { color: #d8deea; font-size: .88rem; margin: 7px 0; }
    ul.features li::before { content: "✓"; color: var(--blue-bright); font-weight: 900; margin-right: 9px; }
    .package .btn { width: 100%; font-size: .9rem; padding: 10px 14px; }
    .note { font-size: .82rem; color: var(--muted); margin-top: 18px; }
    .included { display: grid; grid-template-columns: repeat(3, minmax(0,1fr)); gap: 16px; }
    .feature-card { background: var(--panel); border: 1px solid var(--line); padding: 22px; border-radius: 15px; }
    .feature-card .num { color: var(--blue-bright); font-weight: 900; font-size: .82rem; letter-spacing: .12em; }
    .feature-card h3 { margin: 10px 0 7px; }
    .feature-card p { margin: 0; color: var(--muted); font-size: .94rem; }
    .cta { background: linear-gradient(120deg, rgba(52,120,246,.19), rgba(52,120,246,.04)); border: 1px solid var(--line); border-radius: 22px; padding: clamp(24px, 5vw, 52px); display: flex; justify-content: space-between; align-items: center; gap: 24px; }
    .cta h2 { max-width: 640px; }
    .cta p { color: var(--muted); max-width: 640px; margin-bottom: 0; }
    footer { border-top: 1px solid var(--line); padding: 28px 0; color: var(--muted); font-size: .84rem; }
    .footer-inner { display: flex; justify-content: space-between; gap: 20px; flex-wrap: wrap; }
    @media (max-width: 900px) {
      .packages { grid-template-columns: repeat(2, minmax(0,1fr)); }
      .included { grid-template-columns: repeat(2, minmax(0,1fr)); }
      nav { gap: 14px; }
    }
    @media (max-width: 620px) {
      .wrap { width: min(100% - 28px, 1120px); }
      .nav { min-height: 68px; }
      nav a:not(.btn) { display: none; }
      .hero { padding: 66px 0 50px; }
      section { padding: 50px 0; }
      .packages, .included { grid-template-columns: 1fr; }
      .cta { align-items: flex-start; flex-direction: column; }
    }
  </style>
</head>
<body>
  <header>
    <div class="wrap nav">
      <a class="brand" href="#inicio" aria-label="NEXO Agência Digital">NE<span>X</span>O</a>
      <nav aria-label="Navegação principal">
        <a href="#pacotes">Pacotes</a>
        <a href="#incluido">O que está incluído</a>
        <a href="#contato" class="btn">Consultar pacote</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero" id="inicio">
      <div class="wrap">
        <div class="eyebrow">NEXO Agência Digital</div>
        <h1>Mais estrutura para a sua presença no <em>Instagram.</em></h1>
        <p>Pacotes que combinam métricas para o Instagram com materiais de conteúdo para ajudar a organizar a sua comunicação. Escolha o nível que faz sentido para o seu projeto.</p>
        <div class="hero-actions">
          <a class="btn" href="#pacotes">Ver pacotes</a>
          <a class="btn secondary" href="#incluido">Conhecer os materiais</a>
        </div>
        <div class="proof">
          <span>Opções para diferentes fases</span>
          <span>Materiais de conteúdo incluídos</span>
          <span>Atendimento sob consulta</span>
        </div>
      </div>
    </section>

    <section id="pacotes">
      <div class="wrap">
        <div class="section-head">
          <div class="eyebrow">Escolha o seu pacote</div>
          <h2>Um ponto de partida para cada objetivo.</h2>
          <p>Os valores abaixo são uma proposta inicial de composição dos pacotes e podem ser ajustados antes da publicação. Preços finais ficam em aberto para preencher manualmente.</p>
        </div>

        <div class="packages">
          <article class="tier">
            <div class="tier-head"><div class="tier-label">Nível 01</div><h3>Básico</h3><p>Para começar com uma estrutura simples.</p></div>
            <div class="package">
              <h4>Básico 500</h4><div class="price">Consultar <small>Preço a definir</small></div>
              <ul class="features"><li>500 seguidores</li><li>100 curtidas</li><li>500 visualizações</li><li>3 posts personalizados</li><li>10 ideias de vídeos</li><li>10 ganchos para conteúdos</li><li>Legendas para os posts</li></ul>
              <a class="btn" href="#contato">Consultar pacote</a>
            </div>
            <div class="package">
              <h4>Básico 1.000</h4><div class="price">Consultar <small>Preço a definir</small></div>
              <ul class="features"><li>1.000 seguidores</li><li>200 curtidas</li><li>1.000 visualizações</li><li>5 posts personalizados</li><li>15 ideias de vídeos</li><li>15 ganchos para conteúdos</li><li>Legendas para os posts</li></ul>
              <a class="btn" href="#contato">Consultar pacote</a>
            </div>
          </article>

          <article class="tier">
            <div class="tier-head"><div class="tier-label">Nível 02</div><h3>Intermediário</h3><p>Mais materiais para manter a consistência.</p></div>
            <div class="package">
              <h4>Intermediário 2.500</h4><div class="price">Consultar <small>Preço a definir</small></div>
              <ul class="features"><li>2.500 seguidores</li><li>500 curtidas</li><li>2.500 visualizações</li><li>8 posts personalizados</li><li>25 ideias de vídeos</li><li>25 ganchos para conteúdos</li><li>Legendas para os posts</li></ul>
              <a class="btn" href="#contato">Consultar pacote</a>
            </div>
            <div class="package">
              <h4>Intermediário 5.000</h4><div class="price">Consultar <small>Preço a definir</small></div>
              <ul class="features"><li>5.000 seguidores</li><li>1.000 curtidas</li><li>5.000 visualizações</li><li>12 posts personalizados</li><li>40 ideias de vídeos</li><li>40 ganchos para conteúdos</li><li>Legendas para os posts</li></ul>
              <a class="btn" href="#contato">Consultar pacote</a>
            </div>
          </article>

          <article class="tier">
            <div class="tier-head"><div class="tier-label">Nível 03</div><h3>Premium</h3><p>Maior volume de materiais para planear.</p></div>
            <div class="package">
              <h4>Premium 10.000</h4><div class="price">Consultar <small>Preço a definir</small></div>
              <ul class="features"><li>10.000 seguidores</li><li>2.000 curtidas</li><li>10.000 visualizações</li><li>15 posts personalizados</li><li>60 ideias de vídeos</li><li>60 ganchos para conteúdos</li><li>Legendas para os posts</li></ul>
              <a class="btn" href="#contato">Consultar pacote</a>
            </div>
            <div class="package">
              <h4>Premium 15.000</h4><div class="price">Consultar <small>Preço a definir</small></div>
              <ul class="features"><li>15.000 seguidores</li><li>3.000 curtidas</li><li>15.000 visualizações</li><li>20 posts personalizados</li><li>100 ideias de vídeos</li><li>100 ganchos para conteúdos</li><li>Legendas para os posts</li></ul>
              <a class="btn" href="#contato">Consultar pacote</a>
            </div>
          </article>
        </div>
        <p class="note">Nota: quantidades apresentadas como proposta inicial. Métricas fornecidas por terceiros podem variar, ser removidas pela plataforma e não garantem alcance, vendas ou crescimento orgânico. Confirme as condições antes de contratar.</p>
      </div>
    </section>

    <section id="incluido">
      <div class="wrap">
        <div class="section-head">
          <div class="eyebrow">Mais do que números</div>
          <h2>Materiais para apoiar o seu conteúdo.</h2>
          <p>Os extras dos pacotes ajudam a dar forma ao conteúdo e a manter uma linha de comunicação mais organizada.</p>
        </div>
        <div class="included">
          <article class="feature-card"><div class="num">01 / CRIAÇÃO</div><h3>Posts personalizados</h3><p>Peças pensadas para o nicho e a identidade do perfil, com legendas para acompanhar as publicações.</p></article>
          <article class="feature-card"><div class="num">02 / PLANEAMENTO</div><h3>Ideias de vídeos</h3><p>Sugestões de temas para facilitar a criação de Reels e outros conteúdos curtos.</p></article>
          <article class="feature-card"><div class="num">03 / ATENÇÃO</div><h3>Ganchos para conteúdos</h3><p>Frases de abertura para captar a atenção e apresentar o tema logo nos primeiros segundos.</p></article>
          <article class="feature-card"><div class="num">04 / ANÁLISE</div><h3>Análise de perfil</h3><p>Observação do perfil para identificar pontos de melhoria na apresentação e na comunicação.</p></article>
          <article class="feature-card"><div class="num">05 / DIREÇÃO</div><h3>Alinhamento editorial</h3><p>Orientação para manter consistência de temas, tom e posicionamento do perfil.</p></article>
          <article class="feature-card"><div class="num">06 / ORGANIZAÇÃO</div><h3>Calendário de postagens</h3><p>Uma base de planeamento para distribuir conteúdos ao longo do tempo.</p></article>
        </div>
      </div>
    </section>

    <section id="contato">
      <div class="wrap">
        <div class="cta">
          <div><div class="eyebrow">Vamos conversar</div><h2>Encontre o pacote adequado ao seu projeto.</h2><p>Adicione aqui o seu número de WhatsApp, link de contacto e preços finais quando estiver tudo definido.</p></div>
          <a class="btn" href="mailto:">Adicionar contacto</a>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="wrap footer-inner">
      <div><strong>NEXO Agência Digital</strong> · Presença digital com direção.</div>
      <div>© <span id="year"></span> NEXO. Todos os direitos reservados.</div>
    </div>
  </footer>
  <script>document.getElementById('year').textContent = new Date().getFullYear();</script>
</body>
</html>
