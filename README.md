<html lang="pt-br">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Vivência de Meditação & Respiração Terapêutica</title>
  <meta name="description" content="Uma vivência prática para reduzir estresse, acalmar a mente e reconectar com a presença — conduzida por Evandro & Alinne." />
  <meta property="og:title" content="Vivência de Meditação & Respiração Terapêutica" />
  <meta property="og:description" content="Respiração consciente, meditação guiada e relaxamento profundo para leveza e clareza." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=Meditacao+%26+Respiracao+Terapeutica" />
  <meta name="twitter:card" content="summary_large_image" />

  <style>
    :root{
      --rose:#C9376E;
      --rose-2:#FCE9F0;
      --blue:#3AAFA9;
      --blue-2:#E6F9F8;
      --ink:#0F172A;
      --soft:#667085;
      --line:#E9EEF5;
      --bg:#FFFFFF;
      --success:#10B981;
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--ink);
      font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,"Helvetica Neue",Arial}
    img{max-width:100%;display:block}
    a{text-decoration:none}

    /* Barra topo */
    .top-bar{
      background:var(--rose); color:#fff; text-align:center;
      padding:14px 10px; font-weight:900; letter-spacing:.04em;
      font-size:clamp(18px,4.4vw,26px); text-transform:uppercase;
    }

    .wrap{max-width:1100px;margin:0 auto}
    section{padding:56px 20px;border-bottom:1px solid var(--line)}
    .grid{display:grid;gap:24px}
    .two{grid-template-columns:1fr}
    @media(min-width:900px){.two{grid-template-columns:1fr 1fr}}

    /* Hero */
    .hero{padding:32px 20px}
    .hero-card{
      background:#fff;border:1px solid var(--line);border-radius:22px;
      padding:28px;max-width:980px;margin:0 auto;text-align:center;
      box-shadow:0 14px 34px rgba(0,0,0,.06)
    }
    .divider{height:10px;margin:22px auto;max-width:320px;border-radius:999px;
      background:linear-gradient(90deg,var(--rose),var(--blue))}
    .lead{color:var(--soft);font-size:18px;max-width:820px;margin:10px auto}

    /* Títulos */
    .section-title{
      font-size:clamp(28px,4.2vw,42px);font-weight:900;margin:0 0 18px;
      background:linear-gradient(90deg,var(--rose),var(--rose));
      -webkit-background-clip:text;background-clip:text;color:transparent;text-align:center;
    }
    .grad-left{
      font-size:clamp(26px,4vw,34px);margin:0 0 12px;font-weight:900;
      background:linear-gradient(90deg,var(--rose),var(--rose));
      -webkit-background-clip:text;background-clip:text;color:transparent;text-align:left;
    }
    p{margin:8px 0 0;font-size:18px;color:var(--soft)}
    ul{margin:8px 0 0 18px;color:var(--soft);font-size:18px}
    li{margin:8px 0}
    .list-check li{list-style:none;padding-left:28px;position:relative}
    .list-check li:before{content:"✓";position:absolute;left:0;top:0;color:var(--success);font-weight:900}

    /* Tarja rosa */
    .tag{
      display:inline-block;background:var(--rose);color:#fff;
      font-weight:900;letter-spacing:.06em;text-transform:uppercase;
      border-radius:12px;padding:10px 14px;font-size:clamp(14px,2.4vw,16px);
    }

    /* Cards */
    .card{background:#fff;border:1px solid var(--line);border-radius:18px;padding:24px;box-shadow:0 10px 28px rgba(31,35,48,.05)}
    .pink{background:var(--rose-2)}
    .blue{background:var(--blue-2)}

    /* CTA */
    .cta{display:flex;gap:12px;justify-content:center;flex-wrap:wrap;margin-top:12px}
    .btn{display:inline-block;padding:14px 20px;border-radius:14px;font-weight:900;box-shadow:0 8px 18px rgba(0,0,0,.08)}
    .primary{background:var(--rose);color:#fff}
    .ghost{background:#fff;border:2px solid var(--blue);color:var(--blue)}
    .primary:hover{filter:brightness(1.05)}
    .ghost:hover{background:var(--blue);color:#fff}

    /* Instrutores */
    .instrutores-grid{display:grid;gap:22px;grid-template-columns:1fr}
    @media(min-width:800px){.instrutores-grid{grid-template-columns:1fr 1fr}}
    .inst-card{background:#fff;border:1px solid var(--line);border-radius:16px;padding:18px;box-shadow:0 10px 26px rgba(0,0,0,.06);text-align:center}
    .inst-name{margin:10px 0 4px;font-weight:900;color:var(--ink);font-size:18px}
    .inst-role{margin:0;color:var(--soft);font-size:14px}
    .avatar-wrap{width:160px;height:160px;margin:8px auto 12px;display:grid;place-items:center;border-radius:50%;
      background:conic-gradient(from 200deg,#f6d,#ff9a9e,#fecfef,#f6d);}
    .avatar-ring{width:144px;height:144px;border-radius:50%;background:#fff;display:grid;place-items:center}
    .avatar{width:132px;height:132px;border-radius:50%;object-fit:cover;display:block}
    .inst-list{margin:10px auto 0;max-width:520px;text-align:left;color:var(--soft);font-size:15px;line-height:1.55}
    .inst-list li{margin:6px 0}
    .inst-note{margin-top:10px;font-size:14px;color:#64748b;text-align:center}

    /* Preço */
    .price-card{text-align:center;padding:24px;border:1px solid var(--line);border-radius:18px;box-shadow:0 10px 28px rgba(0,0,0,.05);max-width:360px;margin:0 auto}
    .price{font-size:44px;font-weight:900;color:var(--rose);margin:10px 0}

    /* Depoimentos */
    .testimonials{display:grid;gap:18px}
    @media(min-width:900px){.testimonials{grid-template-columns:1fr 1fr}}
    .t-card{border:1px solid var(--line);border-radius:16px;padding:16px 18px;box-shadow:0 8px 22px rgba(0,0,0,.05);background:#fff}
    .t-name{font-weight:900;margin:0 0 6px;font-size:16px;color:#0f172a}

    /* FAQ */
    .faq{max-width:980px;margin:0 auto}
    .faq-item{margin:12px 0;border-radius:14px;overflow:hidden;box-shadow:0 6px 18px rgba(0,0,0,.06);border:1px solid var(--line)}
    .faq-q{width:100%;text-align:left;background:var(--rose);border:0;padding:16px 18px;font-size:18px;font-weight:900;color:#fff;cursor:pointer;display:flex;justify-content:space-between;align-items:center}
    .faq-q .mark{font-weight:900;color:#fff}
    .faq-a{max-height:0;overflow:hidden;transition:max-height .28s ease;background:#5cc3be;color:#fff}
    .faq-a-inner{padding:16px 18px;font-size:16px;line-height:1.55}
    .faq-item.open .faq-a{max-height:360px}
    .faq-item.open .faq-q .mark{opacity:.9}

    /* CTA final + rodapé */
    .footer-cta{background:var(--blue-2);border:1px solid #dbeafe;border-radius:16px;padding:26px;display:flex;gap:16px;flex-wrap:wrap;align-items:center;justify-content:space-between}
    footer{padding:28px 0;background:var(--rose);color:#fff;font-size:14px;text-align:center}

    /* WhatsApp flutuante */
    .whats-float{
      position:fixed; right:22px; bottom:18px; z-index:1000;
      width:60px; height:60px; border-radius:50%;
      background:#25D366; box-shadow:0 12px 28px rgba(0,0,0,.18);
      display:flex; align-items:center; justify-content:center;
    }
    .whats-float svg{width:30px;height:30px;fill:#fff}
  </style>
</head>
<body>

  <!-- Topo -->
  <div class="top-bar">Vivência de Meditação & Respiração Terapêutica</div>

  <!-- Hero -->
  <div class="hero">
    <div class="wrap">
      <div class="hero-card">
        <h1 style="margin:0;font-size:clamp(32px,5vw,48px)">Respire fundo. Viva leve.</h1>
        <p class="lead">Respiração consciente, meditação guiada e relaxamento profundo para reduzir estresse, organizar os pensamentos e cultivar presença no dia a dia.</p>
        <div class="divider" aria-hidden="true"></div>
        <div class="cta">
          <a href="#inscricao" class="btn primary">Quero participar</a>
          <a href="https://wa.me/5549998110445?text=Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20de%20Medita%C3%A7%C3%A3o%20%26%20Respira%C3%A7%C3%A3o" class="btn ghost" target="_blank" rel="noopener">Falar no WhatsApp</a>
        </div>
      </div>
    </div>
  </div>

  <!-- O que é / Benefícios -->
  <section>
    <div class="wrap">
      <div class="grid two">
        <div class="card pink">
          <span class="tag">O que é</span>
          <h2 class="grad-left">Vivência terapêutica</h2>
          <p>Integra técnicas de respiração, meditação e atenção plena para desacelerar, aliviar tensões e abrir espaço para clareza emocional.</p>
        </div>
        <div class="card blue">
          <span class="tag">Benefícios</span>
          <h2 class="grad-left">Resultados que você sente</h2>
          <ul class="list-check">
            <li>Redução do estresse e da ansiedade</li>
            <li>Melhora do sono e do foco</li>
            <li>Regulação emocional e paz interna</li>
            <li>Consciência corporal e energia estável</li>
            <li>Mais presença, fé e confiança na vida</li>
            <li>Ferramentas simples para o dia a dia</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Para quem é / Como funciona -->
  <section>
    <div class="wrap">
      <div class="grid two">
        <div class="card">
          <span class="tag">Para quem é</span>
          <h2 class="grad-left">Aberta a todos os níveis</h2>
          <ul class="list-check">
            <li>Pessoas em busca de leveza e organização mental</li>
            <li>Quem vive “no 360” e precisa desacelerar</li>
            <li>Iniciantes e praticantes — sem pré-requisitos</li>
          </ul>
        </div>
        <div class="card">
          <span class="tag">Como funciona</span>
          <h2 class="grad-left">Encontro presencial em grupo</h2>
          <p>Práticas conduzidas, pausas conscientes e orientações para aplicar no cotidiano.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Instrutores -->
  <section>
    <div class="wrap">
      <span class="tag">Instrutores</span>
      <h2 class="section-title" style="margin-top:10px">Evandro &amp; Alinne</h2>
      <div class="instrutores-grid">
        <!-- Evandro -->
        <figure class="inst-card" role="group" aria-labelledby="evandro-name">
          <div class="avatar-wrap"><div class="avatar-ring">
            <img class="avatar" src="Da Evandro (2).jpg" alt="Evandro — foto de perfil redonda">
          </div></div>
          <figcaption>
            <div id="evandro-name" class="inst-name">Evandro</div>
            <p class="inst-role">Facilitador • Respiração & Meditação</p>
            <ul class="inst-list">
              <li>Formação em Respiração Consciente (Breathwork)</li>
              <li>Constelação Familiar & Sistêmica</li>
              <li>Inteligência Emocional e Comunicação Não Violenta</li>
              <li>Condução de grupos e vivências</li>
            </ul>
          </figcaption>
        </figure>
        <!-- Alinne -->
        <figure class="inst-card" role="group" aria-labelledby="alinne-name">
          <div class="avatar-wrap"><div class="avatar-ring">
            <img class="avatar" src="Da Alinne.jpg" alt="Alinne — foto de perfil redonda">
          </div></div>
          <figcaption>
            <div id="alinne-name" class="inst-name">Alinne</div>
            <p class="inst-role">Facilitadora • Respiração & Presença</p>
            <ul class="inst-list">
              <li>Formação em Meditação Guiada & Mindfulness</li>
              <li>Respiração Terapêutica e Regulação Emocional</li>
              <li>Constelação Sistêmica (atendimento em grupo)</li>
              <li>Experiência em acolhimento e processos de cura</li>
            </ul>
          </figcaption>
        </figure>
      </div>
      <p class="inst-note">Evandro &amp; Alinne conduzem juntos a Vivência de Meditação &amp; Respiração Terapêutica.</p>
    </div>
  </section>

  <!-- Investimento -->
  <section id="inscricao">
    <div class="wrap">
      <div class="price-card">
        <span class="tag" style="font-size:18px;padding:12px 16px;border-radius:14px">Investimento</span>
        <div class="price">R$ 440,00</div>
        <div class="cta" style="margin-top:6px">
          <a href="https://wa.me/5549998110445?text=Quero%20garantir%20minha%20vaga%20na%20Viv%C3%AAncia" class="btn primary" target="_blank" rel="noopener">Garantir minha vaga</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Depoimentos -->
  <section>
    <div class="wrap">
      <span class="tag">Depoimentos Reais</span>
      <h2 class="section-title" style="margin-top:10px">O que as pessoas sentiram</h2>
      <div class="testimonials">
        <div class="t-card"><p class="t-name">Roselei Teles</p><p>“Fomos iluminados pela luz divina e vimos a proteção de Deus na nossa vida. Que paz — gratidão Aline e Evandro.”</p></div>
        <div class="t-card"><p class="t-name">Germano Micheli</p><p>“Meditação e respiração de hoje foi incrível. Cada vez que participo fica melhor — não dá vontade de parar.”</p></div>
        <div class="t-card"><p class="t-name">Alini De Paris</p><p>“Sou grata pela experiência — me trouxe leveza, presença e conexão.”</p></div>
        <div class="t-card"><p class="t-name">Marisa</p><p>“Percebi o quanto é importante dar atenção à respiração e desacelerar. Já estou colocando em prática — tem me ajudado muito.”</p></div>
        <div class="t-card"><p class="t-name">Ivete</p><p>“Aprendi a controlar meus pensamentos. Saí em paz, com leveza e tive uma noite de sono tranquila.”</p></div>
        <div class="t-card"><p class="t-name">Michely</p><p>“Dia maravilhoso de muita aprendizagem. A partir de hoje vou ser outra pessoa. Só agradecimentos.”</p></div>
        <div class="t-card"><p class="t-name">Idalina</p><p>“Saí outra pessoa: leve, tranquila e confiante. A conexão do grupo e a troca de energias foram mágicas.”</p></div>
        <div class="t-card"><p class="t-name">Onira Marolli</p><p>“A vivência me tranquilizou e organizou os pensamentos. Agora é seguir com calma na alma.”</p></div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section>
    <div class="wrap">
      <span class="tag">FAQ</span>
      <h2 class="section-title" style="margin-top:10px">Perguntas Frequentes</h2>
      <div class="faq">
        <div class="faq-item">
          <button class="faq-q" aria-expanded="false"><span>Preciso ter experiência prévia?</span><span class="mark">+</span></button>
          <div class="faq-a" aria-hidden="true"><div class="faq-a-inner">Não. É para todos os níveis — você será guiado passo a passo.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q" aria-expanded="false"><span>O que levar?</span><span class="mark">+</span></button>
          <div class="faq-a" aria-hidden="true"><div class="faq-a-inner">Roupas confortáveis, água e, se quiser, seu tapete/almofada.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q" aria-expanded="false"><span>Duração do encontro</span><span class="mark">+</span></button>
          <div class="faq-a" aria-hidden="true"><div class="faq-a-inner">Imersão de aproximadamente 3 horas.</div></div>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA final -->
  <section style="padding:32px 20px">
    <div class="wrap">
      <div class="footer-cta">
        <div>
          <div style="font-weight:800;color:var(--rose);letter-spacing:.06em;text-transform:uppercase;font-size:12px">Respire diferente</div>
          <h3 style="margin:6px 0 0;font-size:22px;color:var(--ink)">Você no controle da sua presença — um passo de cada vez.</h3>
        </div>
        <a href="https://wa.me/5549998110445?text=Quero%20participar%20da%20Viv%C3%AAncia" class="btn primary" target="_blank" rel="noopener">Inscrever-se agora</a>
      </div>
    </div>
  </section>

  <!-- Rodapé -->
  <footer>© 2025 Vivência de Meditação & Respiração Terapêutica — Todos os direitos reservados.</footer>

  <!-- WhatsApp flutuante -->
  <a class="whats-float" href="https://wa.me/5549998110445?text=Oi!%20Quero%20mais%20informacoes%20da%20Vivencia" target="_blank" rel="noopener" aria-label="Falar no WhatsApp">
    <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Zm-8.4 2.2c4.1 0 7.4 3.3 7.4 7.4a7.4 7.4 0 0 1-10.1 6.8l-.3-.1-2.6.7.7-2.5-.1-.3a7.4 7.4 0 0 1 5-11.9Zm4.2 9.8c-.2.6-1.1 1-1.5 1.1-.4.1-.9.1-1.5 0s-1.5-.5-2.6-1.1c-1-.6-1.8-1.6-2.1-2.1-.3-.5-.5-1.3-.1-1.9.2-.3.5-.8.8-.8h.6c.1 0 .4-.1.6.5.2.6.8 2 .9 2.2.1.2.1.4 0 .6s-.2.4-.4.6c-.2.2-.4.4-.2.7.2.3.9 1.4 2.1 2 .9.5 1.6.6 1.9.4.3-.2.4-.5.6-.8.2-.3.5-.4.8-.3l1.9.9c.3.1.5.3.6.5Z"/></svg>
  </a>

  <!-- FAQ toggle -->
  <script>
    (function(){
      const items = document.querySelectorAll('.faq-item');
      items.forEach((item) => {
        const btn = item.querySelector('.faq-q');
        const panel = item.querySelector('.faq-a');
        btn.addEventListener('click', () => {
          items.forEach(i => {
            if(i !== item){
              i.classList.remove('open');
              i.querySelector('.faq-q').setAttribute('aria-expanded','false');
              i.querySelector('.faq-a').setAttribute('aria-hidden','true');
            }
          });
          const isOpen = item.classList.toggle('open');
          btn.setAttribute('aria-expanded', isOpen ? 'true' : 'false');
          panel.setAttribute('aria-hidden', isOpen ? 'false' : 'true');
        });
      });
    })();
  </script>
</body>
</html>
