<html lang="pt-br">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Vivência de Meditação & Respiração Terapêutica</title>
  <meta name="description" content="Vivência prática para reduzir estresse, acalmar a mente e reconectar com a presença — conduzida por Evandro & Alinne." />
  <meta property="og:title" content="Vivência de Meditação & Respiração Terapêutica" />
  <meta property="og:description" content="Respiração consciente, meditação guiada e relaxamento profundo para leveza e clareza." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://via.placeholder.com/1200x930.png?text=Meditacao+%26+Respiracao+Terapeutica" />
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

    /* Oculta header padrão do tema GitHub Pages */
    header, .page-header, .site-header, .project-name, .project-tagline,
    #header, #banner, .header, .site-title, .site-nav, .masthead,
    body > h1:first-of-type, body > .octicon-link, body > .container-lg > h1 {
      display:none !important;
      visibility:hidden !important;
      height:0 !important; margin:0 !important; padding:0 !important;
    }

    /* Faixa rosa topo (não fixa, rola junto) */
    .top-bar{
      position: relative;
      width:100vw;
      margin-left:calc(50% - 50vw);
      background:var(--rose);
      color:#fff;
      text-align:center;
      padding:22px 10px;
      font-weight:900; letter-spacing:.06em;
      font-size:clamp(20px,4.8vw,30px);
      text-transform:uppercase;
      z-index:1;
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

    /* Tarja rosa de seção */
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

    /* Instrutores (foto redonda com anel) */
    .instrutores-grid{display:grid;gap:22px;grid-template-columns:1fr}
    @media(min-width:800px){.instrutores-grid{grid-template-columns:1fr 1fr}}
    .inst-card{background:#fff;border:1px solid var(--line);border-radius:16px;padding:18px;box-shadow:0 10px 26px rgba(0,0,0,.06);text-align:center}
    .inst-name{margin:10px 0 4px;font-weight:900;color:var(--ink);font-size:18px}
    .inst-role{margin:0;color:var(--soft);font-size:14px}
    .avatar-wrap{width:160px;height:160px;margin:8px auto 12px;display:grid;place-items:center;border-radius:50%;
      background:conic-gradient(from 200deg,#f6d,#ff9a9e,#fecfef,#f6d);}
    .avatar-ring{width:144px;height:144px;border-radius:50%;background:#fff;display:grid;place-items:center}
    .avatar{width:132px;height:132px;border-radius:50%;object-fit:cover;display:block;object-position:center var(--avatar-y,10%)}
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

    footer{padding:28px 0;background:var(--rose);color:#fff;font-size:14px;text-align:center}
  </style>
</head>
<body>

  <!-- Topo -->
  <div class="top-bar">VIVÊNCIA DE MEDITAÇÃO & RESPIRAÇÃO TERAPÊUTICA</div>

  <!-- Hero -->
  <div class="hero">
    <div class="wrap">
      <div class="hero-card">
        <h1 style="margin:0;font-size:clamp(32px,5vw,48px)">Respire fundo. Viva leve.</h1>
        <p class="lead">Respiração consciente, meditação guiada e relaxamento profundo para reduzir estresse, organizar os pensamentos e cultivar presença no dia a dia.</p>
        <div class="divider" aria-hidden="true"></div>
        <div class="cta">
          <a href="#inscricao" class="btn primary">Quero participar</a>
          <a href="https://wa.me/5549998110445?text=Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia" class="btn ghost" target="_blank" rel="noopener">Falar no WhatsApp</a>
        </div>
      </div>
    </div>
  </div>

  <!-- O que é -->
  <section>
    <div class="wrap">
      <span class="tag">O que é</span>
      <h2 class="section-title" style="margin-top:10px">Vivência terapêutica</h2>
      <div class="grid two">
        <div class="card pink">
          <h3 class="grad-left">Integração mente–corpo</h3>
          <p>Respiração, meditação e atenção plena para desacelerar e abrir espaço para clareza emocional.</p>
        </div>
        <div class="card blue">
          <h3 class="grad-left">Aplicável no dia a dia</h3>
          <p>Ferramentas simples que você leva para a rotina: pausas conscientes, presença e autocuidado.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Benefícios -->
  <section>
    <div class="wrap">
      <span class="tag">Benefícios</span>
      <h2 class="section-title" style="margin-top:10px">Resultados que você sente</h2>
      <div class="grid two">
        <div class="card pink">
          <h3 class="grad-left">Menos estresse</h3>
          <p>Reduz ansiedade e tensão física.</p>
        </div>
        <div class="card blue">
          <h3 class="grad-left">Sono melhor</h3>
          <p>Mente mais calma para noites restauradoras.</p>
        </div>
        <div class="card pink">
          <h3 class="grad-left">Clareza e foco</h3>
          <p>Organiza pensamentos e apoia decisões.</p>
        </div>
        <div class="card blue">
          <h3 class="grad-left">Presença</h3>
          <p>Mais conexão consigo e com a vida.</p>
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
        <figure class="inst-card">
          <div class="avatar-wrap"><div class="avatar-ring">
            <img class="avatar" src="evandro.jpg" alt="Evandro — foto de perfil redonda" style="--avatar-y:50%;">
          </div></div>
          <figcaption>
            <div class="inst-name">Evandro</div>
            <p class="inst-role">Facilitador • Respiração & Meditação</p>
          </figcaption>
        </figure>

        <!-- Alinne -->
        <figure class="inst-card">
          <div class="avatar-wrap"><div class="avatar-ring">
            <img class="avatar" src="alinne.jpg" alt="Alinne — foto de perfil redonda" style="--avatar-y:10%;">
          </div></div>
          <figcaption>
            <div class="inst-name">Alinne</div>
            <p class="inst-role">Facilitadora • Respiração & Presença</p>
          </figcaption>
        </figure>
      </div>
    </div>
  </section>

  <!-- Investimento -->
  <section id="inscricao">
    <div class="wrap">
      <div class="price-card">
        <span class="tag" style="font-size:18px;padding:12px 16px;border-radius:14px">Investimento</span>
        <div class="price">R$ 440,00</div>
        <div class="cta" style="margin-top:6px">
          <a href="https://wa.me/5549998110445?text=Quero%20garantir%20minha%20vaga" class="btn primary" target="_blank" rel="noopener">Garantir minha vaga</a>
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
        <div class="t-card"><p class="t-name">Ivete</p><p>“A vivência de ontem foi maravilhosa. Aprendi que preciso controlar meus pensamentos. Saí em paz, com uma leveza que nunca senti; tive uma noite de sono muito tranquila. Estou decidida a mudar.”</p></div>
        <div class="t-card"><p class="t-name">Germano</p><p>“Meditação e respiração de hoje foi incrível; cada vez que participo fica melhor — daí não dá vontade de parar kkkk.”</p></div>
        <div class="t-card"><p class="t-name">Aline</p><p>“Hoje foi muito bom. Sou grata pela experiência, pois me trouxe leveza, presença e conexão.”</p></div>
        <div class="t-card"><p class="t-name">Marisa</p><p>“Percebi o quanto é importante dar atenção ao pensamento e à respiração, desacelerar. O que aprendemos já está me ajudando no dia a dia.”</p></div>
        <div class="t-card"><p class="t-name">Michely</p><p>“Um dia maravilhoso de muito aprendizado. A partir de hoje vou ser outra pessoa. Agradeço à Aline, ao Evandro e a todos que estiveram presentes.”</p></div>
        <div class="t-card"><p class="t-name">Idalina</p><p>“Fui com a ideia de ‘meditação normal’. Saí outra Idalina — leve, tranquila e confiante. A troca de energias do grupo é mágica. Estou renovada em paz.”</p></div>
        <div class="t-card"><p class="t-name">Onira</p><p>“A vivência me tranquilizou, organizou os pensamentos. Agora, seguir com calma na alma.”</p></div>
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

  <footer>© 2025 Vivência de Meditação & Respiração Terapêutica — Todos os direitos reservados.</footer>

  <!-- JS FAQ -->
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
