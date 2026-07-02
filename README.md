<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>MuhammadMirzo — GitHub Profile</title>
<link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;600;700&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet"/>
<style>
:root{
  --bg:#07090F;--s1:#0D1117;--s2:#161B22;--s3:#1C2333;
  --bd:#21262D;--b1:#0D47A1;--b2:#1565C0;--b4:#1E88E5;
  --bl:#64B5F6;--bx:#BBDEFB;--tx:#E6EDF3;--tm:#8B949E;--tw:#FFFFFF;
  --glow:rgba(100,181,246,0.15);
}
*{margin:0;padding:0;box-sizing:border-box;}
body{background:var(--bg);color:var(--tx);font-family:'Inter',sans-serif;overflow-x:hidden;}

.hero{position:relative;text-align:center;padding:70px 20px 50px;background:linear-gradient(180deg,#0D2B6B 0%,#07090F 100%);overflow:hidden;}
.stars{position:absolute;inset:0;pointer-events:none;}
.star{position:absolute;border-radius:50%;background:var(--bl);animation:twinkle var(--d,3s) ease-in-out infinite alternate;}
@keyframes twinkle{from{opacity:.1;transform:scale(.8);}to{opacity:.9;transform:scale(1.2);}}

.av-ring{display:inline-block;width:130px;height:130px;border-radius:50%;background:conic-gradient(var(--bl),var(--b1),var(--b4),var(--bl));animation:spin 8s linear infinite;padding:3px;margin-bottom:28px;}
@keyframes spin{to{transform:rotate(360deg);}}
.av-inner{width:100%;height:100%;border-radius:50%;background:var(--bg);display:flex;align-items:center;justify-content:center;overflow:hidden;}

.hero h1{font-family:'Fira Code',monospace;font-size:clamp(1.8rem,5vw,2.8rem);font-weight:700;color:var(--tw);margin-bottom:6px;}
.hero h1 em{color:var(--bl);font-style:normal;}
.tagline{color:var(--bl);letter-spacing:3px;text-transform:uppercase;font-size:.8rem;font-weight:300;margin-bottom:28px;}
.tw-box{font-family:'Fira Code',monospace;font-size:.95rem;color:var(--bl);background:rgba(13,71,161,.18);border:1px solid rgba(100,181,246,.25);border-radius:8px;padding:10px 24px;display:inline-block;min-width:300px;}
.cur{animation:blink .8s step-end infinite;}
@keyframes blink{50%{opacity:0;}}

.wrap{max-width:920px;margin:0 auto;padding:0 20px 64px;}

.stitle{font-family:'Fira Code',monospace;font-size:1rem;color:var(--bl);margin:52px 0 20px;display:flex;align-items:center;gap:12px;}
.stitle::after{content:'';flex:1;height:1px;background:linear-gradient(90deg,var(--b2),transparent);}

.about-list{display:flex;flex-direction:column;gap:10px;}
.about-item{display:flex;align-items:center;gap:14px;background:var(--s2);border:1px solid var(--bd);border-left:3px solid var(--b2);border-radius:8px;padding:12px 16px;font-size:.92rem;transition:border-color .2s,background .2s;}
.about-item:hover{border-left-color:var(--bl);background:var(--s3);}
.about-icon{width:36px;height:36px;border-radius:8px;flex-shrink:0;background:rgba(13,71,161,.3);border:1px solid rgba(100,181,246,.2);display:flex;align-items:center;justify-content:center;}

.sk-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(130px,1fr));gap:12px;}
.sk-card{background:var(--s2);border:1px solid var(--bd);border-radius:10px;padding:16px 10px;text-align:center;transition:transform .2s,border-color .2s,box-shadow .2s;cursor:default;}
.sk-card:hover{transform:translateY(-5px);border-color:var(--bl);box-shadow:0 0 20px var(--glow);}
.sk-card svg{display:block;margin:0 auto 10px;}
.sk-name{font-size:.72rem;color:var(--tm);font-family:'Fira Code',monospace;letter-spacing:.5px;}

.badges{display:flex;flex-wrap:wrap;gap:8px;margin-top:16px;}
.badge{display:inline-flex;align-items:center;gap:7px;background:rgba(13,71,161,.25);border:1px solid rgba(100,181,246,.25);border-radius:6px;padding:6px 14px;font-family:'Fira Code',monospace;font-size:.74rem;color:var(--bl);font-weight:600;transition:background .2s,box-shadow .2s;}
.badge:hover{background:rgba(21,101,192,.4);box-shadow:0 0 12px var(--glow);}
.badge svg{flex-shrink:0;}

.stat-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;}
.stat-card{background:var(--s2);border:1px solid var(--bd);border-radius:12px;overflow:hidden;}
.stat-card img{width:100%;display:block;}

.con-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:14px;}
.con-card{background:var(--s2);border:1px solid var(--bd);border-radius:12px;padding:20px 18px;display:flex;align-items:center;gap:14px;text-decoration:none;color:var(--tx);transition:border-color .2s,background .2s,transform .2s;}
.con-card:hover{border-color:var(--bl);background:var(--s3);transform:translateY(-3px);}
.con-icon{width:46px;height:46px;border-radius:10px;flex-shrink:0;background:linear-gradient(135deg,var(--b1),var(--b4));display:flex;align-items:center;justify-content:center;}
.con-label{font-size:.68rem;color:var(--tm);text-transform:uppercase;letter-spacing:1.2px;margin-bottom:3px;}
.con-val{font-family:'Fira Code',monospace;font-size:.82rem;color:var(--bl);}

footer{background:linear-gradient(180deg,var(--bg) 0%,#0D2B6B 100%);text-align:center;padding:36px 20px;color:var(--tm);font-size:.78rem;font-family:'Fira Code',monospace;}
footer span{color:var(--bl);}
</style>
</head>
<body>

<div class="hero" id="hero">
<div class="stars" id="stars"></div>

<div class="av-ring">
  <div class="av-inner">
    <svg width="100" height="100" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
      <rect x="22" y="28" width="56" height="42" rx="10" fill="#0D47A1" stroke="#64B5F6" stroke-width="1.5"/>
      <line x1="50" y1="28" x2="50" y2="18" stroke="#64B5F6" stroke-width="2" stroke-linecap="round"/>
      <circle cx="50" cy="15" r="4" fill="#64B5F6"/>
      <rect x="30" y="38" width="14" height="10" rx="4" fill="#64B5F6"/>
      <rect x="56" y="38" width="14" height="10" rx="4" fill="#64B5F6"/>
      <circle cx="37" cy="43" r="3" fill="#0D1117"/>
      <circle cx="63" cy="43" r="3" fill="#0D1117"/>
      <circle cx="39" cy="41" r="1" fill="#BBDEFB"/>
      <circle cx="65" cy="41" r="1" fill="#BBDEFB"/>
      <rect x="34" y="56" width="32" height="7" rx="3" fill="#1565C0"/>
      <rect x="37" y="58" width="5" height="3" rx="1" fill="#64B5F6"/>
      <rect x="45" y="58" width="5" height="3" rx="1" fill="#64B5F6"/>
      <rect x="53" y="58" width="5" height="3" rx="1" fill="#64B5F6"/>
      <rect x="43" y="70" width="14" height="8" rx="3" fill="#0D47A1" stroke="#64B5F6" stroke-width="1"/>
      <rect x="18" y="78" width="64" height="18" rx="7" fill="#0D47A1" stroke="#64B5F6" stroke-width="1.5"/>
      <circle cx="50" cy="87" r="4" fill="#64B5F6" opacity=".8"/>
      <circle cx="38" cy="87" r="2.5" fill="#1976D2"/>
      <circle cx="62" cy="87" r="2.5" fill="#1976D2"/>
    </svg>
  </div>
</div>

<h1>Muhammad<em>Mirzo</em></h1>
<p class="tagline">Robotics &amp; Software Enthusiast</p>
<div class="tw-box" id="tw"></div>
</div>

<main class="wrap">

<div class="stitle">&lt;!-- men haqimda --&gt;</div>
<div class="about-list">

  <div class="about-item">
    <div class="about-icon">
      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#64B5F6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 10v6M2 10l10-5 10 5-10 5z"/><path d="M6 12v5c3 3 9 3 12 0v-5"/></svg>
    </div>
    <span><strong>Robbit</strong> ta'lim markazida robototexnika va dasturlash o'rganganman</span>
  </div>

  <div class="about-item">
    <div class="about-icon">
      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#64B5F6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="11" width="18" height="10" rx="2"/><circle cx="12" cy="5" r="2"/><path d="M12 7v4"/></svg>
    </div>
    <span>Robototexnika: <strong>Arduino, EV3 Mindstorms, LEGO SPIKE, VEX Car, Markerzoid, VEDO AI</strong></span>
  </div>

  <div class="about-item">
    <div class="about-icon">
      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#64B5F6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="16 18 22 12 16 6"/><polyline points="8 6 2 12 8 18"/></svg>
    </div>
    <span>HTML, Python, C++ va AI bilan ishlashni yaxshi ko'raman</span>
  </div>

  <div class="about-item">
    <div class="about-icon">
      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#64B5F6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><line x1="2" y1="12" x2="22" y2="12"/><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/></svg>
    </div>
    <span>Open-source loyihalarga hissa qo'shishga harakat qilaman</span>
  </div>

</div>

<div class="stitle">&lt;!-- texnologiyalar --&gt;</div>
<div class="sk-grid">

  <div class="sk-card">
    <svg width="42" height="42" viewBox="0 0 42 42">
      <rect width="42" height="42" rx="9" fill="#E44D2620"/>
      <text x="21" y="27" text-anchor="middle" font-size="20" font-weight="700" fill="#E44D26" font-family="monospace">&lt;/&gt;</text>
    </svg>
    <div class="sk-name">HTML</div>
  </div>

  <div class="sk-card">
    <svg width="42" height="42" viewBox="0 0 42 42">
      <rect width="42" height="42" rx="9" fill="#3776AB20"/>
      <path d="M21 8c-5 0-4.7 2.2-4.7 2.2v2.3h4.8v.7H13.6S10 12.8 10 18s3.2 5 3.2 5h2v-2.4s-.2-3.2 3.1-3.2h4.5s2.8.1 2.8-2.7V10.9S26.1 8 21 8z" fill="#3776AB"/>
      <circle cx="18" cy="10.5" r="1" fill="#FFD43B"/>
      <path d="M21 34c5 0 4.7-2.2 4.7-2.2v-2.3h-4.8v-.7h7.5s3.6.4 3.6-4.8-3.2-5-3.2-5h-2v2.4s.2 3.2-3.1 3.2h-4.5s-2.8-.1-2.8 2.7V31S15.9 34 21 34z" fill="#FFD43B"/>
      <circle cx="24" cy="31.5" r="1" fill="#3776AB"/>
    </svg>
    <div class="sk-name">Python</div>
  </div>

  <div class="sk-card">
    <svg width="42" height="42" viewBox="0 0 42 42">
      <rect width="42" height="42" rx="9" fill="#00599C20"/>
      <text x="21" y="26" text-anchor="middle" font-size="14" font-weight="700" fill="#00599C" font-family="monospace">C++</text>
    </svg>
    <div class="sk-name">C++</div>
  </div>

  <div class="sk-card">
    <svg width="42" height="42" viewBox="0 0 42 42">
      <rect width="42" height="42" rx="9" fill="#64B5F620"/>
      <circle cx="21" cy="17" r="6" fill="none" stroke="#64B5F6" stroke-width="1.5"/>
      <circle cx="21" cy="17" r="2.5" fill="#64B5F6"/>
      <line x1="21" y1="23" x2="21" y2="34" stroke="#64B5F6" stroke-width="1.5"/>
      <line x1="14" y1="29" x2="28" y2="29" stroke="#64B5F6" stroke-width="1.5"/>
      <line x1="14" y1="29" x2="11" y2="35" stroke="#64B5F6" stroke-width="1.5"/>
      <line x1="28" y1="29" x2="31" y2="35" stroke="#64B5F6" stroke-width="1.5"/>
    </svg>
    <div class="sk-name">AI / ML</div>
  </div>

  <div class="sk-card">
    <svg width="42" height="42" viewBox="0 0 42 42">
      <rect width="42" height="42" rx="9" fill="#00979D20"/>
      <rect x="7" y="16" width="28" height="13" rx="3" fill="none" stroke="#00979D" stroke-width="1.5"/>
      <circle cx="14" cy="22" r="3" fill="none" stroke="#00979D" stroke-width="1.5"/>
      <path d="M20 22h7" stroke="#00979D" stroke-width="2" stroke-linecap="round"/>
      <path d="M17 22h3" stroke="#00979D" stroke-width="1.5" stroke-linecap="round"/>
      <path d="M28 20v5M30 21v3" stroke="#00979D" stroke-width="1.5" stroke-linecap="round"/>
      <line x1="10" y1="16" x2="10" y2="12" stroke="#00979D" stroke-width="1.5" stroke-linecap="round"/>
      <line x1="14" y1="16" x2="14" y2="12" stroke="#00979D" stroke-width="1.5" stroke-linecap="round"/>
    </svg>
    <div class="sk-name">Arduino</div>
  </div>

  <div class="sk-card">
    <svg width="42" height="42" viewBox="0 0 42 42">
      <rect width="42" height="42" rx="9" fill="#E2001A15"/>
      <rect x="7" y="13" width="28" height="17" rx="4" fill="none" stroke="#E2001A" stroke-width="1.5"/>
      <rect x="11" y="17" width="9" height="6" rx="2" fill="#E2001A" opacity=".6"/>
      <rect x="22" y="17" width="8" height="6" rx="2" fill="#E2001A" opacity=".6"/>
      <circle cx="21" cy="15" r="1.5" fill="#E2001A"/>
      <line x1="5" y1="22" x2="7" y2="22" stroke="#E2001A" stroke-width="2"/>
      <line x1="35" y1="22" x2="37" y2="22" stroke="#E2001A" stroke-width="2"/>
    </svg>
    <div class="sk-name">EV3 Mindstorms</div>
  </div>

  <div class="sk-card">
    <svg width="42" height="42" viewBox="0 0 42 42">
      <rect width="42" height="42" rx="9" fill="#FFC50020"/>
      <rect x="8" y="9" width="26" height="24" rx="5" fill="none" stroke="#FFC500" stroke-width="1.5"/>
      <circle cx="21" cy="21" r="6" fill="none" stroke="#FFC500" stroke-width="1.5"/>
      <circle cx="21" cy="21" r="2" fill="#FFC500"/>
      <line x1="21" y1="9" x2="21" y2="13" stroke="#FFC500" stroke-width="1.5"/>
      <line x1="21" y1="29" x2="21" y2="33" stroke="#FFC500" stroke-width="1.5"/>
      <line x1="8" y1="21" x2="12" y2="21" stroke="#FFC500" stroke-width="1.5"/>
      <line x1="30" y1="21" x2="34" y2="21" stroke="#FFC500" stroke-width="1.5"/>
    </svg>
    <div class="sk-name">LEGO SPIKE</div>
  </div>

  <div class="sk-card">
    <svg width="42" height="42" viewBox="0 0 42 42">
      <rect width="42" height="42" rx="9" fill="#64B5F620"/>
      <rect x="6" y="18" width="30" height="10" rx="3" fill="none" stroke="#64B5F6" stroke-width="1.5"/>
      <rect x="11" y="12" width="20" height="8" rx="2" fill="none" stroke="#64B5F6" stroke-width="1.5"/>
      <circle cx="11" cy="28" r="4" fill="none" stroke="#64B5F6" stroke-width="1.5"/>
      <circle cx="31" cy="28" r="4" fill="none" stroke="#64B5F6" stroke-width="1.5"/>
      <circle cx="11" cy="28" r="1.5" fill="#64B5F6"/>
      <circle cx="31" cy="28" r="1.5" fill="#64B5F6"/>
    </svg>
    <div class="sk-name">VEX Car</div>
  </div>

  <div class="sk-card">
    <svg width="42" height="42" viewBox="0 0 42 42">
      <rect width="42" height="42" rx="9" fill="#90CAF920"/>
      <polygon points="21,7 34,14.5 34,29.5 21,37 8,29.5 8,14.5" fill="none" stroke="#90CAF9" stroke-width="1.5"/>
      <polygon points="21,14 27,17.5 27,24.5 21,28 15,24.5 15,17.5" fill="#90CAF9" opacity=".25"/>
      <circle cx="21" cy="21" r="2.5" fill="#90CAF9"/>
    </svg>
    <div class="sk-name">Markerzoid</div>
  </div>

  <div class="sk-card">
    <svg width="42" height="42" viewBox="0 0 42 42">
      <rect width="42" height="42" rx="9" fill="#64B5F620"/>
      <rect x="8" y="12" width="26" height="16" rx="3" fill="none" stroke="#64B5F6" stroke-width="1.5"/>
      <line x1="13" y1="28" x2="11" y2="34" stroke="#64B5F6" stroke-width="1.5"/>
      <line x1="29" y1="28" x2="31" y2="34" stroke="#64B5F6" stroke-width="1.5"/>
      <line x1="9" y1="34" x2="33" y2="34" stroke="#64B5F6" stroke-width="1.5"/>
      <circle cx="15" cy="20" r="2.5" fill="none" stroke="#64B5F6" stroke-width="1.2"/>
      <path d="M21 17l2.5 3-2.5 3" stroke="#64B5F6" stroke-width="1.2" fill="none" stroke-linecap="round"/>
      <path d="M27 17l-1.5 3 1.5 3" stroke="#64B5F6" stroke-width="1.2" fill="none" stroke-linecap="round"/>
    </svg>
    <div class="sk-name">VEDO AI</div>
  </div>

  <div class="sk-card">
    <svg width="42" height="42" viewBox="0 0 42 42">
      <rect width="42" height="42" rx="9" fill="#F0503220"/>
      <path d="M25.5 13.5L14.5 2.5a1.7 1.7 0 0 0-2.4 0L9.9 4.7 13 7.8a2 2 0 0 1 2.5 2.5l3 3a2 2 0 1 1-1.2 1.2L14.5 11.7V19a2 2 0 1 1-1.6 0V11.5a2 2 0 0 1-1.1-2.6L8.7 5.8 2.5 12a1.7 1.7 0 0 0 0 2.4l11 11a1.7 1.7 0 0 0 2.4 0l9.6-9.6a1.7 1.7 0 0 0 0-2.4z" fill="#F05032" opacity=".8" transform="translate(8,8)"/>
    </svg>
    <div class="sk-name">Git / GitHub</div>
  </div>

  <div class="sk-card">
    <svg width="42" height="42" viewBox="0 0 42 42">
      <rect width="42" height="42" rx="9" fill="#5C9BD620"/>
      <circle cx="21" cy="21" r="9" fill="none" stroke="#5C9BD6" stroke-width="1.5"/>
      <circle cx="21" cy="21" r="5" fill="none" stroke="#5C9BD6" stroke-width="1.5"/>
      <circle cx="21" cy="21" r="2" fill="#5C9BD6"/>
      <line x1="21" y1="8" x2="21" y2="12" stroke="#E74C3C" stroke-width="2" stroke-linecap="round"/>
      <line x1="32" y1="15" x2="29" y2="17" stroke="#27AE60" stroke-width="2" stroke-linecap="round"/>
      <line x1="10" y1="15" x2="13" y2="17" stroke="#3498DB" stroke-width="2" stroke-linecap="round"/>
    </svg>
    <div class="sk-name">OpenCV</div>
  </div>

</div>

<div class="badges">
  <div class="badge">
    <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
    Open-Source Contributor
  </div>
  <div class="badge">
    <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="11" width="18" height="10" rx="2"/><circle cx="12" cy="5" r="2"/><path d="M12 7v4"/></svg>
    EV3 Mindstorms
  </div>
  <div class="badge">
    <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="3"/><path d="M12 2v4M12 18v4M4.93 4.93l2.83 2.83M16.24 16.24l2.83 2.83M2 12h4M18 12h4M4.93 19.07l2.83-2.83M16.24 7.76l2.83-2.83"/></svg>
    LEGO SPIKE
  </div>
  <div class="badge">
    <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 17H3a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v3"/><rect x="9" y="11" width="14" height="10" rx="1"/></svg>
    VEX Car
  </div>
  <div class="badge">
    <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polygon points="12 2 22 8.5 22 15.5 12 22 2 15.5 2 8.5 12 2"/></svg>
    Markerzoid
  </div>
  <div class="badge">
    <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="3" width="20" height="14" rx="2"/><line x1="8" y1="21" x2="16" y2="21"/><line x1="12" y1="17" x2="12" y2="21"/></svg>
    VEDO AI
  </div>
  <div class="badge">
    <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="9" cy="12" r="4"/><path d="M15 8a4 4 0 0 1 0 8"/><path d="M15 3a9 9 0 0 1 0 18"/></svg>
    Robototexnik
  </div>
</div>

<div class="stitle">&lt;!-- github statistika --&gt;</div>
<div class="stat-grid">
  <div class="stat-card"><img src="https://github-readme-stats.vercel.app/api?username=muhammadmirzo4321&show_icons=true&theme=cobalt&hide_border=true&title_color=64B5F6&icon_color=64B5F6&text_color=E6EDF3&bg_color=161B22" alt="GitHub Stats"/></div>
  <div class="stat-card"><img src="https://github-readme-streak-stats.herokuapp.com/?user=muhammadmirzo4321&theme=cobalt&hide_border=true&background=161B22&ring=64B5F6&fire=64B5F6&currStreakLabel=64B5F6" alt="Streak"/></div>
</div>
<br/>
<div class="stat-card" style="max-width:380px;margin:0 auto;">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=muhammadmirzo4321&layout=compact&theme=cobalt&hide_border=true&bg_color=161B22&title_color=64B5F6&text_color=E6EDF3" alt="Top Languages"/>
</div>

<div class="stitle">&lt;!-- bog'lanish --&gt;</div>
<div class="con-grid">
  <a class="con-card" href="mailto:muhammadmirzo4321@gmail.com">
    <div class="con-icon">
      <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#BBDEFB" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
    </div>
    <div>
      <div class="con-label">Email</div>
      <div class="con-val">muhammadmirzo4321@gmail.com</div>
    </div>
  </a>
  <a class="con-card" href="tel:+998884020513">
    <div class="con-icon">
      <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#BBDEFB" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6A19.79 19.79 0 0 1 2.12 4.18 2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72c.127.96.361 1.903.7 2.81a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.907.339 1.85.573 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
    </div>
    <div>
      <div class="con-label">Telefon</div>
      <div class="con-val">+998 (88) 402-05-13</div>
    </div>
  </a>
  <a class="con-card" href="https://github.com/muhammadmirzo4321" target="_blank">
    <div class="con-icon">
      <svg width="22" height="22" viewBox="0 0 24 24" fill="#BBDEFB"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0 0 24 12c0-6.63-5.37-12-12-12z"/></svg>
    </div>
    <div>
      <div class="con-label">GitHub</div>
      <div class="con-val">@muhammadmirzo4321</div>
    </div>
  </a>
</div>

</main>

<footer>
  <span>MuhammadMirzo</span> · Robototexnika &amp; Dasturlash<br/>
  <span style="font-size:.7rem;opacity:.45;display:block;margin-top:6px;">Arduino · Python · C++ · AI · EV3 · SPIKE · VEX</span>
</footer>

<script>
const container=document.getElementById('stars');
for(let i=0;i<60;i++){
  const s=document.createElement('div');
  s.className='star';
  const sz=Math.random()*2.5+.5;
  s.style.cssText='left:'+Math.random()*100+'%;top:'+Math.random()*100+'%;width:'+sz+'px;height:'+sz+'px;--d:'+(2+Math.random()*5)+'s;animation-delay:'+-Math.random()*5+'s;opacity:'+(Math.random()*.5+.1);
  container.appendChild(s);
}
const lines=["Open-Source Contributor","Robototexnika mutaxassisi","Arduino | EV3 | SPIKE | VEX","Python / C++ / HTML dasturchisi","Markerzoid | VEDO AI ishqibozi"];
let li=0,ci=0,del=false;
const el=document.getElementById('tw');
function tick(){
  const line=lines[li];
  if(!del){el.innerHTML='$ '+line.slice(0,ci)+'<span class="cur">\u2588</span>';ci++;if(ci>line.length){del=true;setTimeout(tick,2000);return;}}
  else{el.innerHTML='$ '+line.slice(0,ci)+'<span class="cur">\u2588</span>';ci--;if(ci<0){del=false;li=(li+1)%lines.length;ci=0;}}
  setTimeout(tick,del?35:60);
}
tick();
</script>
</body>
</html>

