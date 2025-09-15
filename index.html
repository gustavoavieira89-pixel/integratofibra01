<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Integrato: Análise Competitiva e Rota para Liderança Digital</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.1/dist/chart.umd.min.js"></script>
  <style>
    :root{
      --brand: #6B3CF6; /* roxo Integrato (ajuste se tiver o oficial) */
      --brand-2: #9C7BFF;
      --bg: #0B0C10;
      --surface: #14151C;
      --surface-2:#1B1E27;
      --text: #EAEAF0;
      --muted: #9AA3B2;
      --positive: #22C55E;
      --warning: #F59E0B;
      --danger: #EF4444;
      --accent: #00E6A8;
      --ring: rgba(107,60,246,.4);
      --shadow: 0 10px 30px rgba(0,0,0,.45);
      --radius: 18px;
    }
    *{box-sizing:border-box}
    html,body{height:100%;background:var(--bg);color:var(--text);font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial,sans-serif;}
    a{color:var(--brand)}

    /* App shell */
    .app{display:grid;grid-template-rows:auto 1fr;min-height:100dvh}
    header{
      position:sticky;top:0;z-index:50;background:linear-gradient(180deg,rgba(20,21,28,.9),rgba(20,21,28,.6) 70%,rgba(20,21,28,0));
      backdrop-filter:saturate(1.2) blur(8px);
      border-bottom:1px solid rgba(255,255,255,.06);
    }
    .bar{display:flex;align-items:center;gap:14px;max-width:1200px;margin:0 auto;padding:14px 20px}
    .logo{
      width:28px;height:28px;border-radius:8px;background:conic-gradient(from 220deg at 50% 50%, var(--brand), var(--brand-2), var(--brand));
      box-shadow:0 0 0 3px rgba(107,60,246,.2), inset 0 0 30px rgba(255,255,255,.08);
    }
    .title{font-weight:800;letter-spacing:.2px}
    .spacer{flex:1}
    .btn{
      background:linear-gradient(180deg, var(--brand), #5b2fe0);
      border:1px solid rgba(255,255,255,.12);
      color:#fff;padding:10px 14px;border-radius:12px;font-weight:700;cursor:pointer;
      box-shadow:var(--shadow);transition:transform .1s ease, box-shadow .2s ease;
    }
    .btn:hover{transform:translateY(-1px)}
    .btn-secondary{background:var(--surface-2)}

    /* Slides */
    .deck{max-width:1200px;margin:20px auto 60px;position:relative}
    .slides{scroll-snap-type:y mandatory;height:calc(100dvh - 80px);overflow:auto;border-radius:20px;outline:1px solid rgba(255,255,255,.06)}
    .slide{scroll-snap-align:start;min-height:calc(100dvh - 80px);padding:48px;background:
      radial-gradient(1200px 500px at 90% -10%, rgba(107,60,246,.18), transparent 60%),
      radial-gradient(1200px 500px at -10% 110%, rgba(0,230,168,.10), transparent 60%),
      linear-gradient(180deg, var(--surface), var(--surface));
      display:grid;grid-template-rows:auto 1fr;gap:22px
    }
    .slide h2{font-size:34px;line-height:1.15;margin:0}
    .sub{color:var(--muted)}

    .card{background:linear-gradient(180deg, rgba(255,255,255,.04), rgba(255,255,255,.02));
      border:1px solid rgba(255,255,255,.08);border-radius:var(--radius);padding:22px;box-shadow:var(--shadow)}
    .grid{display:grid;gap:18px}
    .grid.cols-2{grid-template-columns:1fr 1fr}
    .grid.cols-3{grid-template-columns:repeat(3,1fr)}

    .kpi{display:flex;align-items:center;gap:12px}
    .kpi .dot{width:10px;height:10px;border-radius:50%}
    .dot.ok{background:var(--positive)}
    .dot.warn{background:var(--warning)}
    .dot.bad{background:var(--danger)}

    ul.clean{margin:0;padding-left:18px}
    ul.clean li{margin:6px 0}
    .badge{display:inline-flex;align-items:center;gap:8px;padding:6px 10px;border-radius:999px;font-weight:700;font-size:12px;color:#fff;background:rgba(107,60,246,.15);border:1px solid rgba(107,60,246,.35)}

    .progress{position:sticky;top:62px;z-index:40;display:flex;gap:8px;justify-content:center;padding:10px}
    .dotnav{width:10px;height:10px;border-radius:50%;background:rgba(255,255,255,.14);cursor:pointer}
    .dotnav.active{background:var(--brand)}

    footer{position:fixed;inset:auto 0 14px 0;display:flex;justify-content:center;pointer-events:none}
    .footer-inner{pointer-events:auto;display:flex;gap:8px;background:rgba(20,21,28,.7);backdrop-filter:blur(8px);border:1px solid rgba(255,255,255,.07);padding:8px 10px;border-radius:12px}
    .navbtn{width:40px;height:40px;border-radius:10px;background:var(--surface-2);border:1px solid rgba(255,255,255,.1);color:#fff;font-weight:800}

    .table{width:100%;border-collapse:collapse}
    .table th,.table td{padding:10px 12px;border-bottom:1px solid rgba(255,255,255,.06);text-align:left}
    .table th{color:var(--muted);font-weight:600}

    /* Print */
    @media print{
      header, .progress, footer{display:none !important}
      .slides{height:auto;overflow:visible;border:none}
      .slide{min-height:auto;page-break-after:always;padding:28px}
    }
  </style>
</head>
<body>
  <div class="app" id="app">
    <header>
      <div class="bar">
        <div class="logo" aria-label="Logo Integrato"></div>
        <div class="title">Integrato — Análise Competitiva & Rota para Liderança Digital</div>
        <div class="spacer"></div>
        <button class="btn btn-secondary" onclick="window.print()" aria-label="Imprimir/Exportar PDF">Imprimir / PDF</button>
      </div>
      <div class="progress" id="progress"></div>
    </header>

    <main class="deck" aria-live="polite">
      <div class="slides" id="slides" tabindex="0">

        <!-- Slide 1: Capa -->
        <section class="slide" aria-label="Capa">
          <div>
            <h2>Integrato: Análise Competitiva e Rota para Liderança Digital</h2>
            <div class="sub">Executivo — Q3/2025</div>
          </div>
          <div class="grid cols-2">
            <div class="card">
              <h3 style="margin-top:0">Resumo</h3>
              <ul class="clean">
                <li>Integrato domina em <b>reputação</b> (Google Reviews) e <b>orgânico</b> (Instagram).</li>
                <li>Venon <b>dispara em anúncios</b> (humanizados) → CPL menor → <b>CAC mais barato</b>.</li>
                <li>Net Goiás quase <b>invisível no digital</b> (não roda Ads; poucos reviews).</li>
                <li>Alinhar <b>anúncios humanizados + prova social</b> tende a derrubar o CAC da Integrato abaixo do da Venon.</li>
              </ul>
            </div>
            <div class="card">
              <h3 style="margin-top:0">Estado Geral</h3>
              <div class="grid">
                <div class="kpi"><span class="dot ok"></span> Instagram Integrato forte (9/10)</div>
                <div class="kpi"><span class="dot ok"></span> Reviews Integrato fortes (9.5/10)</div>
                <div class="kpi"><span class="dot warn"></span> Anúncios Integrato fracos (5/10)</div>
                <div class="kpi"><span class="dot ok"></span> Venon forte em Ads (9/10)</div>
                <div class="kpi"><span class="dot bad"></span> Net Goiás sem Ads (0/10)</div>
              </div>
            </div>
          </div>
        </section>

        <!-- Slide 2: Scorecard donuts -->
        <section class="slide" aria-label="Scorecard Comparativo">
          <div>
            <h2>Scorecard Comparativo</h2>
            <div class="sub">Notas (0–10): Instagram • Reviews • Anúncios</div>
          </div>
          <div class="grid cols-3">
            <div class="card"><canvas id="donutIntegrato" aria-label="Donuts Integrato"></canvas></div>
            <div class="card"><canvas id="donutVenon" aria-label="Donuts Venon"></canvas></div>
            <div class="card"><canvas id="donutNetGoias" aria-label="Donuts Net Goiás"></canvas></div>
          </div>
        </section>

        <!-- Slide 3: Radar -->
        <section class="slide" aria-label="Matriz de Posicionamento">
          <div>
            <h2>Matriz de Posicionamento</h2>
            <div class="sub">Confiança • Humanização • Clareza de Oferta • Presença em Ads • Proximidade Local</div>
          </div>
          <div class="card"><canvas id="radar" aria-label="Radar comparativo"></canvas></div>
        </section>

        <!-- Slide 4: Por que a Venon lidera em Ads -->
        <section class="slide" aria-label="Por que a Venon lidera em Ads">
          <div>
            <h2>Por que a Venon lidera em Anúncios</h2>
            <div class="sub">Humanização + Volume de Criativos = CPL menor = CAC menor</div>
          </div>
          <div class="grid cols-2">
            <div class="card">
              <ul class="clean">
                <li><b>10 criativos humanizados ativos</b> com rostos e situações reais (lazer, estudo, trabalho).</li>
                <li>Estrutura simples: <b>dor → situação → solução → CTA</b>.</li>
                <li>Conexão emocional eleva CTR e derruba CPL.</li>
                <li>Resultado: <b>CAC mais barato</b> mesmo com menos reviews que a Integrato.</li>
              </ul>
            </div>
            <div class="card">
              <table class="table" aria-label="Comparativo rápido">
                <thead><tr><th></th><th>Integrato</th><th>Venon</th></tr></thead>
                <tbody>
                  <tr><td>Humanização nos Ads</td><td>Baixa</td><td><b>Alta</b></td></tr>
                  <tr><td>Variedade de Criativos</td><td>Média (6)</td><td><b>Alta (10)</b></td></tr>
                  <tr><td>CPL</td><td>Mais alto</td><td><b>Mais baixo</b></td></tr>
                  <tr><td>CAC</td><td>Mais alto</td><td><b>Mais baixo</b></td></tr>
                </tbody>
              </table>
            </div>
          </div>
        </section>

        <!-- Slide 5: Gap & Oportunidade Integrato -->
        <section class="slide" aria-label="Gap & Oportunidade Integrato">
          <div>
            <h2>Anúncios da Integrato — Gap & Oportunidade</h2>
            <div class="sub">Alinhar Ads ao Instagram + Prova Social = CPL ↓ e CAC ↓</div>
          </div>
          <div class="grid cols-2">
            <div class="card">
              <h3 style="margin-top:0">Gaps</h3>
              <ul class="clean">
                <li>Criativos frios, genéricos, sem rostos.</li>
                <li>Não usam <b>+200 reviews (4,8★)</b> nos anúncios.</li>
                <li>CTA pouco urgente e desalinhado com a identidade do feed.</li>
              </ul>
            </div>
            <div class="card">
              <h3 style="margin-top:0">Oportunidades</h3>
              <ul class="clean">
                <li>Humanizar (clientes, técnicos, famílias, bairros).</li>
                <li>Colar <b>prova social</b> (número + prints) em todo criativo.</li>
                <li>Estrutura: <b>Bairro/Dor → Prova Social → Oferta (500 Mega R$99, instala 24h) → CTA</b>.</li>
              </ul>
            </div>
          </div>
        </section>

        <!-- Slide 6: Reviews como ativo -->
        <section class="slide" aria-label="Reviews como ativo">
          <div>
            <h2>Google Reviews — Ativo Estratégico</h2>
            <div class="sub">A confiança dos vizinhos como motor de conversão</div>
          </div>
          <div class="grid cols-3">
            <div class="card">
              <div class="badge">Integrato</div>
              <h3 style="margin:8px 0 6px">200+ avaliações</h3>
              <p class="sub">Média 4,8★</p>
            </div>
            <div class="card">
              <div class="badge">Venon</div>
              <h3 style="margin:8px 0 6px">65 avaliações</h3>
              <p class="sub">Média 4,8★</p>
            </div>
            <div class="card">
              <div class="badge">Net Goiás</div>
              <h3 style="margin:8px 0 6px">10 avaliações</h3>
              <p class="sub">Média 4,5★</p>
            </div>
          </div>
          <div class="card" style="margin-top:18px">
            <canvas id="barsReviews" aria-label="Comparação de Reviews"></canvas>
          </div>
        </section>

        <!-- Slide 7: Onde cada um ganha -->
        <section class="slide" aria-label="Onde cada um ganha">
          <div>
            <h2>Onde cada um está ganhando</h2>
            <div class="sub">Foco em decisões</div>
          </div>
          <div class="grid cols-3">
            <div class="card">
              <h3 style="margin-top:0">Integrato</h3>
              <ul class="clean">
                <li><b>Instagram</b> (posicionamento humano).</li>
                <li><b>Prova social</b> (200+ reviews, 4,8★).</li>
              </ul>
            </div>
            <div class="card">
              <h3 style="margin-top:0">Venon</h3>
              <ul class="clean">
                <li><b>Anúncios humanizados</b> (CPL menor).</li>
                <li><b>CAC menor</b> por maior eficiência criativa.</li>
              </ul>
            </div>
            <div class="card">
              <h3 style="margin-top:0">Net Goiás</h3>
              <ul class="clean">
                <li>Fora do digital pago.</li>
                <li>Espaço aberto para ser <b>engolido</b>.</li>
              </ul>
            </div>
          </div>
        </section>

        <!-- Slide 8: Rota 15 dias -->
        <section class="slide" aria-label="Rota 15 dias">
          <div>
            <h2>Rota de Virada — 15 dias</h2>
            <div class="sub">Ações imediatas para cair CAC</div>
          </div>
          <div class="grid cols-2">
            <div class="card">
              <ul class="clean">
                <li>Gravar <b>10 criativos humanizados</b> (clientes, técnicos, famílias, bairros).</li>
                <li>Copys com: <b>Bairro/Dor → Prova Social (+200 4,8★) → Oferta (500 Mega R$99, instala 24h) → CTA</b>.</li>
                <li>Google Business Profile: <b>produtos/planos, posts semanais, Q&A, fotos por bairro</b>.</li>
              </ul>
            </div>
            <div class="card">
              <ul class="clean">
                <li><b>Meta CPL</b>: ≤ R$12.</li>
                <li><b>Reviews/mês</b>: +100 até 500.</li>
                <li><b>SLA WhatsApp</b>: resposta < 5 min (com bot + humano).</li>
              </ul>
            </div>
          </div>
        </section>

        <!-- Slide 9: 30-60-90 -->
        <section class="slide" aria-label="Plano 30-60-90">
          <div>
            <h2>Plano 30–60–90</h2>
            <div class="sub">Roadmap para previsibilidade</div>
          </div>
          <div class="grid cols-3">
            <div class="card">
              <div class="badge">30 dias</div>
              <ul class="clean">
                <li>Biblioteca de prova social (prints e vídeos).</li>
                <li>Search Brand + Genérico + PMAX Local.</li>
                <li>CRM WhatsApp + SLA + follow-ups.</li>
              </ul>
            </div>
            <div class="card">
              <div class="badge">60 dias</div>
              <ul class="clean">
                <li>LP verificador de cobertura.</li>
                <li>Testes de oferta (instala 24h, mesh 30d, preço fixo 12m).</li>
                <li>Remarketing com reviews e instalações por bairro.</li>
              </ul>
            </div>
            <div class="card">
              <div class="badge">90 dias</div>
              <ul class="clean">
                <li>Escalar PMAX/Search (negativos + termos de bairro).</li>
                <li>SEO local: páginas por bairro.</li>
                <li>Meta: <b>500 reviews</b>.</li>
              </ul>
            </div>
          </div>
        </section>

        <!-- Slide 10: Impacto Financeiro -->
        <section class="slide" aria-label="Impacto Financeiro">
          <div>
            <h2>Impacto Financeiro — CPL & CAC (estimativas)</h2>
            <div class="sub">Com humanização + prova social, CPL tende a igualar Venon; CAC tende a ficar menor</div>
          </div>
          <div class="card"><canvas id="barsFinance" aria-label="Barras Financeiras"></canvas></div>
        </section>

        <!-- Slide 11: Recomendações finais -->
        <section class="slide" aria-label="Recomendações finais">
          <div>
            <h2>Recomendações Finais</h2>
            <div class="sub">Orientadas à decisão</div>
          </div>
          <div class="grid cols-2">
            <div class="card">
              <ul class="clean">
                <li>Ads devem ser o <b>espelho do Instagram</b> (pessoas reais, bairro, dor, solução, CTA).</li>
                <li>Prova social em <b>100% dos criativos</b> (número e prints).</li>
                <li>Rotina semanal de <b>teste A/B</b> (2 criativos, 2 copys, 1 detalhe).</li>
              </ul>
            </div>
            <div class="card">
              <ul class="clean">
                <li>KPI de <b>Reviews</b>: +100/mês até 500.</li>
                <li><b>SLA WhatsApp</b>: < 5 minutos.</li>
                <li>War Room semanal com painel de funil e gargalos.</li>
              </ul>
            </div>
          </div>
        </section>

        <!-- Slide 12: Encerramento -->
        <section class="slide" aria-label="Encerramento">
          <div>
            <h2>Encerramento</h2>
            <div class="sub">Três passos para a virada</div>
          </div>
          <div class="grid cols-3">
            <div class="card"><b>1) Produção</b><br/>Gravar 10 criativos humanizados</div>
            <div class="card"><b>2) GBP</b><br/>Produtos, posts, Q&A e fotos por bairro</div>
            <div class="card"><b>3) Meta de CPL</b><br/>Rodar campanha com meta ≤ R$12</div>
          </div>
        </section>

      </div>
    </main>

    <footer>
      <div class="footer-inner">
        <button class="navbtn" id="prev" aria-label="Slide anterior">◀</button>
        <button class="navbtn" id="next" aria-label="Próximo slide">▶</button>
      </div>
    </footer>
  </div>

  <script>
    const slides = document.getElementById('slides');
    const sections = Array.from(slides.querySelectorAll('.slide'));
    const progress = document.getElementById('progress');

    // Build dot navigation
    sections.forEach((_,i)=>{
      const d=document.createElement('div');d.className='dotnav';d.title='Slide '+(i+1);d.addEventListener('click',()=>goTo(i));progress.appendChild(d)
    });

    function activeDot(){
      const idx = currentIndex();
      progress.querySelectorAll('.dotnav').forEach((el,i)=>{
        el.classList.toggle('active', i===idx)
      })
    }

    function currentIndex(){
      let nearestIndex = 0; let nearestDist = Infinity;
      sections.forEach((s,i)=>{const r=s.getBoundingClientRect();const d=Math.abs(r.top-80);if(d<nearestDist){nearestDist=d;nearestIndex=i}});
      return nearestIndex;
    }

    function goTo(i){
      sections[i].scrollIntoView({behavior:'smooth', block:'start'});
      setTimeout(activeDot, 400);
    }

    document.getElementById('prev').onclick = ()=>goTo(Math.max(0, currentIndex()-1));
    document.getElementById('next').onclick = ()=>goTo(Math.min(sections.length-1, currentIndex()+1));
    slides.addEventListener('scroll', ()=>activeDot());
    window.addEventListener('resize', ()=>activeDot());
    activeDot();

    // Charts theme helpers
    const gridColor = 'rgba(234,234,240,.12)';
    const tickColor = '#C9CFDB';
    const baseDonut = [
      'rgba(107,60,246,.9)','rgba(156,123,255,.9)','rgba(0,230,168,.85)'
    ];
    const baseDonut2 = [
      'rgba(107,60,246,.25)','rgba(156,123,255,.25)','rgba(0,230,168,.25)'
    ];

    // Data
    const scoreInstagram = { Integrato: 9, Venon: 7, NetGoias: 5 };
    const scoreReviews   = { Integrato: 9.5, Venon: 7.5, NetGoias: 4 };
    const scoreAds       = { Integrato: 5, Venon: 9, NetGoias: 0 };

    // Donut builders per provider
    function donutConfig(values, label){
      return {
        type:'doughnut',
        data:{
          labels:['Instagram','Reviews','Anúncios'],
          datasets:[{
            data: values,
            backgroundColor: baseDonut,
            borderColor: ['#2a2352','#2a2352','#0a3a32'],
            borderWidth:1
          }]
        },
        options:{
          plugins:{
            legend:{labels:{color:tickColor}},
            title:{display:true,text:label,color:'#fff',font:{weight:'bold',size:16}}
          },
          cutout:'58%',
        }
      }
    }

    const donut1 = new Chart(
      document.getElementById('donutIntegrato').getContext('2d'),
      donutConfig([scoreInstagram.Integrato, scoreReviews.Integrato, scoreAds.Integrato],'Integrato')
    );
    const donut2 = new Chart(
      document.getElementById('donutVenon').getContext('2d'),
      donutConfig([scoreInstagram.Venon, scoreReviews.Venon, scoreAds.Venon],'Venon')
    );
    const donut3 = new Chart(
      document.getElementById('donutNetGoias').getContext('2d'),
      donutConfig([scoreInstagram.NetGoias, scoreReviews.NetGoias, scoreAds.NetGoias],'Net Goiás')
    );

    // Radar
    const radar = new Chart(
      document.getElementById('radar').getContext('2d'),
      {
        type:'radar',
        data:{
          labels:['Confiança/Prova social','Humanização','Clareza de Oferta','Presença em Ads','Proximidade Local'],
          datasets:[
            {label:'Integrato', data:[9.5,6,7,5,9], borderColor:'rgba(107,60,246,1)', backgroundColor:'rgba(107,60,246,.25)'},
            {label:'Venon', data:[7.5,9,7.5,9,7], borderColor:'rgba(0,230,168,1)', backgroundColor:'rgba(0,230,168,.25)'},
            {label:'Net Goiás', data:[4,4,5,0,5], borderColor:'rgba(156,123,255,1)', backgroundColor:'rgba(156,123,255,.18)'}
          ]
        },
        options:{
          plugins:{legend:{labels:{color:tickColor}}},
          scales:{
            r:{angleLines:{color:gridColor}, grid:{color:gridColor}, pointLabels:{color:tickColor}, ticks:{color:tickColor, showLabelBackdrop:false, max:10, stepSize:2}}
          }
        }
      }
    );

    // Bars: Reviews
    const barsReviews = new Chart(
      document.getElementById('barsReviews').getContext('2d'),
      {
        type:'bar',
        data:{
          labels:['Integrato','Venon','Net Goiás'],
          datasets:[
            {label:'Quantidade de Reviews', data:[200,65,10], backgroundColor:'rgba(107,60,246,.8)'},
            {label:'Média ★', data:[4.8,4.8,4.5], type:'line', borderWidth:2, borderColor:'rgba(0,230,168,1)', pointBackgroundColor:'rgba(0,230,168,1)', yAxisID:'y1'}
          ]
        },
        options:{
          plugins:{legend:{labels:{color:tickColor}}},
          scales:{
            x:{ticks:{color:tickColor}, grid:{color:gridColor}},
            y:{beginAtZero:true, ticks:{color:tickColor}, grid:{color:gridColor}},
            y1:{beginAtZero:false, min:4, max:5, position:'right', ticks:{color:tickColor}, grid:{drawOnChartArea:false}}
          }
        }
      }
    );

    // Bars: Finance (estimativas)
    const barsFinance = new Chart(
      document.getElementById('barsFinance').getContext('2d'),
      {
        type:'bar',
        data:{
          labels:['CPL Atual','CPL Meta','CAC Atual','CAC Meta'],
          datasets:[
            {label:'Integrato', data:[18,12,1.0,0.7], backgroundColor:'rgba(107,60,246,.8)'},
            {label:'Venon (ref.)', data:[12,12,0.8,0.8], backgroundColor:'rgba(0,230,168,.7)'}
          ]
        },
        options:{
          plugins:{legend:{labels:{color:tickColor}}, tooltip:{callbacks:{
            label:(ctx)=>{
              const label = ctx.dataset.label+': ';
              if(ctx.dataIndex<2){return label+ctx.parsed.y.toFixed(0)+' R$ (CPL)'}
              else{return label+ctx.parsed.y.toFixed(2)+'× mensalidade (CAC)'}
            }
          }}},
          scales:{
            x:{ticks:{color:tickColor}, grid:{color:gridColor}},
            y:{beginAtZero:true, ticks:{color:tickColor}, grid:{color:gridColor}}
          }
        }
      }
    );

    // Keyboard nav
    document.addEventListener('keydown', (e)=>{
      if(['ArrowRight','PageDown','Space'].includes(e.key)) { e.preventDefault(); document.getElementById('next').click(); }
      if(['ArrowLeft','PageUp'].includes(e.key)) { e.preventDefault(); document.getElementById('prev').click(); }
      if(e.key==='Home'){goTo(0)}
      if(e.key==='End'){goTo(sections.length-1)}
      if((e.ctrlKey||e.metaKey) && e.key.toLowerCase()==='p'){ /* allow print */ }
    });
  </script>
</body>
</html>
