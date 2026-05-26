# Hi, I'm Nitin Kumar

<p>
  Developer focused on building useful AI, web, and full-stack projects.
</p>

<p>
  <a href="[https://www.linkedin.com/in/YOUR-LINKEDIN/](https://www.linkedin.com/in/nitin-kumar-882743280/)">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:nitinkumar18ad@gmail">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nitinkumar18ad&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" height="170" alt="GitHub stats" />
  <img src="https://streak-stats.demolab.com?user=nitinkumar18ad&theme=tokyonight&hide_border=true" height="170" alt="GitHub streak stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nitinkumar18ad&layout=compact&theme=tokyonight&hide_border=true" height="170" alt="Top languages" />
</p>

---

## Skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,javascript,react,nodejs,express,mongodb,mysql,git,github,vscode&theme=dark" alt="Skills" />
</p>

---

## ANI

<p align="center">
  <img src="./pet.gif" alt="GitPet companion" width="420" />
</p>

<p align="center">
  Animated companion from my GitPet project.
</p>

---

## Featured Work

- [AI-HealthCare](https://github.com/nitinkumar18ad/AI-HealthCare)
- [AI-Skin-Disease-Detector](https://github.com/nitinkumar18ad/AI-Skin-Disease-Detector)
- [Password-Manager](https://github.com/nitinkumar18ad/Password-Manager)

---

## Currently Working On

- Building practical AI and full-stack applications
- Improving GitHub profile presence and project quality
- Learning better deployment and production workflows



- (https://www.linkedin.com/in/nitin-kumar-882743280/)
- nitinkumar18ad@gmail.com with your real email




<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nitinkumar18ad&show_icons=true&theme=tokyonight&hide_border=true" height="170" />
  <img src="https://streak-stats.demolab.com?user=nitinkumar18ad&theme=tokyonight&hide_border=true" height="170" />
</p>

## Skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,js,react,nodejs,express,mongodb,mysql,git,github,vscode&theme=dark" />
</p>

## My GitPet

<p align="center">
  <img src="./pet.gif" alt="GitPet companion" width="420" />
</p>







<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Nitin Kumar — GitHub Profile README</title>
<link href="https://fonts.googleapis.com/css2?family=Space+Mono:ital,wght@0,400;0,700;1,400&family=Syne:wght@400;600;700;800&display=swap" rel="stylesheet"/>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg: #0d0f14;
    --bg2: #13161e;
    --bg3: #1a1e2a;
    --border: rgba(100,120,200,0.18);
    --accent: #5b8af5;
    --accent2: #a78bfa;
    --accent3: #34d399;
    --text: #e8ecf4;
    --muted: #7a83a0;
    --glow: rgba(91,138,245,0.15);
  }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Syne', sans-serif;
    min-height: 100vh;
    overflow-x: hidden;
  }

  /* ── GRID BACKGROUND ── */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image:
      linear-gradient(rgba(91,138,245,0.04) 1px, transparent 1px),
      linear-gradient(90deg, rgba(91,138,245,0.04) 1px, transparent 1px);
    background-size: 48px 48px;
    pointer-events: none;
    z-index: 0;
  }

  /* ── FLOATING ORBS ── */
  .orb {
    position: fixed;
    border-radius: 50%;
    filter: blur(90px);
    opacity: 0.18;
    pointer-events: none;
    z-index: 0;
    animation: drift 18s ease-in-out infinite;
  }
  .orb1 { width: 420px; height: 420px; background: #5b8af5; top: -80px; left: -100px; animation-delay: 0s; }
  .orb2 { width: 320px; height: 320px; background: #a78bfa; bottom: 10%; right: -80px; animation-delay: -6s; }
  .orb3 { width: 260px; height: 260px; background: #34d399; bottom: 30%; left: 20%; animation-delay: -12s; }

  @keyframes drift {
    0%, 100% { transform: translate(0, 0) scale(1); }
    33%       { transform: translate(30px, -20px) scale(1.05); }
    66%       { transform: translate(-20px, 25px) scale(0.97); }
  }

  /* ── WRAPPER ── */
  .wrapper {
    position: relative;
    z-index: 1;
    max-width: 780px;
    margin: 0 auto;
    padding: 3rem 2rem 5rem;
  }

  /* ── HERO ── */
  .hero {
    text-align: center;
    padding: 3rem 0 2rem;
    opacity: 0;
    transform: translateY(30px);
    animation: fadeUp 0.8s 0.1s forwards;
  }

  .greeting {
    font-family: 'Space Mono', monospace;
    font-size: 0.85rem;
    color: var(--accent);
    letter-spacing: 0.2em;
    text-transform: uppercase;
    margin-bottom: 1rem;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 0.5rem;
  }
  .greeting::before, .greeting::after {
    content: '';
    height: 1px;
    width: 40px;
    background: linear-gradient(90deg, transparent, var(--accent));
  }
  .greeting::after { background: linear-gradient(90deg, var(--accent), transparent); }

  h1 {
    font-size: clamp(2.4rem, 6vw, 4rem);
    font-weight: 800;
    line-height: 1.1;
    background: linear-gradient(135deg, #e8ecf4 30%, var(--accent) 60%, var(--accent2) 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    margin-bottom: 1rem;
  }

  .tagline {
    font-size: 1.05rem;
    color: var(--muted);
    max-width: 440px;
    margin: 0 auto 2rem;
    line-height: 1.7;
  }

  /* ── TYPING CURSOR ── */
  .typed-wrap {
    font-family: 'Space Mono', monospace;
    font-size: 0.9rem;
    color: var(--accent3);
    margin-bottom: 2.5rem;
    height: 1.5em;
  }
  .cursor {
    display: inline-block;
    width: 2px;
    height: 1em;
    background: var(--accent3);
    margin-left: 2px;
    vertical-align: middle;
    animation: blink 1s step-end infinite;
  }
  @keyframes blink { 50% { opacity: 0; } }

  /* ── SOCIAL BUTTONS ── */
  .socials {
    display: flex;
    gap: 0.75rem;
    justify-content: center;
    flex-wrap: wrap;
    margin-bottom: 1rem;
  }
  .btn {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    padding: 0.55rem 1.2rem;
    border-radius: 8px;
    font-family: 'Space Mono', monospace;
    font-size: 0.75rem;
    font-weight: 700;
    text-decoration: none;
    letter-spacing: 0.05em;
    transition: transform 0.2s, box-shadow 0.2s;
    border: 1px solid;
    cursor: pointer;
  }
  .btn-linkedin { background: rgba(0,119,181,0.15); border-color: rgba(0,119,181,0.5); color: #5aabf5; }
  .btn-gmail    { background: rgba(209,72,54,0.12);  border-color: rgba(209,72,54,0.4);  color: #f87171; }
  .btn-github   { background: rgba(255,255,255,0.06); border-color: rgba(255,255,255,0.15); color: #c9d1d9; }
  .btn:hover    { transform: translateY(-3px); box-shadow: 0 8px 24px rgba(0,0,0,0.3); }

  /* ── SECTION HEADERS ── */
  .section {
    margin-top: 3.5rem;
    opacity: 0;
    transform: translateY(24px);
  }
  .section.visible {
    animation: fadeUp 0.7s forwards;
  }

  .section-label {
    display: flex;
    align-items: center;
    gap: 0.75rem;
    font-family: 'Space Mono', monospace;
    font-size: 0.72rem;
    color: var(--accent);
    letter-spacing: 0.2em;
    text-transform: uppercase;
    margin-bottom: 1.5rem;
  }
  .section-label::after {
    content: '';
    flex: 1;
    height: 1px;
    background: linear-gradient(90deg, var(--border), transparent);
  }

  /* ── STATS GRID ── */
  .stats-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1rem;
  }
  .stat-card {
    background: var(--bg2);
    border: 1px solid var(--border);
    border-radius: 12px;
    overflow: hidden;
    transition: border-color 0.3s, transform 0.3s;
  }
  .stat-card:hover {
    border-color: rgba(91,138,245,0.4);
    transform: translateY(-4px);
  }
  .stat-card img {
    width: 100%;
    height: auto;
    display: block;
  }

  /* ── SKILLS ── */
  .skills-wrap {
    background: var(--bg2);
    border: 1px solid var(--border);
    border-radius: 16px;
    padding: 2rem;
  }
  .skill-group { margin-bottom: 1.75rem; }
  .skill-group:last-child { margin-bottom: 0; }
  .skill-group-title {
    font-family: 'Space Mono', monospace;
    font-size: 0.7rem;
    color: var(--muted);
    letter-spacing: 0.15em;
    text-transform: uppercase;
    margin-bottom: 0.85rem;
  }
  .skill-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
  }
  .tag {
    font-family: 'Space Mono', monospace;
    font-size: 0.72rem;
    padding: 0.35rem 0.85rem;
    border-radius: 6px;
    border: 1px solid;
    transition: transform 0.2s, background 0.2s;
    cursor: default;
    animation: tagPop 0.4s backwards;
  }
  .tag:hover { transform: scale(1.07); }
  .tag-blue   { background: rgba(91,138,245,0.1);  border-color: rgba(91,138,245,0.3);  color: #93b4fa; }
  .tag-purple { background: rgba(167,139,250,0.1); border-color: rgba(167,139,250,0.3); color: #c4b5fd; }
  .tag-green  { background: rgba(52,211,153,0.1);  border-color: rgba(52,211,153,0.3);  color: #6ee7b7; }
  .tag-amber  { background: rgba(251,191,36,0.1);  border-color: rgba(251,191,36,0.3);  color: #fcd34d; }
  .tag-red    { background: rgba(248,113,113,0.1); border-color: rgba(248,113,113,0.3); color: #fca5a5; }

  @keyframes tagPop {
    from { opacity: 0; transform: scale(0.8); }
    to   { opacity: 1; transform: scale(1); }
  }

  /* ── PROJECTS ── */
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1rem;
  }
  .project-card {
    background: var(--bg2);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 1.4rem;
    text-decoration: none;
    color: inherit;
    transition: border-color 0.3s, transform 0.3s, background 0.3s;
    display: flex;
    flex-direction: column;
    gap: 0.6rem;
    position: relative;
    overflow: hidden;
  }
  .project-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, var(--accent), var(--accent2));
    opacity: 0;
    transition: opacity 0.3s;
  }
  .project-card:hover {
    border-color: rgba(91,138,245,0.4);
    transform: translateY(-5px);
    background: var(--bg3);
  }
  .project-card:hover::before { opacity: 1; }
  .project-icon {
    font-size: 1.5rem;
    margin-bottom: 0.2rem;
  }
  .project-name {
    font-size: 0.95rem;
    font-weight: 700;
    color: var(--text);
  }
  .project-desc {
    font-size: 0.8rem;
    color: var(--muted);
    line-height: 1.5;
    flex: 1;
  }
  .project-link {
    font-family: 'Space Mono', monospace;
    font-size: 0.68rem;
    color: var(--accent);
    letter-spacing: 0.05em;
    display: flex;
    align-items: center;
    gap: 0.3rem;
    margin-top: 0.4rem;
  }
  .arrow { transition: transform 0.2s; }
  .project-card:hover .arrow { transform: translateX(4px); }

  /* ── CURRENT FOCUS ── */
  .focus-list {
    display: flex;
    flex-direction: column;
    gap: 0.75rem;
  }
  .focus-item {
    display: flex;
    align-items: center;
    gap: 1rem;
    padding: 0.9rem 1.2rem;
    background: var(--bg2);
    border: 1px solid var(--border);
    border-radius: 10px;
    font-size: 0.88rem;
    transition: border-color 0.25s, transform 0.25s;
  }
  .focus-item:hover {
    border-color: rgba(52,211,153,0.35);
    transform: translateX(6px);
  }
  .focus-dot {
    width: 8px; height: 8px;
    border-radius: 50%;
    background: var(--accent3);
    flex-shrink: 0;
    box-shadow: 0 0 8px var(--accent3);
    animation: pulse 2s ease-in-out infinite;
  }
  @keyframes pulse {
    0%, 100% { box-shadow: 0 0 6px var(--accent3); transform: scale(1); }
    50%       { box-shadow: 0 0 14px var(--accent3); transform: scale(1.2); }
  }

  /* ── PET/GIF SECTION ── */
  .ani-section {
    text-align: center;
  }
  .ani-frame {
    display: inline-block;
    border: 1px solid var(--border);
    border-radius: 16px;
    overflow: hidden;
    background: var(--bg2);
    padding: 1rem;
    transition: transform 0.3s, box-shadow 0.3s;
  }
  .ani-frame:hover {
    transform: scale(1.03);
    box-shadow: 0 0 40px rgba(91,138,245,0.2);
  }
  .ani-placeholder {
    width: 320px;
    height: 200px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 0.75rem;
    color: var(--muted);
    font-family: 'Space Mono', monospace;
    font-size: 0.75rem;
  }
  .pet-emoji {
    font-size: 3rem;
    animation: bounce 1.5s ease-in-out infinite;
  }
  @keyframes bounce {
    0%, 100% { transform: translateY(0); }
    50%       { transform: translateY(-10px); }
  }

  /* ── DIVIDER ── */
  .divider {
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--border), transparent);
    margin: 3rem 0 0;
  }

  /* ── FOOTER ── */
  .footer {
    text-align: center;
    margin-top: 3rem;
    font-family: 'Space Mono', monospace;
    font-size: 0.72rem;
    color: var(--muted);
    opacity: 0;
    animation: fadeUp 0.7s 1.2s forwards;
  }
  .footer a { color: var(--accent); text-decoration: none; }

  /* ── KEYFRAMES ── */
  @keyframes fadeUp {
    to { opacity: 1; transform: translateY(0); }
  }

  /* ── SCROLL STAR DECORATIONS ── */
  .star {
    position: fixed;
    width: 2px; height: 2px;
    border-radius: 50%;
    background: white;
    opacity: 0;
    animation: twinkle 4s ease-in-out infinite;
    pointer-events: none;
    z-index: 0;
  }
  @keyframes twinkle {
    0%, 100% { opacity: 0; transform: scale(1); }
    50%       { opacity: 0.6; transform: scale(1.5); }
  }
</style>
</head>
<body>

<!-- Orbs -->
<div class="orb orb1"></div>
<div class="orb orb2"></div>
<div class="orb orb3"></div>

<!-- Stars -->
<script>
  for (let i = 0; i < 60; i++) {
    const s = document.createElement('div');
    s.className = 'star';
    s.style.left = Math.random() * 100 + 'vw';
    s.style.top  = Math.random() * 100 + 'vh';
    s.style.animationDelay = (Math.random() * 6) + 's';
    s.style.animationDuration = (3 + Math.random() * 5) + 's';
    document.body.appendChild(s);
  }
</script>

<div class="wrapper">

  <!-- ── HERO ── -->
  <div class="hero">
    <div class="greeting">
      <span>👋</span> Hey there, I'm
    </div>
    <h1>Nitin Kumar</h1>
    <p class="tagline">Developer building practical AI, web, and full-stack projects — one commit at a time.</p>
    <div class="typed-wrap">
      &gt; <span id="typed"></span><span class="cursor"></span>
    </div>
    <div class="socials">
      <a class="btn btn-github" href="https://github.com/nitinkumar18ad" target="_blank">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
        @nitinkumar18ad
      </a>
      <a class="btn btn-linkedin" href="https://www.linkedin.com/in/nitin-kumar-882743280/" target="_blank">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
        LinkedIn
      </a>
      <a class="btn btn-gmail" href="mailto:nitinkumar18ad@gmail.com">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M24 5.457v13.909c0 .904-.732 1.636-1.636 1.636h-3.819V11.73L12 16.64l-6.545-4.91v9.273H1.636A1.636 1.636 0 010 19.366V5.457c0-2.023 2.309-3.178 3.927-1.964L5.455 4.64 12 9.548l6.545-4.910 1.528-1.145C21.69 2.28 24 3.434 24 5.457z"/></svg>
        Gmail
      </a>
    </div>
  </div>

  <!-- ── GITHUB STATS ── -->
  <div class="section" id="stats">
    <div class="section-label">// github stats</div>
    <div class="stats-grid">
      <div class="stat-card">
        <img src="https://github-readme-stats.vercel.app/api?username=nitinkumar18ad&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&bg_color=13161e&title_color=5b8af5&icon_color=a78bfa&text_color=e8ecf4" alt="GitHub Stats"/>
      </div>
      <div class="stat-card">
        <img src="https://streak-stats.demolab.com?user=nitinkumar18ad&theme=tokyonight&hide_border=true&background=13161e&stroke=5b8af5&ring=a78bfa&fire=34d399&currStreakLabel=5b8af5" alt="GitHub Streak"/>
      </div>
      <div class="stat-card">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nitinkumar18ad&layout=compact&theme=tokyonight&hide_border=true&bg_color=13161e&title_color=5b8af5&text_color=e8ecf4" alt="Top Languages"/>
      </div>
    </div>
  </div>

  <!-- ── SKILLS ── -->
  <div class="section" id="skills">
    <div class="section-label">// tech stack</div>
    <div class="skills-wrap">
      <div class="skill-group">
        <div class="skill-group-title">Languages</div>
        <div class="skill-tags">
          <span class="tag tag-blue">Python</span>
          <span class="tag tag-blue">JavaScript</span>
          <span class="tag tag-blue">Java</span>
          <span class="tag tag-blue">SQL</span>
        </div>
      </div>
      <div class="skill-group">
        <div class="skill-group-title">AI / ML</div>
        <div class="skill-tags">
          <span class="tag tag-purple">LangChain</span>
          <span class="tag tag-purple">LangGraph</span>
          <span class="tag tag-purple">OpenAI API</span>
          <span class="tag tag-purple">MCP</span>
          <span class="tag tag-purple">FastAPI</span>
        </div>
      </div>
      <div class="skill-group">
        <div class="skill-group-title">Frontend</div>
        <div class="skill-tags">
          <span class="tag tag-green">React</span>
          <span class="tag tag-green">HTML / CSS</span>
          <span class="tag tag-green">Node.js</span>
          <span class="tag tag-green">Express</span>
        </div>
      </div>
      <div class="skill-group">
        <div class="skill-group-title">Data & Infra</div>
        <div class="skill-tags">
          <span class="tag tag-amber">MongoDB</span>
          <span class="tag tag-amber">MySQL</span>
          <span class="tag tag-amber">Docker</span>
          <span class="tag tag-amber">Git</span>
          <span class="tag tag-amber">GitHub</span>
          <span class="tag tag-amber">VS Code</span>
        </div>
      </div>
    </div>
  </div>

  <!-- ── PROJECTS ── -->
  <div class="section" id="projects">
    <div class="section-label">// featured work</div>
    <div class="projects-grid">
      <a class="project-card" href="https://github.com/nitinkumar18ad/AI-HealthCare" target="_blank">
        <div class="project-icon">🏥</div>
        <div class="project-name">AI-HealthCare</div>
        <div class="project-desc">AI-powered healthcare assistant using FastAPI and LLMs for smart medical query handling.</div>
        <div class="project-link">View on GitHub <span class="arrow">→</span></div>
      </a>
      <a class="project-card" href="https://github.com/nitinkumar18ad/AI-Skin-Disease-Detector" target="_blank">
        <div class="project-icon">🔬</div>
        <div class="project-name">AI Skin Disease Detector</div>
        <div class="project-desc">Computer vision model to detect and classify skin diseases from images.</div>
        <div class="project-link">View on GitHub <span class="arrow">→</span></div>
      </a>
      <a class="project-card" href="https://github.com/nitinkumar18ad/Password-Manager" target="_blank">
        <div class="project-icon">🔐</div>
        <div class="project-name">Password Manager</div>
        <div class="project-desc">Secure, encrypted password manager for safe credential storage and retrieval.</div>
        <div class="project-link">View on GitHub <span class="arrow">→</span></div>
      </a>
    </div>
  </div>

  <!-- ── ANI / GitPet ── -->
  <div class="section ani-section" id="ani">
    <div class="section-label">// my companion — ANI</div>
    <div class="ani-frame">
      <img src="./pet.gif" alt="ANI GitPet" style="width:320px;max-width:100%;display:block;border-radius:8px;"
        onerror="this.style.display='none';document.getElementById('petfallback').style.display='flex';" />
      <div class="ani-placeholder" id="petfallback" style="display:none;">
        <span class="pet-emoji">🤖</span>
        <span>ANI — GitPet Companion</span>
        <span style="color:rgba(122,131,160,0.5);font-size:0.65rem;">( place pet.gif in the same folder )</span>
      </div>
    </div>
    <p style="color:var(--muted);font-size:0.8rem;margin-top:1rem;font-family:'Space Mono',monospace;">
      animated companion from the GitPet project
    </p>
  </div>

  <!-- ── CURRENTLY WORKING ON ── -->
  <div class="section" id="focus">
    <div class="section-label">// currently working on</div>
    <div class="focus-list">
      <div class="focus-item"><div class="focus-dot"></div>Building practical AI and full-stack applications</div>
      <div class="focus-item"><div class="focus-dot"></div>Improving GitHub profile presence and project quality</div>
      <div class="focus-item"><div class="focus-dot"></div>Learning better deployment and production workflows</div>
      <div class="focus-item"><div class="focus-dot"></div>Exploring LangGraph, MCP servers, and AI agents</div>
    </div>
  </div>

  <div class="divider"></div>

  <div class="footer">
    <p>Made with ♥ by <a href="https://github.com/nitinkumar18ad">Nitin Kumar</a> &nbsp;·&nbsp; Powered by curiosity and caffeine ☕</p>
  </div>

</div>

<script>
  // ── TYPING EFFECT ──
  const phrases = [
    'building AI applications...',
    'exploring LangGraph agents...',
    'connecting the dots in code...',
    'shipping side projects...',
  ];
  let pi = 0, ci = 0, deleting = false;
  const el = document.getElementById('typed');
  function type() {
    const phrase = phrases[pi];
    if (!deleting) {
      el.textContent = phrase.slice(0, ++ci);
      if (ci === phrase.length) { deleting = true; setTimeout(type, 1800); return; }
    } else {
      el.textContent = phrase.slice(0, --ci);
      if (ci === 0) { deleting = false; pi = (pi + 1) % phrases.length; }
    }
    setTimeout(type, deleting ? 38 : 70);
  }
  setTimeout(type, 900);

  // ── SCROLL REVEAL ──
  const sections = document.querySelectorAll('.section');
  const obs = new IntersectionObserver((entries) => {
    entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('visible'); obs.unobserve(e.target); } });
  }, { threshold: 0.12 });
  sections.forEach(s => obs.observe(s));

  // ── STAGGERED TAG ANIMATION ──
  document.querySelectorAll('.tag').forEach((t, i) => {
    t.style.animationDelay = (i * 0.045) + 's';
  });
</script>
</body>
</html>
