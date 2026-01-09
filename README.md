
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1" />
  <title>Isaiah Ochieng — Backend Developer</title>
  <meta name="description" content="Professional backend developer portfolio showcasing projects, skills, and contact information." />  <style>
    :root {
      --bg: #f8fafc;
      --card: #ffffff;
      --muted: #6b7280;
      --accent: #3b82f6;
      --radius: 12px;
      --maxw: 980px;
      --text: #111827;
    }

    [data-theme="dark"] {
      --bg: #0f172a;
      --card: #1e293b;
      --muted: #94a3b8;
      --text: #e2e8f0;
      --accent: #3b82f6;
    }

    * { box-sizing: border-box; }
    body { margin: 0; background: var(--bg); color: var(--text); display: flex; justify-content: center; padding: 20px; font-family: 'Inter', sans-serif; transition: 0.2s ease; }
    .wrap { width: 100%; max-width: var(--maxw); display: flex; flex-direction: column; gap: 20px; }

    header { display: flex; align-items: center; gap: 16px; margin-bottom: 16px; flex-wrap: wrap; }
    .avatar { width: 72px; height: 72px; border-radius: var(--radius); background: linear-gradient(135deg,var(--accent),#7c3aed); display: grid; place-items: center; font-weight: 700; font-size: 24px; color: white; flex-shrink: 0; }
    h1 { margin: 0; font-size: 24px; }
    p.lead { margin: 4px 0 0; color: var(--muted); font-size: 15px; line-height: 1.4; }

    .meta { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 8px; }
    .chip { background: #e5e7eb; padding: 6px 10px; border-radius: 999px; font-size: 12px; color: var(--muted); }

    [data-theme="dark"] .chip { background: #334155; }

    .grid { display: flex; flex-direction: column; gap: 20px; }
    @media(min-width: 880px){ .grid { flex-direction: row; } }

    .card { background: var(--card); padding: 20px; border-radius: var(--radius); box-shadow: 0 4px 20px rgba(0,0,0,0.05); flex: 1; }
    .section { margin-bottom: 20px; }

    .projects { display: grid; gap: 12px; }
    .proj { background: #f3f4f6; padding: 14px; border-radius: var(--radius); border-left: 4px solid var(--accent); }
    .proj h3 { margin: 0 0 4px; font-size: 16px; }
    .proj p { margin: 0; color: var(--muted); font-size: 14px; }

    [data-theme="dark"] .proj { background: #334155; }

    .skills { display: flex; flex-direction: column; gap: 6px; }
    .skill { font-size: 14px; }
    .bar { height: 8px; background: #e5e7eb; border-radius: 6px; overflow: hidden; }
    .bar span { display: block; height: 100%; background: var(--accent); }

    [data-theme="dark"] .bar { background: #1e293b; }

    .contact-list { display: flex; flex-direction: column; gap: 8px; margin-top: 10px; }
    .btn { display: inline-block; padding: 10px 14px; border-radius: 8px; background: var(--accent); color: #fff; text-decoration: none; font-weight: 600; text-align: center; }
    a { color: inherit; }

    .toggle-theme { cursor: pointer; padding: 8px 12px; border-radius: 6px; background: var(--card); box-shadow: 0 2px 6px rgba(0,0,0,0.1); }
  </style></head>
<body data-theme="light">
  <main class="wrap"><button class="toggle-theme" onclick="toggleTheme()">Toggle Dark Mode</button>

<div class="grid">
  <section class="card">
    <header>
      <div class="avatar">IO</div>
      <div>
        <h1>Isaiah Ochieng</h1>
        <p class="lead">Backend Developer</p>
        <div class="meta">
          <span class="chip">Open to work</span>
          <span class="chip">Kenya, Nairobi</span>
          <span class="chip">otienoisaiah696@gmail.com</span>
        </div>
      </div>
    </header>

    <div class="section">
      <h2>About</h2>
      <p>I build efficient backend systems and explore crypto technologies to create scalable solutions.</p>
    </div>

    <div class="section">
      <h2>Projects</h2>
      <div class="projects">
        <div class="proj">
          <h3>Project Atlas</h3>
          <p>Enterprise-grade admin dashboard with realtime charts and RBAC.</p>
        </div>
        <div class="proj">
          <h3>Streamline API</h3>
          <p>High-performance REST API for handling data integrations with monitoring and logs.</p>
        </div>
        <div class="proj">
          <h3>Crypto Tracker</h3>
          <p>Backend service powering a crypto price tracking tool used for alerts and analytics.</p>
        </div>
      </div>
    </div>
  </section>

  <aside class="card">
    <div class="section">
      <h2>Skills</h2>
      <div class="skills">
        <div class="skill">Python<div class="bar"><span style="width:70%"></span></div></div>
<div class="skill">C++<div class="bar"><span style="width:50%></span></div>
      </div>
    </div>

    <div class="section">
      <h2>Contact</h2>
      <div class="contact-list">
        <a class="btn" href="mailto:otienoisaiah696@gmail.com">Email Me</a>
        <a href="https://github.com/isaa-bad" target="_blank">GitHub</a>
        <a href="https://www.linkedin.com/in/isaiah-ochieng-16a9b9189" target="_blank">LinkedIn</a>
      </div>
    </div>

    <div class="section">
      <h2>Message Me</h2>
      <form action="https://formsubmit.co/otienoisaiah696@gmail.com" method="POST">
        <input type="hidden" name="_captcha" value="false">
        <input type="text" name="name" placeholder="Your Name" required style="width:100%;padding:10px;margin:5px 0;border-radius:8px;border:1px solid #ccc;">
        <input type="email" name="email" placeholder="Your Email" required style="width:100%;padding:10px;margin:5px 0;border-radius:8px;border:1px solid #ccc;">
        <textarea name="message" placeholder="Message" required style="width:100%;padding:10px;margin:5px 0;border-radius:8px;border:1px solid #ccc;height:80px;"></textarea>
        <button type="submit" class="btn">Send Message</button>
      </form>
    </div>
  </aside>
</div>

  </main><script>
function toggleTheme(){
  const body=document.body;
  body.dataset.theme = body.dataset.theme === "dark" ? "light" : "dark";
}
</script></body>
</html>

##  Tech Stack
- **Languages:**  
  - C++ (core logic / performance-critical components) 
  - Python (backend services, automation, prototypes)

- **Tools:**  
  - Git & GitHub  
  - Linux-based development environment
