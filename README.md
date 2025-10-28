<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Perfil - GitHub</title>
  <link rel="preconnect" href="https://cdn.jsdelivr.net" crossorigin>
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --accent:#7c3aed; --glass: rgba(255,255,255,0.04);
      --muted: #94a3b8; --glass-2: rgba(255,255,255,0.03);
    }
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,ui-sans-serif,system-ui,-apple-system,'Segoe UI',Roboto,'Helvetica Neue',Arial;color:#e6eef8;background:radial-gradient(1200px 600px at 10% 10%, rgba(124,58,237,0.12), transparent), radial-gradient(1000px 400px at 90% 90%, rgba(14,165,233,0.06), transparent), var(--bg);min-height:100vh;}
    .wrap{max-width:980px;margin:40px auto;padding:28px;border-radius:16px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));box-shadow:0 6px 30px rgba(2,6,23,0.7);border:1px solid rgba(255,255,255,0.03)}

    header{display:flex;gap:20px;align-items:center}
    .avatar{width:120px;height:120px;border-radius:16px;overflow:hidden;flex:0 0 120px;border:1px solid var(--glass);background:linear-gradient(135deg,var(--glass),transparent);display:flex;align-items:center;justify-content:center}
    .avatar img{width:100%;height:100%;object-fit:cover}
    .intro{flex:1}
    h1{margin:0;font-size:28px;letter-spacing:-0.5px}
    p.lead{margin:6px 0 0;color:var(--muted)}
    .badges{margin-top:10px;display:flex;gap:10px;flex-wrap:wrap}
    .badge{display:inline-flex;align-items:center;gap:8px;padding:6px 10px;border-radius:999px;background:var(--glass);border:1px solid var(--glass-2);font-size:13px}
    .badge img{width:18px;height:18px;display:block}

    main{display:grid;grid-template-columns:1fr 360px;gap:22px;margin-top:22px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.02)}

    .tech-grid{display:flex;flex-wrap:wrap;gap:12px}
    .tech{width:80px;height:80px;background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);border-radius:12px;display:flex;flex-direction:column;align-items:center;justify-content:center;padding:8px;border:1px solid rgba(255,255,255,0.02)}
    .tech img{width:36px;height:36px;display:block}
    .tech span{font-size:12px;color:var(--muted);margin-top:6px}

    .charts{display:grid;grid-template-columns:1fr 1fr;gap:12px}

    /* GIF tile */
    .eva-tile{position:relative;overflow:hidden;border-radius:10px;border:1px solid rgba(255,255,255,0.03)}
    .eva-tile img{width:100%;height:220px;object-fit:cover;display:block;filter:contrast(1.02) saturate(1.1)}
    .eva-caption{position:absolute;left:12px;bottom:12px;background:linear-gradient(180deg, rgba(0,0,0,0.32), rgba(0,0,0,0.6));padding:8px;border-radius:8px;color:#fff;font-weight:600}

    footer{margin-top:18px;display:flex;gap:8px;align-items:center;justify-content:space-between}
    .small{color:var(--muted);font-size:13px}

    /* Responsive */
    @media (max-width:880px){main{grid-template-columns:1fr} .eva-tile img{height:180px}}

    /* subtle animation */
    .pulse{animation:pulse 6s ease-in-out infinite}
    @keyframes pulse{0%{transform:translateY(0)}50%{transform:translateY(-4px)}100%{transform:translateY(0)}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="avatar">
        <!-- Replace with your avatar URL -->
        <img src="https://avatars.githubusercontent.com/u/583231?v=4" alt="Avatar">
      </div>
      <div class="intro">
        <h1>Tu Nombre — Desarrollador Fullstack</h1>
        <p class="lead">Especializado en aplicaciones web y móviles con React, React Native y .NET. Apasionado por código limpio, buenas UX y performance.</p>
        <div class="badges">
          <span class="badge">⭐ Open to work</span>
          <span class="badge">📍 Monterrey, México</span>
          <span class="badge">💼 Abierto a colaboraciones</span>
        </div>
      </div>
    </header>

    <main>
      <section class="card">
        <h3>📚 Tecnologías</h3>
        <div class="tech-grid" style="margin-top:12px">
          <!-- Icons loaded from jsDelivr simple-icons. Replace or keep. -->
          <div class="tech"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React"><span>React</span></div>
          <div class="tech"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React Native"><span>React Native</span></div>
          <div class="tech"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/expo/expo-original.svg" alt="Expo"><span>Expo</span></div>
          <div class="tech"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#"><span>C#</span></div>
          <div class="tech"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/microsoftsqlserver/microsoftsqlserver-plain.svg" alt="SQL Server"><span>SQL</span></div>
          <div class="tech"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL"><span>MySQL</span></div>
          <div class="tech"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript"><span>TypeScript</span></div>
          <div class="tech"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java"><span>Java</span></div>
        </div>

        <div style="margin-top:18px">
          <h4>📈 Uso de tecnologías (ejemplo)</h4>
          <canvas id="skillsChart" style="width:100%;height:220px;margin-top:8px"></canvas>
        </div>

        <div style="margin-top:18px">
          <h4>🔥 Proyectos recientes</h4>
          <ul style="color:var(--muted);margin-top:8px">
            <li>App móvil de entregas — React Native + Expo</li>
            <li>API para inventarios — .NET 7 + Entity Framework</li>
            <li>Dashboard analítico — React + TypeScript + Chart.js</li>
          </ul>
        </div>
      </section>

      <aside>
        <div class="card eva-tile pulse">
          <!-- GIF: reemplaza la URL por la GIF de EVA-01 que prefieras -->
          <img id="evaGif" src="https://via.placeholder.com/640x360.png?text=Reemplaza+este+GIF+por+Eva+01" alt="EVA-01 GIF">
          <div class="eva-caption">EVA-01 — Piloto: <strong>Shinji</strong></div>
        </div>

        <div class="card" style="margin-top:12px">
          <h4>📎 Enlaces</h4>
          <p style="margin:8px 0;color:var(--muted)"> <a href="#" target="_blank">Portafolio</a> • <a href="#" target="_blank">LinkedIn</a> • <a href="#" target="_blank">Twitter</a></p>

          <h4 style="margin-top:12px">🎯 Contacto</h4>
          <p style="margin:8px 0;color:var(--muted)">Email: tu.email@ejemplo.com</p>
        </div>

        <div class="card" style="margin-top:12px">
          <h4>📊 Pequeñas métricas</h4>
          <div style="display:flex;gap:8px;flex-direction:column">
            <div style="display:flex;justify-content:space-between"><small class="small">Repos activos</small><strong>12</strong></div>
            <div style="display:flex;justify-content:space-between"><small class="small">Contribuciones</small><strong>1.2k</strong></div>
            <div style="display:flex;justify-content:space-between"><small class="small">Followers</small><strong>480</strong></div>
          </div>
        </div>
      </aside>
    </main>

    <footer class="wrap-footer" style="margin-top:18px">
      <div class="small">Generado: Plantilla HTML</div>
      <div class="small">Personalízala y sube a GitHub Pages o úsala como archivo en tu perfil.</div>
    </footer>
  </div>

  <!-- scripts -->
  <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"></script>
  <script>
    // Datos de ejemplo para la gráfica de habilidades (modifica a tu gusto)
    const ctx = document.getElementById('skillsChart');
    new Chart(ctx, {
      type: 'doughnut',
      data: {
        labels: ['React','React Native','C#','.NET','SQL/MySQL','TypeScript','Java','Expo'],
        datasets: [{
          data: [18,12,14,13,12,10,11,10],
          // Chart.js auto picks colors
        }]
      },
      options: {
        plugins:{legend:{position:'bottom',labels:{color:'#cbd5e1'}}},
        maintainAspectRatio:false
      }
    });

    // Fácil reemplazo del GIF: arrastra la URL de la GIF que quieras y pégala en el src
    // Ejemplo de cómo cargar desde un CDN externo o imagen en tu repo
    // document.getElementById('evaGif').src = 'URL_DE_TU_GIF_DE_EVA';

    // Pequeña mejora: lazy load images fuera de viewport
    if('loading' in HTMLImageElement.prototype){
      document.querySelectorAll('img[loading]').forEach(img=>img.loading='lazy');
    }
  </script>
</body>
</html>
