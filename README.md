<!doctype html>
<html lang="es" data-theme>
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Alessandro Caldana – Portafolio</title>
  <meta name="description" content="Portafolio y perfil profesional de Alessandro Caldana – Ingeniero de Sistemas y Desarrollador Web." />
  <meta name="author" content="Alessandro Caldana" />
  <meta property="og:title" content="Portafolio – Alessandro Caldana" />
  <meta property="og:description" content="Ingeniero de Sistemas y Desarrollador Web especializado en UX/UI y front‑end moderno." />
  <meta property="og:type" content="website" />
  <meta name="theme-color" content="#0ea5e9" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <link rel="icon" href="assets/favicon.png" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    :root{
      --bg: #0b1220;
      --panel: #0f172a;
      --text: #e5e7eb;
      --muted:#9ca3af;
      --brand:#0ea5e9;
      --brand-2:#22d3ee;
      --radius: 18px;
      --shadow: 0 10px 30px rgba(2,6,23,.35);
    }
    body{margin:0;font-family:Inter,system-ui;background:var(--bg);color:var(--text)}
    a{color:var(--brand);text-decoration:none}
    a:hover{color:var(--brand-2)}
    .wrap{max-width:1120px;margin:auto;padding:28px}
    header{position:sticky;top:0;backdrop-filter:blur(10px);background:rgba(11,18,32,.9)}
    nav{display:flex;justify-content:space-between;align-items:center}
    .brand{display:flex;align-items:center;gap:10px;font-weight:800}
    .nav-links a{margin:0 10px;color:var(--text)}
    .btn{display:inline-flex;align-items:center;gap:8px;padding:10px 14px;border-radius:12px;font-weight:600;background:linear-gradient(135deg,var(--brand),var(--brand-2));color:#06121f;border:0;transition:.3s}
    .btn:hover{transform:scale(1.05);box-shadow:0 0 20px rgba(14,165,233,.4)}
    .btn.secondary{background:transparent;color:var(--text);border:1px solid rgba(255,255,255,.1)}
    .card{background:var(--panel);border-radius:var(--radius);padding:20px;box-shadow:var(--shadow);transition:.3s}
    .card:hover{transform:translateY(-5px);box-shadow:0 10px 25px rgba(14,165,233,.25)}
    .skills img{width:22px;height:22px;margin-right:8px;vertical-align:middle}
    .hero-banner{position:relative;overflow:hidden;border-radius:var(--radius);margin-bottom:40px;background:linear-gradient(135deg,rgba(14,165,233,0.2),rgba(34,211,238,0.1));}
    .hero-banner video,.hero-banner img{width:100%;height:100%;object-fit:cover;opacity:0.15;position:absolute;top:0;left:0;z-index:0}
    .hero-banner .overlay{position:relative;z-index:1;text-align:center;padding:80px 20px}
    .hero-banner h1{font-size:clamp(32px,4vw,60px);margin:0;color:#fff;text-shadow:0 2px 10px rgba(0,0,0,.5)}
    .hero-banner p{font-size:clamp(14px,1.4vw,18px);color:var(--muted);max-width:700px;margin:14px auto 0}
    .project-img{width:100%;border-radius:14px;margin-bottom:10px;aspect-ratio:16/9;object-fit:cover;}
  </style>
</head>
<body>
  <header>
    <div class="wrap">
      <nav>
        <div class="brand"><i class="fa-solid fa-code"></i> Alessandro Caldana</div>
        <div class="nav-links">
          <a href="#proyectos">Proyectos</a>
          <a href="#skills">Skills</a>
          <a href="#experiencia">Experiencia</a>
          <a href="#contacto">Contacto</a>
        </div>
      </nav>
    </div>
  </header>

  <div class="hero-banner">
    <video autoplay muted loop playsinline poster="assets/banner.jpg">
      <source src="https://cdn.coverr.co/videos/coverr-coding-on-laptop-1382/1080p.mp4" type="video/mp4">
    </video>
    <div class="overlay">
      <h1>Hola, soy <span style="color:var(--brand-2)">Alessandro Caldana</span></h1>
      <p>Ingeniero de Sistemas y Desarrollador Web apasionado por el diseño y la tecnología. <br>Transformo ideas en experiencias digitales con propósito.</p>
    </div>
  </div>

  <main class="wrap">
    <section class="hero" id="inicio">
      <h2>Desarrollador Web y UX/UI</h2>
      <p>Ingeniero de Sistemas recién graduado. Actualmente trabajo en el área de desarrollo web en <strong>Emdupar S.A. E.S.P.</strong>, optimizando módulos de facturación, portales web y APIs internas. Me especializo en crear experiencias visuales modernas y eficientes usando Angular, Node.js y PHP/MySQL.</p>
      <div style="display:flex;gap:10px;margin-top:14px">
        <a class="btn" href="#proyectos"><i class="fa-solid fa-rocket"></i> Ver proyectos</a>
        <a class="btn secondary" href="mailto:alesscaldana@gmail.com"><i class="fa-regular fa-paper-plane"></i> Contáctame</a>
      </div>
    </section>

    <section id="proyectos" style="margin-top:32px">
      <h2>Proyectos destacados</h2>
      <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px;margin-top:20px">
        <article class="card">
          <img class="project-img" src="/mnt/data/10395101-8829-4330-bc36-2648248f1424.png" alt="Pagos Emdupar"/>
          <h3>Pagos Emdupar (proxy + SPA)</h3>
          <p>Integración segura entre frontend Angular y backend PHP con proxy HTTPS y control de sesiones.</p>
        </article>
        <article class="card">
          <img class="project-img" src="/mnt/data/1d696ccb-7691-453b-a77d-fd225aba8752.png" alt="Factory Patterns API"/>
          <h3>Factory Patterns API</h3>
          <p>API modular en Node.js y TypeScript aplicando patrones de diseño como Factory Method y Abstract Factory.</p>
        </article>
        <article class="card">
          <img class="project-img" src="/mnt/data/1e0b32f5-c27b-425d-9f1d-f73da7c6cc4b.png" alt="Sistema de Facturación"/>
          <h3>Sistema de Facturación</h3>
          <p>Sistema PHP/MySQL con CRUD, validaciones de stock y reportes para gestión de ventas.</p>
        </article>
      </div>
    </section>

    <section id="skills" style="margin-top:32px">
      <h2>Skills principales</h2>
      <div class="skills" style="display:flex;flex-wrap:wrap;gap:10px;margin-top:10px">
        <span class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/>HTML5</span>
        <span class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg"/>CSS3 / Tailwind</span>
        <span class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"/>JavaScript / TypeScript</span>
        <span class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angular/angular-original.svg"/>Angular</span>
        <span class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg"/>Node.js</span>
        <span class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg"/>PHP / MySQL</span>
        <span class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg"/>Figma</span>
        <span class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg"/>Git / GitHub</span>
      </div>
    </section>

    <section id="experiencia" style="margin-top:32px">
      <h2>Experiencia</h2>
      <div class="card">
        <h3>Emdupar S.A. E.S.P.</h3>
        <p>Actualmente desempeño funciones en desarrollo web, enfocándome en la modernización del sistema de facturación y la optimización de portales para usuarios y administración. Implemento mejoras UX y gestión de datos en entornos PHP y Angular.</p>
        <span class="chip">2025 · 5 meses</span>
      </div>
    </section>

    <section id="contacto" style="margin-top:32px">
      <h2>Contacto</h2>
      <p>Si deseas colaborar o conocer más de mi trabajo, puedes escribirme directamente a <a href="mailto:alesscaldana@gmail.com">alesscaldana@gmail.com</a> o visitar mis redes.</p>
      <div style="display:flex;gap:10px;flex-wrap:wrap;margin-top:16px" class="social">
        <a href="https://github.com/AlessCaldana" target="_blank"><i class="fa-brands fa-github"></i></a>
        <a href="https://www.linkedin.com/in/alessandro-caldana" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
        <a href="https://www.instagram.com/perruncho22" target="_blank"><i class="fa-brands fa-instagram"></i></a>
      </div>
    </section>

    <footer style="margin-top:32px;text-align:center;color:#9ca3af;font-size:14px">
      © <span id="y"></span> · Hecho con <i class="fa-regular fa-heart"></i> por Alessandro Caldana
    </footer>
  </main>

  <script>
    document.getElementById('y').textContent = new Date().getFullYear();
  </script>
</body>
</html>
