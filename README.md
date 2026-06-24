<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Manirumva Shema Patrick | vary-dev — Full-Stack Developer from Rwanda</title>
<meta name="description" content="Full-Stack Web & App Developer from Rwanda. Building interactive, SEO-optimized, and visually stunning applications with React, Next.js, Flutter, Firebase, and more."/>
<meta name="keywords" content="vary-dev, Manirumva Shema Patrick, Full-Stack Developer, Rwanda, React, Next.js, Flutter, Firebase, Web Developer"/>
<meta name="author" content="Manirumva Shema Patrick"/>
<meta property="og:title" content="Manirumva Shema Patrick | vary-dev"/>
<meta property="og:description" content="Full-Stack Web & App Developer from Rwanda building interactive and visually stunning applications."/>
<meta property="og:type" content="profile"/>
<meta property="og:url" content="https://varydeveloper.netlify.app/"/>
<link rel="preconnect" href="https://fonts.googleapis.com"/>
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin/>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Fira+Code:wght@400;500&display=swap" rel="stylesheet"/>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/dist/tabler-icons.min.css"/>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg: #0d1117;
    --bg2: #161b22;
    --bg3: #21262d;
    --bg4: #30363d;
    --border: #30363d;
    --border2: #444c56;
    --text: #e6edf3;
    --text2: #8b949e;
    --text3: #6e7681;
    --accent: #58a6ff;
    --accent2: #3fb950;
    --accent3: #d2a8ff;
    --accent4: #ffa657;
    --accent5: #f78166;
    --radius: 8px;
    --radius-lg: 12px;
    --font: 'Inter', system-ui, sans-serif;
    --mono: 'Fira Code', 'Cascadia Code', monospace;
  }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: var(--font);
    font-size: 14px;
    line-height: 1.6;
    min-height: 100vh;
    padding: 32px 16px;
  }

  .container {
    max-width: 820px;
    margin: 0 auto;
  }

  /* ── HERO ──────────────────────────────────── */
  .hero {
    display: grid;
    grid-template-columns: auto 1fr;
    gap: 28px;
    align-items: center;
    padding: 28px;
    background: var(--bg2);
    border: 1px solid var(--border);
    border-radius: var(--radius-lg);
    margin-bottom: 20px;
  }

  .avatar-svg { display: block; width: 110px; height: 110px; flex-shrink: 0; }

  .hero-right h1 {
    font-size: 22px;
    font-weight: 700;
    color: var(--text);
    margin-bottom: 2px;
    letter-spacing: -0.3px;
  }

  .handle {
    font-family: var(--mono);
    font-size: 12px;
    color: var(--accent);
    background: rgba(88,166,255,0.1);
    border: 1px solid rgba(88,166,255,0.25);
    padding: 2px 9px;
    border-radius: 20px;
    display: inline-block;
    margin-bottom: 10px;
  }

  .hero-desc {
    font-size: 13px;
    color: var(--text2);
    line-height: 1.65;
    margin-bottom: 14px;
    max-width: 460px;
  }

  .pill-row { display: flex; flex-wrap: wrap; gap: 7px; }

  .pill {
    display: inline-flex;
    align-items: center;
    gap: 5px;
    font-size: 11px;
    font-weight: 500;
    padding: 3px 10px;
    border-radius: 20px;
    border: 1px solid;
  }

  .pill i { font-size: 13px; }
  .pill.blue { background: rgba(88,166,255,0.1); color: #58a6ff; border-color: rgba(88,166,255,0.25); }
  .pill.green { background: rgba(63,185,80,0.1); color: #3fb950; border-color: rgba(63,185,80,0.25); }
  .pill.amber { background: rgba(255,166,87,0.1); color: #ffa657; border-color: rgba(255,166,87,0.25); }
  .pill.purple { background: rgba(210,168,255,0.1); color: #d2a8ff; border-color: rgba(210,168,255,0.25); }

  /* ── GRID LAYOUT ────────────────────────────── */
  .grid-2 {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 16px;
    margin-bottom: 16px;
  }

  .grid-3 {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 16px;
    margin-bottom: 16px;
  }

  /* ── CARDS ──────────────────────────────────── */
  .card {
    background: var(--bg2);
    border: 1px solid var(--border);
    border-radius: var(--radius-lg);
    padding: 20px;
  }

  .card-full {
    background: var(--bg2);
    border: 1px solid var(--border);
    border-radius: var(--radius-lg);
    padding: 20px;
    margin-bottom: 16px;
  }

  .card-title {
    font-size: 11px;
    font-weight: 600;
    color: var(--text3);
    text-transform: uppercase;
    letter-spacing: 0.08em;
    display: flex;
    align-items: center;
    gap: 6px;
    margin-bottom: 16px;
    padding-bottom: 10px;
    border-bottom: 1px solid var(--border);
  }

  .card-title i { font-size: 15px; }

  /* ── SKILL ICONS ────────────────────────────── */
  .skill-group { margin-bottom: 16px; }
  .skill-group:last-child { margin-bottom: 0; }

  .skill-group-label {
    font-size: 10px;
    font-weight: 600;
    color: var(--text3);
    text-transform: uppercase;
    letter-spacing: 0.1em;
    margin-bottom: 8px;
    font-family: var(--mono);
  }

  .skill-icons { display: flex; flex-wrap: wrap; gap: 8px; }

  .skill-icon {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 5px;
    background: var(--bg3);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 10px 8px;
    width: 68px;
    transition: border-color 0.15s, background 0.15s;
    text-decoration: none;
  }

  .skill-icon:hover { border-color: var(--border2); background: var(--bg4); }

  .skill-icon img {
    width: 26px;
    height: 26px;
    object-fit: contain;
    display: block;
  }

  .skill-icon .si-svg {
    width: 26px;
    height: 26px;
    display: block;
  }

  .skill-icon span {
    font-size: 9.5px;
    color: var(--text2);
    font-family: var(--mono);
    text-align: center;
    line-height: 1.2;
    white-space: nowrap;
  }

  /* ── ABOUT LIST ─────────────────────────────── */
  .about-list { list-style: none; display: flex; flex-direction: column; gap: 10px; }

  .about-list li {
    display: flex;
    align-items: flex-start;
    gap: 10px;
    font-size: 13px;
    color: var(--text2);
    line-height: 1.55;
  }

  .about-list li i { font-size: 16px; margin-top: 1px; flex-shrink: 0; }

  .about-list li strong { color: var(--text); font-weight: 500; }

  /* ── CONNECT ────────────────────────────────── */
  .connect-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
    gap: 10px;
  }

  .connect-btn {
    display: flex;
    align-items: center;
    gap: 9px;
    padding: 11px 14px;
    background: var(--bg3);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    text-decoration: none;
    color: var(--text);
    font-size: 13px;
    font-weight: 500;
    transition: border-color 0.15s, background 0.15s;
  }

  .connect-btn:hover { border-color: var(--border2); background: var(--bg4); }
  .connect-btn i { font-size: 18px; flex-shrink: 0; }
  .connect-btn .ext { margin-left: auto; font-size: 11px; color: var(--text3); }

  /* ── STATS ROW ──────────────────────────────── */
  .stats-row {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 12px;
    margin-bottom: 16px;
  }

  .stat-card {
    background: var(--bg2);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 16px;
    text-align: center;
  }

  .stat-card .stat-icon { font-size: 20px; margin-bottom: 6px; display: block; }
  .stat-card .stat-val { font-size: 18px; font-weight: 700; color: var(--text); display: block; font-family: var(--mono); }
  .stat-card .stat-label { font-size: 11px; color: var(--text3); display: block; margin-top: 2px; }

  /* ── FOOTER ─────────────────────────────────── */
  .footer {
    text-align: center;
    padding-top: 20px;
    font-size: 11px;
    color: var(--text3);
    font-family: var(--mono);
  }

  /* ── RESPONSIVE ─────────────────────────────── */
  @media (max-width: 600px) {
    .hero { grid-template-columns: 1fr; text-align: center; }
    .hero-desc { max-width: 100%; }
    .pill-row { justify-content: center; }
    .grid-2, .grid-3 { grid-template-columns: 1fr; }
    .stats-row { grid-template-columns: 1fr 1fr; }
  }
</style>
</head>
<body>
<div class="container">

  <!-- ── HERO ── -->
  <div class="hero">
    <!-- Avatar Bot SVG -->
    <svg class="avatar-svg" viewBox="0 0 110 110" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="vary-dev avatar bot coding with coffee">
      <!-- BG circle -->
      <circle cx="55" cy="55" r="54" fill="#161b22" stroke="#30363d" stroke-width="1"/>
      <!-- Monitor -->
      <rect x="18" y="34" width="62" height="38" rx="4" fill="#21262d" stroke="#58a6ff" stroke-width="0.8"/>
      <rect x="20" y="36" width="58" height="33" rx="3" fill="#0d1117"/>
      <!-- Code lines -->
      <rect x="24" y="40" width="22" height="2" rx="1" fill="#58a6ff"/>
      <rect x="24" y="44" width="34" height="2" rx="1" fill="#f78166"/>
      <rect x="24" y="48" width="28" height="2" rx="1" fill="#3fb950"/>
      <rect x="24" y="52" width="38" height="2" rx="1" fill="#d2a8ff"/>
      <rect x="24" y="56" width="20" height="2" rx="1" fill="#ffa657"/>
      <rect x="24" y="60" width="30" height="2" rx="1" fill="#58a6ff"/>
      <!-- Cursor -->
      <rect x="56" y="60" width="2" height="7" rx="0.5" fill="#e6edf3" opacity="0.9"/>
      <!-- Stand -->
      <rect x="50" y="72" width="10" height="5" rx="1" fill="#30363d"/>
      <rect x="40" y="77" width="30" height="3" rx="1" fill="#30363d"/>
      <!-- Bot head above monitor -->
      <rect x="33" y="10" width="44" height="28" rx="8" fill="#1a1a3e" stroke="#58a6ff" stroke-width="0.8"/>
      <!-- Eyes -->
      <rect x="41" y="19" width="10" height="7" rx="3" fill="#0d1117"/>
      <rect x="59" y="19" width="10" height="7" rx="3" fill="#0d1117"/>
      <circle cx="46" cy="22" r="2.5" fill="#58a6ff"/>
      <circle cx="64" cy="22" r="2.5" fill="#58a6ff"/>
      <!-- Pupil glow -->
      <circle cx="47" cy="21" r="1" fill="#a5d6ff"/>
      <circle cx="65" cy="21" r="1" fill="#a5d6ff"/>
      <!-- Mouth -->
      <path d="M43 31 Q55 36 67 31" stroke="#58a6ff" stroke-width="1.5" fill="none" stroke-linecap="round"/>
      <!-- Antenna -->
      <line x1="55" y1="10" x2="55" y2="4" stroke="#58a6ff" stroke-width="1.5"/>
      <circle cx="55" cy="3" r="3" fill="#ffa657"/>
      <!-- Ear bolts -->
      <rect x="29" y="19" width="4" height="8" rx="2" fill="#30363d" stroke="#58a6ff" stroke-width="0.5"/>
      <rect x="77" y="19" width="4" height="8" rx="2" fill="#30363d" stroke="#58a6ff" stroke-width="0.5"/>
      <!-- Coffee cup -->
      <rect x="77" y="60" width="14" height="11" rx="2" fill="#6f4e37" stroke="#a0724f" stroke-width="0.8"/>
      <path d="M91 63 Q97 63 97 68 Q97 73 91 73" stroke="#a0724f" stroke-width="1.2" fill="none" stroke-linecap="round"/>
      <rect x="78" y="60" width="12" height="3" rx="1" fill="#c8a97e" opacity="0.5"/>
      <path d="M81 58 Q82 55 81 52" stroke="#8b949e" stroke-width="0.8" fill="none" stroke-linecap="round" opacity="0.7"/>
      <path d="M85 58 Q87 54 85 51" stroke="#8b949e" stroke-width="0.8" fill="none" stroke-linecap="round" opacity="0.7"/>
      <!-- Puppy -->
      <ellipse cx="13" cy="86" rx="9" ry="6" fill="#c8a97e"/>
      <ellipse cx="12" cy="80" rx="6" ry="5" fill="#c8a97e"/>
      <ellipse cx="8" cy="79" rx="3" ry="4" fill="#a08060"/>
      <ellipse cx="16" cy="79" rx="3" ry="4" fill="#a08060"/>
      <circle cx="11" cy="82" r="1.5" fill="#3d2c1e"/>
      <circle cx="14" cy="82" r="1.5" fill="#3d2c1e"/>
      <ellipse cx="12.5" cy="85" rx="2" ry="1.2" fill="#a08060"/>
      <path d="M22 85 Q28 80 24 88" stroke="#c8a97e" stroke-width="2.5" fill="none" stroke-linecap="round"/>
    </svg>

    <div class="hero-right">
      <h1>Patrick Shema Manirumva</h1>
      <div class="handle">@vary-dev</div>
      <p class="hero-desc">Full-Stack Web &amp; App Developer from Rwanda. Building interactive, SEO-optimized, and visually stunning web and mobile applications — with coffee, a puppy, and a lot of passion.</p>
      <div class="pill-row">
        <span class="pill green"><i class="ti ti-map-pin"></i> Rwanda</span>
        <span class="pill blue"><i class="ti ti-code"></i> Full-Stack Dev</span>
        <span class="pill purple"><i class="ti ti-device-mobile"></i> Mobile Dev</span>
        <span class="pill amber"><i class="ti ti-robot"></i> AI &amp; ML</span>
      </div>
    </div>
  </div>

  <!-- ── STATS ── -->
  <div class="stats-row">
    <div class="stat-card">
      <i class="ti ti-briefcase stat-icon" style="color:#58a6ff"></i>
      <span class="stat-val">3+</span>
      <span class="stat-label">Years experience</span>
    </div>
    <div class="stat-card">
      <i class="ti ti-stack stat-icon" style="color:#3fb950"></i>
      <span class="stat-val">Full-Stack</span>
      <span class="stat-label">Web &amp; Mobile</span>
    </div>
    <div class="stat-card">
      <i class="ti ti-world stat-icon" style="color:#d2a8ff"></i>
      <span class="stat-val">SEO</span>
      <span class="stat-label">Optimized builds</span>
    </div>
  </div>

  <!-- ── TECH STACK ── -->
  <div class="card-full">
    <div class="card-title">
      <i class="ti ti-cpu" style="color:#58a6ff"></i> Tech stack
    </div>

    <!-- Languages -->
    <div class="skill-group">
      <div class="skill-group-label">Languages</div>
      <div class="skill-icons">
        <!-- HTML5 -->
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><path d="M4 2l2.4 26.8L16 31l9.6-2.2L28 2H4z" fill="#E44D26"/><path d="M16 29l7.8-2.2L25.8 5H16v24z" fill="#F16529"/><path d="M11.2 11H16V7.8H7.8L8.6 17H16v-3.2H12l-.8-6.8zm.6 10l.2 2L16 24.4v-3.4l-4.2-1z" fill="#EBEBEB"/><path d="M16 11v3.2h3.6L19 17H16v3.2h3l-.4 4.6L16 26v3.4l4.4-1.2.2-3.2.6-7H16z" fill="#fff"/></svg>
          <span>HTML5</span>
        </div>
        <!-- CSS3 -->
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><path d="M4 2l2.4 26.8L16 31l9.6-2.2L28 2H4z" fill="#1572B6"/><path d="M16 29l7.8-2.2L25.8 5H16v24z" fill="#33A9DC"/><path d="M11.2 7.8H16V11H8.4l.6 3H16v3.2H12.2l.4 3 3.4.8v3.4l-4.2-1.2-.6-6.6H8L9 29.2 16 31V7.8z" fill="#fff"/><path d="M16 7.8v3.2h7.2l-.4 3H16v3.2h6.2l-.6 6-5.6 1.4v3.4l5.8-1.4 1.6-15H16z" fill="#EBEBEB"/></svg>
          <span>CSS3</span>
        </div>
        <!-- JavaScript -->
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#F7DF1E"/><path d="M10 25.4c.6 1 1.4 1.8 2.8 1.8 1.4 0 2.4-.7 2.4-2.4V14.2h-2.8v10.4c0 .6-.2.8-.6.8-.4 0-.8-.4-1-.8L10 25.4zm8-.2c.8 1.4 2 2 3.8 2 1.8 0 3.2-.9 3.2-2.8 0-1.6-1-2.4-2.6-3l-.8-.4c-.8-.4-1.2-.6-1.2-1.2 0-.5.4-.9 1-.9.6 0 1 .3 1.4.9l2-1.2c-.8-1.4-2-1.9-3.4-1.9-2.1 0-3.4 1.3-3.4 3 0 1.6.9 2.4 2.4 3l.8.3c.9.4 1.4.7 1.4 1.4 0 .6-.5 1.1-1.4 1.1-.9 0-1.6-.5-2-1.4L18 25.2z"/></svg>
          <span>JavaScript</span>
        </div>
        <!-- Python -->
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><path d="M15.9 2C10.5 2 10.8 4.3 10.8 4.3V7h5.2v1H7.5S4 7.6 4 13.1s3 5.6 3 5.6H9v-2.7s-.1-3 3-3h5.1s2.8.1 2.8-2.7V4.8S20.4 2 15.9 2zm-.3 1.7c.5 0 .9.4.9.9s-.4.9-.9.9-.9-.4-.9-.9.4-.9.9-.9z" fill="#3776AB"/><path d="M16.1 30c5.4 0 5.1-2.3 5.1-2.3V25h-5.2v-1h8.5s3.5.4 3.5-5.1-3-5.6-3-5.6H23v2.7s.1 3-3 3h-5.1s-2.8-.1-2.8 2.7v4.5S11.6 30 16.1 30zm.3-1.7c-.5 0-.9-.4-.9-.9s.4-.9.9-.9.9.4.9.9-.4.9-.9.9z" fill="#FFD43B"/></svg>
          <span>Python</span>
        </div>
        <!-- Tailwind CSS - using SVG wordmark -->
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32" fill="none"><path d="M9 13.2c.8-3.2 2.8-4.8 6-4.8 4.8 0 5.4 3.6 7.8 4.2 1.6.4 3-.2 4.2-1.8-.8 3.2-2.8 4.8-6 4.8-4.8 0-5.4-3.6-7.8-4.2-1.6-.4-3 .2-4.2 1.8zm-6 7.2c.8-3.2 2.8-4.8 6-4.8 4.8 0 5.4 3.6 7.8 4.2 1.6.4 3-.2 4.2-1.8-.8 3.2-2.8 4.8-6 4.8-4.8 0-5.4-3.6-7.8-4.2-1.6-.4-3 .2-4.2 1.8z" fill="#38BDF8"/></svg>
          <span>Tailwind</span>
        </div>
        <!-- TypeScript -->
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#3178C6"/><path d="M9 17h5v-2H4v2h5v10h2V17H9zm9 8.4c.4.4 1 .8 1.8 1 .8.3 1.7.4 2.7.4 1 0 2-.2 2.8-.5.8-.4 1.5-.9 2-1.6.5-.7.7-1.5.7-2.5 0-.8-.2-1.5-.5-2-.3-.5-.7-1-1.3-1.3-.5-.4-1.3-.7-2.2-1l-1-.4c-.6-.2-1-.4-1.3-.7-.3-.3-.4-.6-.4-.9 0-.4.1-.7.4-1 .3-.3.7-.4 1.2-.4.5 0 .9.1 1.2.3.3.2.5.5.7.9l2.1-1c-.4-.9-1-1.6-1.8-2-.8-.4-1.7-.6-2.7-.6-1 0-1.8.2-2.6.6-.7.4-1.3.9-1.7 1.6-.4.7-.6 1.4-.6 2.2 0 1.2.3 2.1 1 2.8.7.7 1.7 1.3 3 1.7l1 .3c.8.3 1.3.5 1.6.8.3.3.5.6.5 1 0 .5-.2.8-.5 1.1-.3.3-.8.4-1.4.4-.6 0-1.2-.2-1.6-.5-.4-.3-.7-.8-.9-1.4L17 25.4c.3.7.7 1.3 1 1.8 0 0 0 0 0 0z" fill="white"/></svg>
          <span>TypeScript</span>
        </div>
      </div>
    </div>

    <!-- Frameworks & Libraries -->
    <div class="skill-group">
      <div class="skill-group-label">Frameworks &amp; libraries</div>
      <div class="skill-icons">
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><circle cx="16" cy="16" r="3" fill="#61DAFB"/><path d="M16 9.6c4.3 0 8.3.7 11.2 1.9 3.4 1.4 5.3 3.4 5.3 5.5 0 2.2-2 4.3-5.6 5.7C23.9 24 20 24.7 16 24.7c-4 0-8-.7-10.9-2-3.6-1.4-5.6-3.5-5.6-5.7 0-2.1 1.9-4.1 5.3-5.5C7.7 10.3 11.7 9.6 16 9.6zm0-1.6C7.2 8 1 11.6 1 16c0 4.4 6.2 8 15 8s15-3.6 15-8c0-4.4-6.2-8-15-8z" fill="#61DAFB"/><path d="M9.8 12.8c2.1-3.7 5-6.5 7.6-7.9 3-1.7 5.7-1.6 7 .4 1.3 2.1.4 5.5-2.3 8.8-2.2 2.7-5.2 4.9-8 5.6-3.2.8-5.7-.1-6.9-2.2-1.2-2-.8-5.4 2.6-4.7zm13.4 7.6c-2.2 3.7-5 6.5-7.6 7.9-3 1.7-5.7 1.6-7-.4-1.3-2.1-.4-5.5 2.3-8.8 2.2-2.7 5.2-4.9 8-5.6 3.2-.8 5.7.1 6.9 2.2.7 1.2.6 3.1-.6 4.7z" fill="#61DAFB"/></svg>
          <span>React</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" fill="black" rx="3"/><path d="M17 18.5l4 6.5h4.5L20 17l5.5-8H21l-4 6.3V3h-4v26h4V18.5z" fill="white"/></svg>
          <span>Next.js</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><path d="M16 1.8L1.5 9.6v12.8L16 30.2l14.5-7.8V9.6L16 1.8zm0 3.3l10.5 5.7v11.4L16 28l-10.5-5.8V10.8L16 5.1z" fill="#7952B3"/><path d="M16 8.5l-5.5 3v6l5.5 3 5.5-3v-6L16 8.5zm0 2.5l3 1.7v3.3L16 17.7l-3-1.7v-3.3L16 11z" fill="#7952B3"/></svg>
          <span>Bootstrap</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><path d="M4 28L12 4h4L8 28H4zm12 0l8-24h4L20 28h-4z" fill="#61DAFB"/><circle cx="24" cy="16" r="3" fill="#61DAFB"/></svg>
          <span>React Native</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><path d="M13.9 2.4L2 21.6C2 21.6 8 30 16 30c8 0 14-8.4 14-8.4L18.1 2.4C17.3 1 14.7 1 13.9 2.4z" fill="#42A5F5"/><path d="M16 5.2L7.3 20.4c-.2.4 0 .8.3 1L16 26.8l8.4-5.4c.3-.2.5-.6.3-1L16 5.2z" fill="#0D47A1"/><path d="M16 9.8l-6.3 10.9c-.2.3 0 .6.3.8L16 25l6-3.5c.3-.2.5-.5.3-.8L16 9.8z" fill="#42A5F5"/></svg>
          <span>Flutter</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#1a1a1a"/><path d="M7 7h6v6H7V7zm6 6h6v6h-6v-6zm6-6h6v6h-6V7zm-6 12h6v6h-6v-6zm-6 0h6v6H7v-6z" fill="#61DAFB" opacity="0.15"/><path d="M7 9h4v4H7V9zm5 0h4v4h-4V9zm5 0h4v4h-4V9zm2.5 8c0-2.2-1.8-4-4-4s-4 1.8-4 4 1.8 4 4 4 4-1.8 4-4zm-4 6c-2.2 0-4 1.8-4 4h8c0-2.2-1.8-4-4-4z" fill="#61DAFB"/></svg>
          <span>Express</span>
        </div>
      </div>
    </div>

    <!-- AI / ML / Data -->
    <div class="skill-group">
      <div class="skill-group-label">AI · ML · Data visualization</div>
      <div class="skill-icons">
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><path d="M16 3C8.8 3 3 8.8 3 16s5.8 13 13 13 13-5.8 13-13S23.2 3 16 3zm0 2c1.7 0 3.3.4 4.7 1L6 20.7C4.4 18.9 3.5 16.6 3.5 14c0-6.9 5.6-12.5 12.5-12.5zm0 21c-6.9 0-12.5-5.6-12.5-12.5 0-2.6.8-5 2.2-6.9L21.7 21c-1.7 1.3-3.6 2-5.7 2z" fill="#EE4C2C"/></svg>
          <span>PyTorch</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><path d="M16 3l-1.5 1.5L11 8l-1.5 1.5L8 11l-1.5 1.5L5 14v4l1.5 1.5L8 21l1.5 1.5L11 24l1.5 1.5L14 27h4l1.5-1.5L21 24l1.5-1.5L24 21l1.5-1.5L27 18v-4l-1.5-1.5L24 11l-1.5-1.5L21 8l-1.5-1.5L18 5z" fill="none" stroke="#FF6F00" stroke-width="2"/><path d="M16 9a7 7 0 100 14A7 7 0 0016 9zm0 3a4 4 0 110 8 4 4 0 010-8z" fill="#FF6F00"/></svg>
          <span>TensorFlow</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#11557C"/><path d="M6 23V9h2.5l7.5 11V9H18v14h-2.5L8 12v11H6zm13-7c0-4 2.7-7 7-7v2c-2.8 0-4.7 2-4.7 5s1.9 5 4.7 5v2c-4.3 0-7-3-7-7z" fill="#E8C547"/></svg>
          <span>Matplotlib</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#150458"/><path d="M8 7h16v2H8V7zm0 4h10v2H8v-2zm0 4h16v2H8v-2zm0 4h10v2H8v-2zm0 4h16v2H8v-2z" fill="white" opacity="0.3"/><path d="M5 8l9 8-9 8" fill="none" stroke="#E70488" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
          <span>Pandas</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#4C78A8"/><circle cx="8" cy="24" r="2" fill="white"/><circle cx="14" cy="16" r="2" fill="white"/><circle cx="20" cy="12" r="2" fill="white"/><circle cx="26" cy="8" r="2" fill="white"/><path d="M8 24l6-8 6-4 6-4" stroke="white" stroke-width="1.5" fill="none" opacity="0.6"/></svg>
          <span>Vega-Altair</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#F0772A"/><path d="M6 26V16l5-5 4 6 4-10 7 19H6z" fill="white"/></svg>
          <span>Seaborn</span>
        </div>
      </div>
    </div>

    <!-- Databases -->
    <div class="skill-group">
      <div class="skill-group-label">Databases</div>
      <div class="skill-icons">
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><ellipse cx="16" cy="8" rx="12" ry="4" fill="#4DB33D"/><path d="M4 8v6c0 2.2 5.4 4 12 4s12-1.8 12-4V8c0 2.2-5.4 4-12 4S4 10.2 4 8z" fill="#3FA333"/><path d="M4 14v6c0 2.2 5.4 4 12 4s12-1.8 12-4v-6c0 2.2-5.4 4-12 4S4 16.2 4 14z" fill="#4DB33D"/><path d="M4 20v4c0 2.2 5.4 4 12 4s12-1.8 12-4v-4c0 2.2-5.4 4-12 4S4 22.2 4 20z" fill="#3FA333"/></svg>
          <span>MongoDB</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><path d="M16 3C9.4 3 4 5.2 4 8v16c0 2.8 5.4 5 12 5s12-2.2 12-5V8c0-2.8-5.4-5-12-5zm0 2c5.5 0 10 1.8 10 3s-4.5 3-10 3S6 9.2 6 8s4.5-3 10-3zM6 11.4c2.1 1 5.7 1.6 10 1.6s7.9-.6 10-1.6V14c0 1.2-4.5 3-10 3S6 15.2 6 14v-2.6zm0 6c2.1 1 5.7 1.6 10 1.6s7.9-.6 10-1.6V20c0 1.2-4.5 3-10 3S6 21.2 6 20v-2.6zm0 6c2.1 1 5.7 1.6 10 1.6s7.9-.6 10-1.6V26c0 1.2-4.5 3-10 3S6 27.2 6 26v-2.6z" fill="#00758F"/></svg>
          <span>MySQL</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><path d="M16 3C9.4 3 4 5.2 4 8v16c0 2.8 5.4 5 12 5s12-2.2 12-5V8c0-2.8-5.4-5-12-5z" fill="#336791"/><ellipse cx="16" cy="8" rx="12" ry="5" fill="#4a90d9"/><path d="M4 13.5c0 2.8 5.4 5 12 5s12-2.2 12-5" stroke="#4a90d9" stroke-width="0.5" fill="none"/><path d="M4 19c0 2.8 5.4 5 12 5s12-2.2 12-5" stroke="#4a90d9" stroke-width="0.5" fill="none"/><circle cx="22" cy="8" r="2" fill="white" opacity="0.5"/></svg>
          <span>PostgreSQL</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><path d="M5.7 2.5L2 8.8l14 20.7 14-20.7L26.3 2.5H5.7z" fill="#FFCA28"/><path d="M2 8.8h12V29.5L2 8.8z" fill="#F57F17"/><path d="M18 8.8h12L16 29.5V8.8z" fill="#F57F17"/><path d="M2 8.8h28L20 3.5H12L2 8.8z" fill="#FFCA28" opacity="0.7"/></svg>
          <span>Firebase</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#3ECF8E"/><path d="M9 21l4-8 4 5 3-4 5 7H9zm3-10a2 2 0 100-4 2 2 0 000 4z" fill="white"/></svg>
          <span>Supabase</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#003B57"/><path d="M7 10h18v2H7v-2zm0 5h18v2H7v-2zm0 5h12v2H7v-2z" fill="white"/><circle cx="24" cy="22" r="4" fill="#0F97C7"/></svg>
          <span>SQLite</span>
        </div>
      </div>
    </div>

    <!-- Cloud & Hosting -->
    <div class="skill-group">
      <div class="skill-group-label">Cloud &amp; hosting</div>
      <div class="skill-icons">
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><path d="M24 14a8 8 0 00-15.7-2A6 6 0 008 24h16a6 6 0 000-12z" fill="#00AD9F"/><path d="M24 14a8 8 0 00-15.7-2" fill="none" stroke="#00AD9F" stroke-width="0.5"/></svg>
          <span>Netlify</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#000000"/><path d="M16 5l-3 9h-7l6 4-2 9 6-4 6 4-2-9 6-4h-7L16 5z" fill="white"/></svg>
          <span>Vercel</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><path d="M16 4L4 10v12l12 6 12-6V10L16 4zm0 2.3l9.3 4.7-9.3 4.7-9.3-4.7L16 6.3zm-10 6.6l9 4.5V27l-9-4.5V12.9zm11 14.1V17.4l9-4.5v9.6l-9 4.5z" fill="#0DB7ED"/></svg>
          <span>Docker</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#FF9900"/><path d="M8 18c0 1.7 3.6 3 8 3s8-1.3 8-3" stroke="white" stroke-width="1.5" fill="none"/><path d="M24 18v3c0 1.7-3.6 3-8 3s-8-1.3-8-3v-3" stroke="white" stroke-width="1.5" fill="none"/><ellipse cx="16" cy="15" rx="8" ry="3" fill="white" opacity="0.9"/></svg>
          <span>AWS</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><circle cx="16" cy="16" r="12" fill="#F05032"/><path d="M16 6v12M16 18l-5-5M16 18l5-5" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
          <span>Git</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#181717"/><path d="M16 4C9.4 4 4 9.4 4 16c0 5.3 3.4 9.8 8.2 11.4.6.1.8-.3.8-.6v-2.2c-3.3.7-4-1.6-4-1.6-.5-1.4-1.3-1.8-1.3-1.8-1.1-.7.1-.7.1-.7 1.2.1 1.8 1.2 1.8 1.2 1.1 1.8 2.8 1.3 3.5 1 .1-.8.4-1.3.7-1.6-2.7-.3-5.5-1.3-5.5-5.9 0-1.3.5-2.4 1.2-3.2-.1-.3-.5-1.5.1-3.2 0 0 1-.3 3.3 1.2a11.5 11.5 0 016 0c2.3-1.5 3.3-1.2 3.3-1.2.6 1.7.2 2.9.1 3.2.8.8 1.2 1.9 1.2 3.2 0 4.6-2.8 5.6-5.5 5.9.4.4.8 1.1.8 2.2v3.3c0 .3.2.7.8.6A12 12 0 0028 16c0-6.6-5.4-12-12-12z" fill="white"/></svg>
          <span>GitHub</span>
        </div>
      </div>
    </div>

    <!-- Server Administration -->
    <div class="skill-group">
      <div class="skill-group-label">Server administration</div>
      <div class="skill-icons">
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#0078D4"/><path d="M4 8h24v5H4V8zm0 11h24v5H4v-5zm2 2h4v1H6v-1zm0-11h4v1H6V9zm8 11h4v1h-4v-1zm0-11h4v1h-4V9zm8 11h4v1h-4v-1zm0-11h4v1h-4V9zm-5 5a3 3 0 100 6 3 3 0 000-6z" fill="white"/></svg>
          <span>Windows Server</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><circle cx="16" cy="16" r="12" fill="#FCC624"/><circle cx="16" cy="16" r="8" fill="#1a1a1a"/><circle cx="16" cy="16" r="4" fill="#FCC624"/></svg>
          <span>Linux</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#4EAA25"/><path d="M6 12h20v8H6v-8zm2 2v4h16v-4H8zm0 1h4v2H8v-2zm6 0h4v2h-4v-2zm6 0h2v2h-2v-2z" fill="white"/><path d="M9 10V8h2v2H9zm4 0V8h2v2h-2zm4 0V8h2v2h-2z" fill="white" opacity="0.5"/></svg>
          <span>Nginx</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#E8612C"/><path d="M6 8h20v5H6V8zm0 11h20v5H6v-5zm10-5.5a2.5 2.5 0 110 5 2.5 2.5 0 010-5z" fill="white" opacity="0.9"/></svg>
          <span>Apache</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#2C3E50"/><rect x="6" y="8" width="20" height="3" rx="1" fill="#3498DB"/><rect x="6" y="13" width="20" height="3" rx="1" fill="#2ECC71"/><rect x="6" y="18" width="14" height="3" rx="1" fill="#E74C3C"/><rect x="6" y="23" width="18" height="3" rx="1" fill="#95A5A6"/></svg>
          <span>SSH / CLI</span>
        </div>
      </div>
    </div>

    <!-- Design Tools -->
    <div class="skill-group">
      <div class="skill-group-label">Design tools</div>
      <div class="skill-icons">
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><path d="M10 4h12v8H10z" fill="#F24E1E"/><path d="M4 16a6 6 0 016-6h4v12H10a6 6 0 01-6-6z" fill="#FF7262"/><path d="M10 22h6a6 6 0 010 12h-6v-12z" fill="#A259FF"/><path d="M22 4h6a6 6 0 010 12h-6V4z" fill="#1ABCFE"/><path d="M22 16a6 6 0 110 12V16z" fill="#0ACF83"/></svg>
          <span>Figma</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#7D2AE7"/><path d="M8 8h16v2H8V8zm0 5h11v2H8v-2zm0 5h16v2H8v-2zm0 5h11v2H8v-2z" fill="white" opacity="0.5"/><path d="M22 17a5 5 0 11-10 0 5 5 0 0110 0zm-5-3l-2.5 4.5h5L17 14z" fill="white"/></svg>
          <span>Canva</span>
        </div>
        <div class="skill-icon">
          <svg class="si-svg" viewBox="0 0 32 32"><rect width="32" height="32" rx="3" fill="#001E36"/><rect x="6" y="6" width="20" height="20" rx="2" fill="#31A8FF"/><path d="M10 22l8-16 8 16H10zm8-13l-5 10h10l-5-10z" fill="white" opacity="0.9"/></svg>
          <span>Photoshop</span>
        </div>
      </div>
    </div>
  </div>

  <!-- ── ABOUT + CONNECT ROW ── -->
  <div class="grid-2">
    <!-- About -->
    <div class="card">
      <div class="card-title">
        <i class="ti ti-user" style="color:#d2a8ff"></i> About me
      </div>
      <ul class="about-list">
        <li>
          <i class="ti ti-device-desktop-code" style="color:#58a6ff"></i>
          Building <strong>dynamic websites, React apps, admin dashboards, and e-commerce platforms</strong>.
        </li>
        <li>
          <i class="ti ti-seedling" style="color:#3fb950"></i>
          Exploring <strong>Next.js, Flutter, Firebase, and AI tools</strong> actively.
        </li>
        <li>
          <i class="ti ti-palette" style="color:#ffa657"></i>
          Passionate about <strong>UI/UX design</strong> and digital storytelling.
        </li>
        <li>
          <i class="ti ti-search" style="color:#58a6ff"></i>
          Skilled in <strong>Google SEO, Maps integration, and AI model training</strong>.
        </li>
        <li>
          <i class="ti ti-server" style="color:#d2a8ff"></i>
          Managing <strong>Linux and Windows servers</strong>, cloud deployments.
        </li>
        <li>
          <i class="ti ti-users" style="color:#3fb950"></i>
          Open to <strong>collaborating on real-world projects</strong>.
        </li>
      </ul>
    </div>

    <!-- Connect -->
    <div class="card">
      <div class="card-title">
        <i class="ti ti-antenna-bars-5" style="color:#3fb950"></i> Connect
      </div>
      <div style="display:flex;flex-direction:column;gap:9px;">
        <a class="connect-btn" href="https://varydeveloper.netlify.app/" target="_blank" rel="noopener noreferrer">
          <i class="ti ti-world" style="color:#58a6ff"></i>
          <span>varydeveloper.netlify.app</span>
          <i class="ti ti-arrow-up-right ext"></i>
        </a>
        <a class="connect-btn" href="https://github.com/vary-dev" target="_blank" rel="noopener noreferrer">
          <i class="ti ti-brand-github" style="color:#e6edf3"></i>
          <span>github.com/vary-dev</span>
          <i class="ti ti-arrow-up-right ext"></i>
        </a>
        <a class="connect-btn" href="https://www.instagram.com/vary_dev" target="_blank" rel="noopener noreferrer">
          <i class="ti ti-brand-instagram" style="color:#E1306C"></i>
          <span>instagram.com/vary_dev</span>
          <i class="ti ti-arrow-up-right ext"></i>
        </a>
        <a class="connect-btn" href="https://www.linkedin.com/in/vary-001" target="_blank" rel="noopener noreferrer">
          <i class="ti ti-brand-linkedin" style="color:#0A66C2"></i>
          <span>linkedin.com/in/vary-001</span>
          <i class="ti ti-arrow-up-right ext"></i>
        </a>
        <a class="connect-btn" href="https://www.youtube.com/@vary-dev" target="_blank" rel="noopener noreferrer">
          <i class="ti ti-brand-youtube" style="color:#FF0000"></i>
          <span>youtube.com/@vary-dev</span>
          <i class="ti ti-arrow-up-right ext"></i>
        </a>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <div class="footer">
    <span style="color:var(--accent)">vary-dev</span> &nbsp;·&nbsp; Rwanda &nbsp;·&nbsp; Full-Stack Developer &nbsp;·&nbsp; <span style="color:var(--accent2)">open to work</span>
  </div>

</div>
</body>
</html># README.md
