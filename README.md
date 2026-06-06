<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>README banner directions</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,300;9..144,500&family=Archivo:wght@400;500;700;900&family=JetBrains+Mono:wght@400;500;700&display=swap" rel="stylesheet">
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { background:#fff; font-family:'Archivo',system-ui,sans-serif; color:#111; padding:32px 20px; }
  .wrap { max-width:900px; margin:0 auto; }
  .opt { margin-bottom:44px; }
  .lbl { display:flex; align-items:baseline; gap:10px; margin-bottom:12px; }
  .lbl b { font-size:18px; font-weight:700; }
  .lbl span { font-size:13px; color:#666; }
  .frame { border:1px solid #e5e5e5; border-radius:10px; overflow:hidden; }
  svg { display:block; width:100%; height:auto; }
  .note { font-size:13px; color:#777; margin-top:8px; }
  h2 { font-size:14px; letter-spacing:.08em; text-transform:uppercase; color:#999; margin-bottom:20px; }
</style>
</head>
<body>
<div class="wrap">
<h2>Pick a direction</h2>

<!-- OPTION 1: CINEMATIC -->
<div class="opt">
  <div class="lbl"><b>1 — Cinematic</b><span>dark, refined serif, quiet glow</span></div>
  <div class="frame">
    <svg viewBox="0 0 900 300" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <linearGradient id="c1bg" x1="0" y1="0" x2="1" y2="1">
          <stop offset="0" stop-color="#0a0a10"/>
          <stop offset="1" stop-color="#14141f"/>
        </linearGradient>
        <radialGradient id="c1glow" cx="0.78" cy="0.3" r="0.5">
          <stop offset="0" stop-color="#3b82f6" stop-opacity="0.22"/>
          <stop offset="1" stop-color="#3b82f6" stop-opacity="0"/>
        </radialGradient>
      </defs>
      <rect width="900" height="300" fill="url(#c1bg)"/>
      <rect width="900" height="300" fill="url(#c1glow)"/>
      <g stroke="#ffffff" stroke-opacity="0.04">
        <line x1="0" y1="75" x2="900" y2="75"/><line x1="0" y1="150" x2="900" y2="150"/><line x1="0" y1="225" x2="900" y2="225"/>
      </g>
      <text x="64" y="112" font-family="Archivo" font-size="12" letter-spacing="4" fill="#7dd3fc">BACKEND &#183; DEVOPS &#183; INFRASTRUCTURE</text>
      <text x="62" y="172" font-family="Fraunces" font-weight="300" font-size="58" fill="#f5f5f7">Surya Pratap Das</text>
      <rect x="64" y="196" width="44" height="2" fill="#3b82f6"/>
      <text x="64" y="224" font-family="Fraunces" font-weight="300" font-style="italic" font-size="20" fill="#a9adba">I build infrastructure that scales.</text>
      <text x="64" y="262" font-family="JetBrains Mono" font-size="12.5" fill="#6b7280">Node.js &#183; TypeScript &#183; Kafka &#183; Terraform &#183; AWS &#183; PostgreSQL &#183; Redis</text>
    </svg>
  </div>
  <p class="note">Hero serif name, hairline accent, near-black field with a single cool glow. Reads premium / editorial-tech.</p>
</div>

<!-- OPTION 2: EDITORIAL / SWISS -->
<div class="opt">
  <div class="lbl"><b>2 — Editorial / Swiss</b><span>bold grotesk, grid, one hot accent</span></div>
  <div class="frame">
    <svg viewBox="0 0 900 300" xmlns="http://www.w3.org/2000/svg">
      <rect width="900" height="300" fill="#f3f0e9"/>
      <rect x="0" y="0" width="14" height="300" fill="#e8542b"/>
      <g stroke="#111" stroke-opacity="0.12">
        <line x1="600" y1="0" x2="600" y2="300"/>
      </g>
      <text x="56" y="74" font-family="JetBrains Mono" font-size="12" letter-spacing="2" fill="#8a8576">01 / ENGINEER</text>
      <text x="52" y="150" font-family="Archivo" font-weight="900" font-size="68" fill="#15130e" letter-spacing="-2">SURYA PRATAP</text>
      <text x="52" y="214" font-family="Archivo" font-weight="900" font-size="68" fill="#15130e" letter-spacing="-2">DAS<tspan font-family="Archivo" font-weight="400" font-size="22" fill="#e8542b" dx="22" dy="-30">Backend &amp; DevOps</tspan></text>
      <text x="56" y="262" font-family="JetBrains Mono" font-size="12.5" fill="#55503f">Kafka &#183; Terraform &#183; AWS ECS &#183; 60&#8211;70K concurrent users</text>
      <text x="628" y="74" font-family="JetBrains Mono" font-size="11" letter-spacing="1" fill="#8a8576">BHUBANESWAR, IN</text>
      <text x="628" y="150" font-family="Archivo" font-weight="700" font-size="40" fill="#15130e">70K</text>
      <text x="628" y="172" font-family="JetBrains Mono" font-size="11" fill="#8a8576">concurrent users</text>
    </svg>
  </div>
  <p class="note">Magazine energy — oversized type, a hard accent stripe, grid index numbers. Confident and designed (very different from the plain text version).</p>
</div>

<!-- OPTION 3: TERMINAL -->
<div class="opt">
  <div class="lbl"><b>3 — Terminal</b><span>monospace, command-line, dev native</span></div>
  <div class="frame">
    <svg viewBox="0 0 900 300" xmlns="http://www.w3.org/2000/svg">
      <rect width="900" height="300" fill="#0d1117"/>
      <rect x="0" y="0" width="900" height="38" fill="#161b22"/>
      <circle cx="26" cy="19" r="6" fill="#ff5f56"/><circle cx="48" cy="19" r="6" fill="#ffbd2e"/><circle cx="70" cy="19" r="6" fill="#27c93f"/>
      <text x="450" y="23" text-anchor="middle" font-family="JetBrains Mono" font-size="12" fill="#6e7681">surya@infra: ~</text>
      <text x="28" y="86" font-family="JetBrains Mono" font-size="14" fill="#7ee787">surya@infra<tspan fill="#6e7681">:</tspan><tspan fill="#58a6ff">~</tspan><tspan fill="#6e7681">$</tspan> <tspan fill="#e6edf3">whoami</tspan></text>
      <text x="28" y="114" font-family="JetBrains Mono" font-size="14" fill="#e6edf3">Surya Pratap Das &#8212; Backend &amp; DevOps Engineer</text>
      <text x="28" y="156" font-family="JetBrains Mono" font-size="14" fill="#7ee787">surya@infra<tspan fill="#6e7681">:</tspan><tspan fill="#58a6ff">~</tspan><tspan fill="#6e7681">$</tspan> <tspan fill="#e6edf3">cat stack.txt</tspan></text>
      <text x="28" y="184" font-family="JetBrains Mono" font-size="13" fill="#8b949e">node &#183; typescript &#183; kafka &#183; terraform &#183; aws &#183; docker &#183; postgres</text>
      <text x="28" y="226" font-family="JetBrains Mono" font-size="14" fill="#7ee787">surya@infra<tspan fill="#6e7681">:</tspan><tspan fill="#58a6ff">~</tspan><tspan fill="#6e7681">$</tspan> <tspan fill="#e6edf3">scale --target=1M</tspan></text>
      <text x="28" y="254" font-family="JetBrains Mono" font-size="13" fill="#58a6ff">&#10003; reached 60&#8211;70K concurrent users in load testing<tspan fill="#7ee787" dx="6">_</tspan></text>
    </svg>
  </div>
  <p class="note">Hacker / CLI aesthetic. Instantly reads "infra engineer" and feels native to a dev audience.</p>
</div>

</div>
</body>
</html>
