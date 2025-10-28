
</head>
<body>
  <div class="wrap">
    <header>
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
         
        </div>

        <div style="margin-top:18px">
          <h4>📈 Uso de tecnologías</h4>
          
        </div>

        <div style="margin-top:18px">
          <h4>🔥 Proyectos recientes</h4>
     
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
       
        </div>
      </aside>
    </main>

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
