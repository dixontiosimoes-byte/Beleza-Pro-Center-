<!doctype html>
<html lang="pt">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Guia Prático da Gastrite — Apenas 69 MT</title>

  <!-- Open Graph / Twitter -->
  <meta property="og:title" content="Guia Prático da Gastrite — Apenas 69 MT" />
  <meta property="og:description" content="Guia simples e adaptado a Moçambique para controlar a gastrite: alimentos, hábitos e alívio rápido." />
  <meta property="og:image" content="https://source.unsplash.com/1200x630/?stomach,health" />
  <meta property="og:type" content="website" />
  <meta name="twitter:card" content="summary_large_image" />

  <!-- Structured data (Product/Offer) -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Product",
    "name": "Guia Prático da Gastrite",
    "description": "Guia simples e adaptado à realidade de Moçambique para controlar a gastrite: alimentos, hábitos e alívio rápido.",
    "offers": {
      "@type": "Offer",
      "priceCurrency": "MZN",
      "price": "69",
      "url": "https://wa.me/258835127096"
    }
  }
  </script>

  <style>
    :root{
      --bg:#f4f6f9;
      --card:#ffffff;
      --accent:#2bb673;
      --accent-2:#0066cc;
      --muted:#6b7280;
      --dark:#071024;
      --radius:14px;
      --maxw:1100px;
      --container-pad:20px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;
      background:var(--bg);
      color:var(--dark);
      -webkit-font-smoothing:antialiased;
      line-height:1.45;
    }
    .wrap{max-width:var(--maxw);margin:28px auto;padding:var(--container-pad)}
    .card{
      background:var(--card);
      border-radius:var(--radius);
      padding:18px;
      box-shadow:0 14px 40px rgba(9,18,28,0.06);
      overflow:hidden;
    }

    .grid{
      display:grid;
      grid-template-columns: 1fr 380px;
      gap:22px;
      align-items:start;
    }

    /* LEFT: hero + copy */
    .hero{
      border-radius:12px;
      overflow:hidden;
      position:relative;
      height:360px;
    }
    .hero img{width:100%;height:100%;object-fit:cover;display:block}
    .badge{
      position:absolute;left:16px;top:16px;
      background:rgba(0,0,0,0.6);color:#fff;padding:8px 12px;border-radius:999px;font-weight:700;font-size:13px;
    }

    header h1{
      font-size:26px;
      margin:14px 0 6px 0;
      line-height:1.06;
      letter-spacing:-0.2px;
    }
    header p.lead{
      color:var(--muted);
      margin:0 0 14px 0;
      font-size:16px;
    }

    .meta{display:flex;gap:10px;flex-wrap:wrap;margin-top:8px}
    .pill{background:#eef6ff;padding:8px 10px;border-radius:999px;font-weight:700;color:#0b4ea2;font-size:13px}

    .benefits{display:grid;grid-template-columns:repeat(2,1fr);gap:10px;margin-top:16px}
    .benef{
      display:flex;gap:12px;align-items:flex-start;background:#fbfdff;padding:12px;border-radius:10px;border:1px solid rgba(10,20,40,0.03)
    }
    .dot{width:10px;height:10px;border-radius:50%;background:var(--accent);margin-top:6px}
    .benef p{margin:0;font-size:14px;color:var(--dark)}

    /* Right: price card */
    .price-card{
      background:linear-gradient(180deg,#ffffff,#f8fbff);
      border-radius:12px;padding:20px;border:1px solid rgba(10,20,40,0.04);
      text-align:center;
      position:sticky;top:20px;
    }
    .label{font-weight:700;color:var(--muted);font-size:13px}
    .price{
      font-size:44px;font-weight:900;color:var(--accent-2);margin:6px 0 4px 0;
    }
    .price small{display:block;font-size:14px;color:var(--muted);font-weight:600;margin-top:6px}

    .cta{
      display:inline-flex;align-items:center;gap:10px;justify-content:center;
      margin-top:14px;text-decoration:none;background:var(--accent-2);
      color:#fff;padding:12px 16px;border-radius:10px;font-weight:800;
      box-shadow:0 10px 30px rgba(0,102,204,0.12);
    }
    .cta svg{width:18px;height:18px;flex:0 0 18px}

    .tiny{font-size:13px;color:var(--muted);margin-top:10px}

    .scarcity{background:#fff7f0;border:1px solid #ffe5cc;padding:10px;border-radius:10px;color:#7a2b00;font-weight:700;margin-top:12px}

    .tests{margin-top:18px}
    .test{display:flex;gap:12px;margin:12px 0;padding:12px;border-radius:10px;background:#fbfdff;border:1px solid rgba(10,20,40,0.03)}
    .test img{width:56px;height:56px;border-radius:999px;object-fit:cover}
    .test p{margin:0;font-size:14px;color:#111}

    details{margin:10px 0;padding:12px;border-radius:8px;background:#fbfbfb;border:1px solid rgba(11,18,24,0.03)}
    summary{font-weight:700;cursor:pointer;font-size:15px}

    .footer{font-size:13px;color:var(--muted);text-align:center;margin-top:18px}

    /* mobile / responsive */
    @media (max-width:900px){
      .grid{grid-template-columns:1fr;gap:16px}
      .price-card{position:relative;top:0}
      .benefits{grid-template-columns:1fr}
      .hero{height:260px}
    }

    /* sticky bottom CTA for mobile */
    .bottom-cta{
      display:none;
      position:fixed;left:12px;right:12px;bottom:12px;background:linear-gradient(90deg,var(--accent-2),#2b9cd9);
      color:#fff;padding:12px;border-radius:12px;box-shadow:0 20px 40px rgba(8,20,40,0.12);z-index:60;
      justify-content:space-between;align-items:center;gap:12px;
    }
    .bottom-cta .btn{font-weight:800;text-decoration:none;color:#fff;padding:10px 14px;border-radius:8px;background:rgba(255,255,255,0.06)}
    .timer{font-weight:800;font-size:14px}
    @media (max-width:740px){ .bottom-cta{display:flex} }
  </style>
</head>
<body>
  <main class="wrap" aria-labelledby="page-title">
    <div class="card" role="main">
      <div class="grid">
        <!-- LEFT: HERO + COPY -->
        <div>
          <div class="hero" aria-hidden="false">
            <span class="badge">Promoção local • Moçambique</span>
            <!-- clean/simples imagens via Unsplash; substitua por imagem fixa se preferir -->
            <img src="https://source.unsplash.com/1400x900/?stomach,health,food" alt="Pessoa tocando a região do estômago, simbolizando desconforto e alívio">
          </div>

          <header style="margin-top:12px">
            <h1 id="page-title">Guia Prático da Gastrite — Alívio real em passos simples</h1>
            <p class="lead">Um guia direto, adaptado à vida em Moçambique. Dicas práticas, alimentos locais que ajudam, e técnicas para reduzir a dor — tudo por apenas 69 MT.</p>
          </header>

          <div class="meta" aria-hidden="true">
            <div class="pill">Leitura rápida • Fácil de aplicar</div>
            <div class="pill">Suporte via WhatsApp</div>
            <div class="pill">Pagamento local (M-Pesa, transferência)</div>
          </div>

          <div style="margin-top:16px">
            <h2 style="font-size:18px;margin-bottom:8px">O que você vai aprender</h2>
            <div class="benefits" role="list">
              <div class="benef" role="listitem">
                <div class="dot" aria-hidden="true"></div>
                <p><strong>Alimentos que ajudam</strong><br>Opções locais, baratas e fáceis de encontrar.</p>
              </div>
              <div class="benef" role="listitem">
                <div class="dot" aria-hidden="true"></div>
                <p><strong>O que evitar</strong><br>Gatilhos comuns para reduzir crises.</p>
              </div>
              <div class="benef" role="listitem">
                <div class="dot" aria-hidden="true"></div>
                <p><strong>Alívio rápido</strong><br>Técnicas simples para reduzir queimação e dor.</p>
              </div>
              <div class="benef" role="listitem">
                <div class="dot" aria-hidden="true"></div>
                <p><strong>Hábitos locais</strong><br>Dicas adaptadas aos costumes e alimentos moçambicanos.</p>
              </div>
            </div>
          </div>

          <!-- Testimonials -->
          <section class="tests" aria-labelledby="testimonials-title" style="margin-top:18px">
            <h2 id="testimonials-title" style="font-size:18px;margin-bottom:10px">O que dizem outras pessoas</h2>

            <div class="test" aria-live="polite">
              <img src="https://source.unsplash.com/120x120/?woman,smile" alt="Foto de Anabela, leitora">
              <div>
                <p><strong>Anabela, Maputo</strong></p>
                <p>"Em poucos dias a queimação diminuiu. Usei as dicas de alimentação e resultou. Atendimento rápido pelo WhatsApp."</p>
              </div>
            </div>

            <div class="test" aria-live="polite">
              <img src="https://source.unsplash.com/120x120/?man,smile" alt="Foto de João, leitor">
              <div>
                <p><strong>João, Beira</strong></p>
                <p>"Conteúdo prático. Dá para aplicar já com o que temos em casa. Recomendo!"</p>
              </div>
            </div>
          </section>

          <!-- FAQ -->
          <section style="margin-top:18px" aria-labelledby="faq-title">
            <h2 id="faq-title" style="font-size:18px;margin-bottom:8px">Perguntas frequentes</h2>

            <details>
              <summary>Como recebo o guia após pagar?</summary>
              <div style="margin-top:8px">Combinamos o pagamento pelo WhatsApp (M-Pesa, transferência ou outro método local). Assim que confirmado, enviamos o PDF pelo chat.</div>
            </details>

            <details>
              <summary>Posso tirar dúvidas depois de comprar?</summary>
              <div style="margin-top:8px">Sim — suporte por WhatsApp incluído para ajudar a aplicar as recomendações.</div>
            </details>

            <details>
              <summary>O guia substitui consulta médica?</summary>
              <div style="margin-top:8px">Não. O guia oferece orientações práticas, mas em casos graves procure atendimento médico.</div>
            </details>
          </section>

          <div class="footer" style="margin-top:18px">
            © Guia Prático da Gastrite — Conteúdo informativo (não substitui consulta médica)
          </div>
        </div>

        <!-- RIGHT: PRICE + CTA -->
        <aside class="price-card" aria-labelledby="price-title">
          <div class="label" id="price-title">Preço especial</div>
          <div class="price">69 MT</div>
          <div class="tiny">Oferta por tempo limitado</div>

          <div class="scarcity" id="countdown" role="status" aria-live="polite" style="margin-top:12px;font-size:15px">
            Oferta termina em: <strong id="timer">Carregando...</strong>
          </div>

          <!-- WhatsApp CTA -->
          <a
            href="https://wa.me/258835127096?text=Ol%C3%A1%21%20Quero%20comprar%20o%20Guia%20Pr%C3%A1tico%20da%20Gastrite%20(69%20MT).%20Meu%20nome%3A%20%5Bseu%20nome%5D%20%E2%80%94%20Moro%20em%20%5Bcidade%5D.%20Como%20posso%20efectuar%20o%20pagamento%3F"
            class="cta"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="Comprar o Guia por WhatsApp — 69 MT"
          >
            <!-- WhatsApp icon -->
            <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
              <path fill="#fff" d="M20.52 3.48A11.93 11.93 0 0012 .5 11.94 11.94 0 003.48 12c0 2.11.55 4.16 1.6 5.98L3 21l2.56-1.3A11.93 11.93 0 0012 23.5c6.62 0 11.94-5.32 11.94-11.94 0-3.19-1.24-6.18-3.42-8.08z"/>
              <path d="M16.22 13.12c-.28-.14-1.66-.82-1.92-.91-.26-.09-.45-.13-.64.14-.19.28-.74.91-.91 1.1-.17.19-.35.21-.63.07-.28-.14-1.17-.43-2.23-1.37-.82-.73-1.37-1.64-1.53-1.92-.16-.28-.02-.43.12-.57.12-.12.28-.32.42-.48.14-.16.18-.28.28-.47.09-.19.05-.36-.02-.51-.07-.15-.64-1.53-.88-2.1-.23-.55-.47-.48-.64-.49l-.55-.01c-.19 0-.5.07-.77.36-.26.29-1 1-1 2.44 0 1.43 1.03 2.81 1.17 3.01.14.19 2.03 3.11 4.92 4.35 0 0 .27.12.5.06.23-.06 1.66-.68 1.9-1.34.24-.66.24-1.22.17-1.34-.07-.12-.25-.19-.53-.33z" fill="#fff"/>
            </svg>
            <span>Comprar por 69 MT — WhatsApp</span>
          </a>

          <div class="tiny">Ao clicar abre o WhatsApp com mensagem pronta. Combinamos o pagamento e enviamos o guia em PDF.</div>

          <div style="margin-top:14px;text-align:left">
            <strong style="font-size:13px">O que está incluído</strong>
            <ul style="padding-left:18px;margin:8px 0 0 0;color:#111">
              <li>Guia em PDF — passo a passo</li>
              <li>Lista de alimentos e planos simples</li>
              <li>Suporte por WhatsApp para dúvidas</li>
            </ul>
          </div>
        </aside>
      </div>
    </div>
  </main>

  <!-- Bottom sticky CTA (mobile) -->
  <div class="bottom-cta" role="dialog" aria-live="polite" aria-label="Chamar no WhatsApp">
    <div style="display:flex;gap:10px;align-items:center">
      <div style="font-size:13px">Guia por <strong style="font-size:16px">69 MT</strong></div>
      <div class="timer" id="bottom-timer" aria-hidden="true"></div>
    </div>
    <a href="https://wa.me/258835127096?text=Ol%C3%A1%21%20Quero%20comprar%20o%20Guia%20Pr%C3%A1tico%20da%20Gastrite%20(69%20MT).%20Meu%20nome%3A%20%5Bseu%20nome%5D%20%E2%80%94%20Moro%20em%20%5Bcidade%5D.%20Como%20posso%20efectuar%20o%20pagamento%3F" class="btn" style="text-decoration:none;color:#fff;font-weight:800">Comprar</a>
  </div>

  <script>
    // Countdown: offer expires in 48 hours from first visit (client-side)
    (function(){
      const key = 'gv_gastrite_offer_deadline_v1';
      let deadline = localStorage.getItem(key);
      if (!deadline) {
        deadline = Date.now() + 48 * 60 * 60 * 1000;
        localStorage.setItem(key, deadline);
      } else {
        deadline = parseInt(deadline, 10);
      }

      function updateTimer() {
        const now = Date.now();
        let diff = Math.max(0, deadline - now);

        const days = Math.floor(diff / (24*60*60*1000));
        diff -= days * 24*60*60*1000;
        const hours = Math.floor(diff / (60*60*1000));
        diff -= hours * 60*60*1000;
        const mins = Math.floor(diff / (60*1000));
        diff -= mins * 60*1000;
        const secs = Math.floor(diff / 1000);

        const parts = [];
        if (days > 0) parts.push(days + 'd');
        parts.push(String(hours).padStart(2,'0') + 'h');
        parts.push(String(mins).padStart(2,'0') + 'm');
        parts.push(String(secs).padStart(2,'0') + 's');

        const text = parts.join(' ');
        const el = document.getElementById('timer');
        const el2 = document.getElementById('bottom-timer');
        if (el) el.textContent = text;
        if (el2) el2.textContent = text;

        if (deadline - now <= 0) {
          const scarcity = document.getElementById('countdown');
          if (scarcity) scarcity.textContent = 'Promoção terminada — preço pode aumentar';
          clearInterval(intervalId);
        }
      }

      updateTimer();
      const intervalId = setInterval(updateTimer, 1000);
    })();

    // Simple visibility for bottom CTA on scroll (mobile)
    (function(){
      const bottom = document.querySelector('.bottom-cta');
      if (!bottom) return;
      function check(){
        if (window.innerWidth <= 740) {
          bottom.style.display = 'flex';
        } else {
          bottom.style.display = 'none';
        }
      }
      check();
      window.addEventListener('resize', check);
    })();
  </script>
</body>
</html>
