<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { background: #0d1117; }
  .readme-wrap {
    background: #0d1117;
    color: #c9d1d9;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
    padding: 0;
    border: 1px solid #30363d;
    border-radius: 12px;
    overflow: hidden;
    max-width: 760px;
  }
  .banner {
    background: #0d1117;
    text-align: center;
    padding: 2.5rem 1rem 1.5rem;
  }
  .banner h1 {
    font-size: 2rem;
    font-weight: 700;
    color: #ffffff;
    letter-spacing: -1px;
  }
  .typing {
    font-family: monospace;
    font-size: 13px;
    color: #3fb950;
    margin-top: 8px;
    min-height: 20px;
  }
  .body { padding: 2rem; }
  .sec-title {
    font-size: 15px;
    font-weight: 600;
    color: #ffffff;
    margin-bottom: 1rem;
    display: flex;
    align-items: center;
    gap: 6px;
  }
  hr { border: none; border-top: 1px solid #30363d; margin: 1.5rem 0; }
  .prev-about { font-size: 13px; line-height: 1.7; color: #8b949e; }
  .prev-about strong { color: #c9d1d9; }
  .tech-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-top: 0.5rem; }
  .tech-card { background: #161b22; border: 1px solid #30363d; border-radius: 8px; padding: 10px 12px; }
  .tech-card-title { font-size: 11px; text-transform: uppercase; letter-spacing: 0.05em; color: #8b949e; margin-bottom: 8px; }
  .tech-badges { display: flex; flex-wrap: wrap; gap: 4px; }
  .chip { background: #0d1117; border: 1px solid #30363d; border-radius: 4px; padding: 2px 7px; font-size: 11px; color: #c9d1d9; display: inline-flex; align-items: center; gap: 4px; }

  /* SKILL BARS — dark terminal style */
  .skill-row {
    display: flex;
    align-items: center;
    gap: 12px;
    margin-bottom: 10px;
    font-family: monospace;
  }
  .skill-name {
    font-size: 13px;
    color: #c9d1d9;
    min-width: 130px;
    display: flex;
    align-items: center;
    gap: 6px;
  }
  .skill-track {
    flex: 1;
    height: 8px;
    background: #1c2128;
    border-radius: 4px;
    overflow: hidden;
    border: 1px solid #30363d;
  }
  .skill-fill {
    height: 100%;
    border-radius: 4px;
    background: #3fb950;
    box-shadow: 0 0 6px #3fb95066;
  }
  .skill-pct {
    font-size: 12px;
    color: #8b949e;
    min-width: 36px;
    text-align: right;
    font-family: monospace;
  }

  .certs { font-size: 13px; color: #8b949e; padding-left: 1.2rem; line-height: 2; }
  .certs li strong { color: #c9d1d9; }
  .contact-chips { display: flex; flex-wrap: wrap; gap: 6px; margin-top: 0.5rem; }
  .contact-chip { border: 1px solid #30363d; border-radius: 6px; padding: 5px 12px; font-size: 12px; color: #c9d1d9; display: flex; align-items: center; gap: 5px; }
</style>

<div class="readme-wrap">
  <div class="banner">
    <h1>Rodrigo Dalavia Fechner</h1>
    <div class="typing" id="typing"></div>
  </div>
  <div class="body">
    <div class="sec-title">👨‍💻 Sobre mim</div>
    <p class="prev-about">
      Olá, prazer — me chamo <strong>Rodrigo</strong> e atuo como <strong>DevOps</strong>. Minha trajetória começou em redes e infraestrutura, mas acabei descobrindo automações e decidi unir os dois mundos. Atualmente trabalho com desenvolvimento de automações em <strong>Python</strong> e também com infraestrutura, redes e servidores. Meu objetivo é entregar resultados valiosos automatizando processos ou dando suporte a sistemas legados.
    </p>
    <hr/>
    <div class="sec-title">🛠️ Stack Tecnológica</div>
    <div class="tech-grid">
      <div class="tech-card">
        <div class="tech-card-title">🤖 Automação & RPA</div>
        <div class="tech-badges">
          <span class="chip">Python ⭐</span><span class="chip">Playwright</span><span class="chip">Pyautogui</span><span class="chip">FastAPI</span><span class="chip">OpenCV</span><span class="chip">LangChain</span><span class="chip">Pandas</span>
        </div>
      </div>
      <div class="tech-card">
        <div class="tech-card-title">🌐 Redes & Infra</div>
        <div class="tech-badges">
          <span class="chip">TCP/IP ⭐</span><span class="chip">Windows Server</span><span class="chip">Linux</span><span class="chip">Active Directory</span><span class="chip">Hyper-V</span><span class="chip">WireShark</span><span class="chip">Tenable</span>
        </div>
      </div>
      <div class="tech-card">
        <div class="tech-card-title">🗄️ Banco de Dados</div>
        <div class="tech-badges">
          <span class="chip">MySQL ⭐</span><span class="chip">DBeaver</span><span class="chip">PostgreSQL</span><span class="chip">SQL Server</span>
        </div>
      </div>
      <div class="tech-card">
        <div class="tech-card-title">🔧 Ferramentas</div>
        <div class="tech-badges">
          <span class="chip">Git ⭐</span><span class="chip">Docker</span><span class="chip">Terraform</span><span class="chip">Kanban</span>
        </div>
      </div>
    </div>
    <hr/>
    <div class="sec-title">📊 Nível de Habilidades</div>
    <div id="skills-section"></div>
    <hr/>
    <div class="sec-title">🎓 Certificações</div>
    <ul class="certs">
      <li><strong>Jornada Python</strong> — Hashtag, 05/2026</li>
      <li><strong>Redes TCP/IP</strong> — Udemy, 12/2024</li>
      <li><strong>Linux</strong> — Udemy, 05/2025</li>
    </ul>
    <hr/>
    <div class="sec-title">📬 Contato</div>
    <div class="contact-chips">
      <span class="contact-chip">🔗 LinkedIn</span>
      <span class="contact-chip">✉️ rodrigodalavia@gmail.com</span>
      <span class="contact-chip">📍 Porto Alegre, RS</span>
    </div>
  </div>
</div>

<script>
  const skills = [
    { name: 'Python',         pct: 80, color: '#3fb950' },
    { name: 'Windows Server', pct: 75, color: '#3fb950' },
    { name: 'Linux',          pct: 60, color: '#3fb950' },
    { name: 'Redes TCP/IP',   pct: 80, color: '#3fb950' },
    { name: 'MySQL',          pct: 70, color: '#3fb950' },
    { name: 'HTML, CSS',      pct: 65, color: '#3fb950' },
    { name: 'Git',            pct: 75, color: '#3fb950' },
  ];

  const container = document.getElementById('skills-section');
  skills.forEach(s => {
    container.innerHTML += `
      <div class="skill-row">
        <span class="skill-name">${s.name}</span>
        <div class="skill-track">
          <div class="skill-fill" style="width:${s.pct}%;background:${s.color};box-shadow:0 0 8px ${s.color}55"></div>
        </div>
        <span class="skill-pct">${s.pct}%</span>
      </div>`;
  });

  const lines = [
    'Otimizando performance e entregando resultados.',
    'Python | RPA | Playwright | FastAPI | Pandas',
    'Redes TCP/IP e Infraestrutura'
  ];
  const el = document.getElementById('typing');
  let li = 0, ci = 0;
  function tick() {
    const line = lines[li];
    if (ci <= line.length) {
      el.textContent = '> ' + line.slice(0, ci) + '_';
      ci++;
      setTimeout(tick, 40);
    } else {
      ci = 0; li = (li + 1) % lines.length;
      setTimeout(tick, 1800);
    }
  }
  tick();
</script>