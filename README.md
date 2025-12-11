<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Isaiah Ochieng — Developer Portfolio</title>
  <meta name="description" content="Professional backend developer portfolio showcasing projects, skills, and contact information." />  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#94a3b8; --accent:#3b82f6; --glass: rgba(255,255,255,0.03);
      --radius:14px; --maxw:980px; color-scheme: dark;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%;}
    body{margin:0;background:linear-gradient(180deg,var(--bg),#071022);color:#e6eef8;display:flex;align-items:center;justify-content:center;padding:40px 20px}
    .wrap{width:100%;max-width:var(--maxw)}
    header{display:flex;align-items:center;gap:18px;margin-bottom:22px}
    .avatar{width:84px;height:84px;border-radius:12px;flex:0 0 84px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:grid;place-items:center;font-weight:700;font-size:28px;color:white}
    h1{margin:0;font-size:28px}
    p.lead{margin:6px 0 0;color:var(--muted)}

    .grid{display:grid;grid-template-columns:1fr 340px;gap:20px}
    @media (max-width:880px){.grid{grid-template-columns:1fr}}

    .card{background:linear-gradient(180deg,var(--card),rgba(8,12,20,0.8));padding:20px;border-radius:var(--radius);box-shadow:0 8px 30px rgba(2,6,23,0.6)}
    .section{margin-bottom:18px}
    .meta{display:flex;gap:12px;flex-wrap:wrap}
    .chip{background:var(--glass);padding:8px 12px;border-radius:999px;font-size:13px;color:var(--muted)}

    .projects{display:grid;gap:12px}
    .proj{background:linear-gradient(180deg,#07102111,transparent);padding:14px;border-radius:10px;border:1px solid rgba(255,255,255,0.03)}
    .proj h3{margin:0 0 6px;font-size:16px}
    .proj p{margin:0;color:var(--muted);font-size:14px}
    .proj .tags{margin-top:8px}
    .tag{display:inline-block;background:#081226;padding:6px 8px;border-radius:8px;font-size:12px;color:var(--muted);margin-right:6px}

    .sidebar .card{padding:16px}
    .skills{display:flex;flex-wrap:wrap;gap:8px}
    .skill{background:transparent;border:1px solid rgba(255,255,255,0.04);padding:8px 10px;border-radius:8px;font-size:13px;color:var(--muted)}

    .contact-list{display:flex;flex-direction:column;gap:8px}
    .btn{display:inline-block;padding:10px 14px;border-radius:10px;background:linear-gradient(90deg,var(--accent),#7c3aed);color:white;text-decoration:none;font-weight:600}

    footer{margin-top:18px;color:var(--muted);font-size:13px;text-align:center}
    a{color:inherit}
    .muted{color:var(--muted)}
  </style></head>
<body>
  <main class="wrap" role="main">
    <div class="grid">
      <section class="card">
        <header>
          <div class="avatar" aria-hidden="true">IO</div>
          <div>
            <h1 id="name">Isaiah Ochieng — Backend Developer</h1>
            <p class="lead">Am a backend web developer and a Crypto enthusiast.</p>
            <div class="meta" style="margin-top:10px">
              <span class="chip">Open to work</span>
              <span class="chip">Location: Kenya, Nairobi</span>
              <span class="chip">Email: otienoisaiah696@gmail.com</span>
            </div>
          </div>
        </header><div class="section">
      <h2 style="margin:0 0 8px;font-size:18px">About</h2>
      <p class="muted">I build efficient backend systems and explore crypto technologies to create scalable solutions.</p>
    </div>

    <div class="section">
      <h2 style="margin:0 0 8px;font-size:18px">Selected Projects</h2>
      <div class="projects">
        <article class="proj">
          <h3>Project Atlas — <small class="muted">SaaS Dashboard</small></h3>
          <p>Enterprise-grade admin dashboard with realtime charts and role-based access.</p>
          <div class="tags"><span class="tag">React</span><span class="tag">Node.js</span><span class="tag">Postgres</span></div>
        </article>

        <article class="proj">
          <h3>Streamline API — <small class="muted">REST API</small></h3>
          <p>High-performance REST API for handling data integrations with monitoring and logs.</p>
          <div class="tags"><span class="tag">Python</span><span class="tag">FastAPI</span><span class="tag">Redis</span></div>
        </article>

        <article class="proj">
          <h3>Crypto Tracker — <small class="muted">Web Tool</small></h3>
          <p>A backend service that powers a crypto price tracking tool used for alerts and analytics.</p>
          <div class="tags"><span class="tag">Go</span><span class="tag">Postgres</span><span class="tag">Docker</span></div>
        </article>
      </div>
    </div>
  </section>

  <aside class="sidebar">
    <div class="card">
      <h3 style="margin-top:0">Skills</h3>
      <div class="skills">
        <span class="skill">Node.js</span>
        <span class="skill">Python</span>
        <span class="skill">FastAPI</span>
        <span class="skill">Postgres</span>
        <span class="skill">Docker</span>
        <span class="skill">REST APIs</span>
        <span class="skill">Git</span>
        <span class="skill">Cloud (AWS/GCP)</span>
      </div>

      <hr style="border:none;height:1px;background:rgba(255,255,255,0.03);margin:14px 0">

      <h3 style="margin:0 0 8px">Contact</h3>
      <div class="contact-list">
        <a class="btn" href="mailto:otienoisaiah696@gmail.com">Email me</a>
        <a style="text-decoration:none;color:var(--muted);font-size:13px" href="https://github.com/your-username" target="_blank">github.com/your-username</a>
        <a style="text-decoration:none;color:var(--muted);font-size:13px" href="https://www.linkedin.com/in/isaiah-ochieng-16a9b9189" target="_blank">linkedin.com/in/isaiah-ochieng-16a9b9189</a>
      </div>
    </div>
  </aside>
</div>

  </main>
</body>
</html>
