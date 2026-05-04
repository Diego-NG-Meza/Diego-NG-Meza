<style>
  @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500&family=IBM+Plex+Sans:wght@400;500&display=swap');
  .wrap { font-family: 'IBM Plex Sans', sans-serif; padding: 2rem 1.5rem; max-width: 700px; }
  .mono { font-family: 'IBM Plex Mono', monospace; }
  .name { font-size: 28px; font-weight: 500; color: var(--color-text-primary); margin: 0 0 4px; }
  .role { font-size: 14px; color: var(--color-text-secondary); margin: 0 0 1.5rem; font-family: 'IBM Plex Mono', monospace; }
  .divider { border: none; border-top: 0.5px solid var(--color-border-tertiary); margin: 1.5rem 0; }
  .bio { font-size: 15px; color: var(--color-text-secondary); line-height: 1.7; margin: 0 0 1.5rem; }
  .section-label { font-size: 11px; font-weight: 500; letter-spacing: 0.1em; text-transform: uppercase; color: var(--color-text-tertiary); margin: 0 0 12px; font-family: 'IBM Plex Mono', monospace; }
  .tech-grid { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 1.5rem; }
  .tech-pill { font-family: 'IBM Plex Mono', monospace; font-size: 12px; padding: 4px 10px; border: 0.5px solid var(--color-border-secondary); border-radius: 4px; color: var(--color-text-secondary); background: var(--color-background-secondary); }
  .stat-row { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; margin-bottom: 1.5rem; }
  .stat-card { background: var(--color-background-secondary); border-radius: 8px; padding: 12px 14px; }
  .stat-val { font-size: 20px; font-weight: 500; color: var(--color-text-primary); font-family: 'IBM Plex Mono', monospace; }
  .stat-lbl { font-size: 11px; color: var(--color-text-tertiary); margin-top: 2px; }
  .status-bar { display: flex; align-items: center; gap: 10px; padding: 12px 14px; background: var(--color-background-secondary); border-radius: 8px; border: 0.5px solid var(--color-border-tertiary); }
  .dot { width: 8px; height: 8px; border-radius: 50%; background: #3db57a; flex-shrink: 0; }
  .status-text { font-size: 13px; color: var(--color-text-secondary); font-family: 'IBM Plex Mono', monospace; }
  .contact-row { display: flex; gap: 12px; flex-wrap: wrap; margin-top: 1rem; }
  .contact-link { font-size: 13px; font-family: 'IBM Plex Mono', monospace; color: var(--color-text-info); text-decoration: none; border-bottom: 0.5px solid var(--color-border-info); padding-bottom: 1px; }
</style>

<div class="wrap">
  <p class="name">Diego Noel Galarza Meza</p>
  <p class="role">Frontend Developer — Guadalajara, MX</p>

  <p class="bio">
    Construyo interfaces web limpias y funcionales. Me enfoco en escribir HTML semantico, CSS organizado y JavaScript claro. Busco incorporarme a un equipo donde pueda aportar desde el primer dia y seguir creciendo como desarrollador.
  </p>

  <hr class="divider">

  <p class="section-label">Tecnologias</p>
  <div class="tech-grid">
    <span class="tech-pill">HTML5</span>
    <span class="tech-pill">CSS3</span>
    <span class="tech-pill">JavaScript</span>
    <span class="tech-pill">React</span>
    <span class="tech-pill">Tailwind CSS</span>
    <span class="tech-pill">Bootstrap</span>
    <span class="tech-pill">Git</span>
    <span class="tech-pill">Responsive Design</span>
  </div>

  <hr class="divider">

  <div class="status-bar">
    <div class="dot"></div>
    <span class="status-text">Disponible para trabajo — open to opportunities</span>
  </div>

  <div class="contact-row">
    <a class="contact-link" href="https://github.com/Diego-NG-Meza" target="_blank">github.com/Diego-NG-Meza</a>
  </div>
</div>
