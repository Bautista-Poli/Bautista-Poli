
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: var(--font-sans); color: var(--color-text-primary); }
  .container { max-width: 680px; padding: 1.5rem 0; }
  .divider { border: none; border-top: 0.5px solid var(--color-border-tertiary); margin: 1.5rem 0; }
  h1 { font-size: 22px; font-weight: 500; margin-bottom: 0.5rem; }
  h3 { font-size: 16px; font-weight: 500; margin-bottom: 0.75rem; color: var(--color-text-primary); }
  h4 { font-size: 14px; font-weight: 500; margin-bottom: 0.5rem; color: var(--color-text-secondary); }
  p { font-size: 15px; line-height: 1.7; color: var(--color-text-secondary); }
  .badge-row { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 0.75rem; }
  .badge { display: inline-flex; align-items: center; gap: 6px; padding: 6px 14px; border-radius: 6px; font-size: 13px; font-weight: 500; letter-spacing: 0.5px; border: none; cursor: default; }
  .badge img { height: 16px; width: auto; }

  /* Omnia FC: fondo negro, letra naranja fuerte */
  .badge-omnia { background: #000000; color: #FF6B00; border: 0.5px solid #FF6B00; text-decoration: none; }
  .badge-omnia:hover { background: #111111; }

  /* Sophie Vila: fondo crema, letra marrón */
  .badge-sophie { background: #FFFDD0; color: #5D2E0C; border: 0.5px solid #C8A97A; text-decoration: none; }
  .badge-sophie:hover { background: #FFF9B0; }

  .project-link { display: inline-flex; align-items: center; gap: 8px; padding: 8px 18px; border-radius: 8px; font-size: 13px; font-weight: 500; letter-spacing: 0.5px; text-decoration: none; transition: opacity 0.15s; }
  .project-link:hover { opacity: 0.85; }
  .project-link .dot { width: 7px; height: 7px; border-radius: 50%; display: inline-block; }

  .tech-badge { display: inline-flex; align-items: center; gap: 5px; padding: 5px 11px; border-radius: 6px; font-size: 12px; font-weight: 500; background: var(--color-background-secondary); color: var(--color-text-primary); border: 0.5px solid var(--color-border-tertiary); }

  .stats-container { display: flex; gap: 12px; flex-wrap: wrap; }
  .stat-card { flex: 1; min-width: 200px; background: var(--color-background-secondary); border-radius: var(--border-radius-lg); border: 0.5px solid var(--color-border-tertiary); overflow: hidden; }
  .stat-card img { width: 100%; display: block; }
  .stat-card.error { display: flex; align-items: center; justify-content: center; padding: 2rem; min-height: 120px; }
  .stat-card.error p { font-size: 13px; color: var(--color-text-tertiary); text-align: center; }

  .counter-badge { display: inline-flex; align-items: center; gap: 6px; padding: 4px 12px; border-radius: 999px; font-size: 12px; background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); color: var(--color-text-secondary); margin-bottom: 1rem; }
  .li-item { display: flex; align-items: flex-start; gap: 8px; font-size: 15px; color: var(--color-text-secondary); margin-bottom: 6px; line-height: 1.6; }
  .li-item .dot { margin-top: 8px; width: 5px; height: 5px; border-radius: 50%; background: var(--color-text-tertiary); flex-shrink: 0; }
  .linkedin-btn { display: inline-flex; align-items: center; gap: 8px; padding: 8px 18px; border-radius: 8px; background: #0077B5; color: #fff; font-size: 13px; font-weight: 500; text-decoration: none; border: none; cursor: pointer; }
  .linkedin-btn:hover { background: #005e93; }
</style>

<div class="container">
  <div style="display:flex; align-items:center; justify-content:space-between; flex-wrap:wrap; gap:12px; margin-bottom:1.5rem;">
    <div>
      <h1>Bautista Álvarez Poli</h1>
      <p style="font-size:14px; color:var(--color-text-secondary);">Ingeniero Informático · Full Stack Developer</p>
    </div>
    <div class="counter-badge">
      <i class="ti ti-eye" aria-hidden="true" style="font-size:15px;"></i>
      <img src="https://komarev.com/ghpvc/?username=BautistaAlvarezPoli&color=blueviolet&style=flat-square&label=visitas" alt="Profile views" style="height:20px; width:auto;" onerror="this.replaceWith(document.createTextNode('Perfil visto'))">
    </div>
  </div>

  <hr class="divider">

  <h3><i class="ti ti-user-circle" aria-hidden="true" style="font-size:18px; vertical-align:-3px; margin-right:6px;"></i>Sobre mí</h3>
  <p style="margin-bottom:0.75rem;">Soy <strong style="font-weight:500; color:var(--color-text-primary);">Ingeniero Informático</strong> y <strong style="font-weight:500; color:var(--color-text-primary);">Desarrollador Full Stack</strong>. Me especializo en crear soluciones digitales robustas, desde sistemas de gestión empresarial hasta portafolios de arte digital.</p>
  <div style="margin-top:0.75rem;">
    <div class="li-item"><span class="dot"></span><span>🎓 Estudiante de Ingeniería Informática en la UCA.</span></div>
    <div class="li-item"><span class="dot"></span><span>🚀 Experto en <strong style="font-weight:500;">Angular</strong>, <strong style="font-weight:500;">React Native</strong> y <strong style="font-weight:500;">Node.js</strong>.</span></div>
    <div class="li-item"><span class="dot"></span><span>🛠️ Enfoque en escalabilidad, performance y experiencia de usuario.</span></div>
  </div>

  <hr class="divider">

  <h3><i class="ti ti-rocket" aria-hidden="true" style="font-size:18px; vertical-align:-3px; margin-right:6px;"></i>Proyectos destacados</h3>
  <div class="badge-row" style="margin-top:0.5rem;">
    <a href="https://www.omniafc.com.ar/inicio" target="_blank" class="project-link" style="background:#000000; color:#FF6B00; border: 1px solid #FF6B00;">
      <span class="dot" style="background:#FF6B00;"></span>
      OMNIA FC
      <i class="ti ti-external-link" aria-hidden="true" style="font-size:13px;"></i>
    </a>
    <a href="https://sophievila.com.ar/" target="_blank" class="project-link" style="background:#FFFDD0; color:#5D2E0C; border: 1px solid #C8A97A;">
      <span class="dot" style="background:#5D2E0C;"></span>
      SOPHIE VILA
      <i class="ti ti-external-link" aria-hidden="true" style="font-size:13px;"></i>
    </a>
  </div>

  <hr class="divider">

  <h3><i class="ti ti-tools" aria-hidden="true" style="font-size:18px; vertical-align:-3px; margin-right:6px;"></i>Tecnologías y herramientas</h3>
  
  <h4 style="margin-top:0.75rem;">Frontend</h4>
  <div class="badge-row">
    <span class="tech-badge"><img src="https://img.shields.io/badge/-DD0031?logo=angular&logoColor=white&style=flat" style="height:14px;" alt="">Angular</span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/-61DAFB?logo=react&logoColor=black&style=flat" style="height:14px;" alt="">React Native</span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/-F7DF1E?logo=javascript&logoColor=black&style=flat" style="height:14px;" alt="">JavaScript</span>
  </div>
  
  <h4 style="margin-top:0.75rem;">Backend & Databases</h4>
  <div class="badge-row">
    <span class="tech-badge"><img src="https://img.shields.io/badge/-339933?logo=nodedotjs&logoColor=white&style=flat" style="height:14px;" alt="">Node.js</span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/-000000?logo=express&logoColor=white&style=flat" style="height:14px;" alt="">Express.js</span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/-47A248?logo=mongodb&logoColor=white&style=flat" style="height:14px;" alt="">MongoDB</span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/-4479A1?logo=mysql&logoColor=white&style=flat" style="height:14px;" alt="">MySQL</span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/-3776AB?logo=python&logoColor=white&style=flat" style="height:14px;" alt="">Python</span>
  </div>

  <h4 style="margin-top:0.75rem;">DevOps & Herramientas</h4>
  <div class="badge-row">
    <span class="tech-badge"><img src="https://img.shields.io/badge/-000000?logo=vercel&logoColor=white&style=flat" style="height:14px;" alt="">Vercel</span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/-131415?logo=railway&logoColor=white&style=flat" style="height:14px;" alt="">Railway</span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/-F05032?logo=git&logoColor=white&style=flat" style="height:14px;" alt="">Git</span>
  </div>

  <hr class="divider">

  <h3><i class="ti ti-chart-bar" aria-hidden="true" style="font-size:18px; vertical-align:-3px; margin-right:6px;"></i>Estadísticas de GitHub</h3>
  <div class="stats-container" style="margin-top:0.75rem;" id="stats-container">
    <div class="stat-card" id="card-general">
      <img 
        src="https://github-readme-stats.vercel.app/api?username=balvarezpoli&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&cachebuster=2026"
        alt="GitHub stats de Bautista"
        onerror="handleStatError('card-general', 'Stats generales')"
      />
    </div>
    <div class="stat-card" id="card-langs">
      <img 
        src="https://github-readme-stats.vercel.app/api/top-langs/?username=balvarezpoli&layout=compact&theme=tokyonight&hide_border=true&cachebuster=2026"
        alt="Lenguajes más usados"
        onerror="handleStatError('card-langs', 'Top lenguajes')"
      />
    </div>
  </div>
  <p style="font-size:12px; color:var(--color-text-tertiary); margin-top:8px;">
    <i class="ti ti-info-circle" aria-hidden="true" style="font-size:13px; vertical-align:-2px;"></i>
    Si las imágenes no cargan, puede ser un límite de rate de la API de GitHub. El README de tu perfil las mostrará correctamente.
  </p>

  <hr class="divider">

  <h3><i class="ti ti-mail" aria-hidden="true" style="font-size:18px; vertical-align:-3px; margin-right:6px;"></i>Contacto</h3>
  <div style="margin-top:0.75rem;">
    <a href="https://www.linkedin.com/in/bautista-alvarez-poli-84b4891b6" target="_blank" class="linkedin-btn">
      <i class="ti ti-brand-linkedin" aria-hidden="true" style="font-size:16px;"></i>
      LinkedIn
    </a>
  </div>
</div>

<script>
function handleStatError(cardId, label) {
  const card = document.getElementById(cardId);
  if (!card) return;
  card.classList.add('error');
  card.innerHTML = '<p style="font-size:13px; color:var(--color-text-tertiary); text-align:center;"><i class="ti ti-photo-off" style="font-size:20px; display:block; margin-bottom:6px;"></i>' + label + ' no disponible<br><span style="font-size:11px;">Rate limit de GitHub API</span></p>';
}
</script>


### 📫 Contacto
<p align="left">
  <a href="https://www.linkedin.com/in/bautista-alvarez-poli-84b4891b6" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>
