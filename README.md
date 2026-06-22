[jayesh_github_profile.html](https://github.com/user-attachments/files/29191248/jayesh_github_profile.html)<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Cheedella Jayesh — GitHub Profile</title>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet"/>
<style>
:root{--void:#03050a;--deep:#070d1a;--card:rgba(255,255,255,0.04);--border:rgba(139,92,246,0.25);--purple:#8b5cf6;--cyan:#06b6d4;--pink:#ec4899;--green:#10b981;--amber:#f59e0b;--white:#f1f5f9;--muted:#64748b;--glow-p:0 0 40px rgba(139,92,246,0.3);--glow-c:0 0 40px rgba(6,182,212,0.3);}
*{margin:0;padding:0;box-sizing:border-box;}
body{background:var(--void);color:var(--white);font-family:'Space Grotesk',sans-serif;overflow-x:hidden;}
#canvas{position:fixed;top:0;left:0;width:100%;height:100%;z-index:0;pointer-events:none;}
.grid{position:fixed;inset:0;background-image:linear-gradient(rgba(139,92,246,0.04) 1px,transparent 1px),linear-gradient(90deg,rgba(139,92,246,0.04) 1px,transparent 1px);background-size:60px 60px;z-index:0;pointer-events:none;}
.wrap{position:relative;z-index:2;max-width:920px;margin:0 auto;padding:40px 24px 80px;}
.orb{position:fixed;border-radius:50%;filter:blur(80px);pointer-events:none;z-index:1;animation:fl 8s ease-in-out infinite;}
.o1{width:400px;height:400px;background:rgba(139,92,246,0.12);top:-100px;right:-100px;}
.o2{width:300px;height:300px;background:rgba(6,182,212,0.1);bottom:0;left:-80px;animation-delay:-4s;}
.o3{width:250px;height:250px;background:rgba(236,72,153,0.08);top:40%;right:5%;animation-delay:-2s;}
@keyframes fl{0%,100%{transform:translateY(0) scale(1);}50%{transform:translateY(-30px) scale(1.05);}}
/* HERO */
.hero{text-align:center;padding:60px 0 40px;}
.badge{display:inline-flex;align-items:center;gap:8px;background:rgba(139,92,246,0.12);border:1px solid var(--border);border-radius:999px;padding:6px 18px;font-size:12px;font-family:'JetBrains Mono',monospace;color:var(--purple);letter-spacing:.08em;margin-bottom:28px;}
.dot{width:7px;height:7px;border-radius:50%;background:var(--green);box-shadow:0 0 8px var(--green);animation:pulse 1.5s infinite;}
@keyframes pulse{0%,100%{opacity:1;transform:scale(1);}50%{opacity:.5;transform:scale(1.4);}}
.hero-name{font-size:clamp(42px,8vw,76px);font-weight:700;line-height:1;letter-spacing:-.03em;background:linear-gradient(135deg,#fff 0%,var(--purple) 50%,var(--cyan) 100%);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;margin-bottom:12px;}
.hero-sub{font-family:'JetBrains Mono',monospace;font-size:14px;color:var(--muted);margin-bottom:28px;}
.hero-sub span{color:var(--cyan);}
.tw{font-size:20px;font-weight:600;color:var(--purple);min-height:34px;margin-bottom:32px;}
.cur{display:inline-block;width:2px;height:1.1em;background:var(--cyan);vertical-align:middle;margin-left:3px;animation:blink .8s step-end infinite;}
@keyframes blink{50%{opacity:0;}}
/* SOCIALS */
.socials{display:flex;justify-content:center;flex-wrap:wrap;gap:10px;margin-bottom:16px;}
.sb{display:inline-flex;align-items:center;gap:7px;padding:9px 18px;border-radius:10px;font-size:13px;font-weight:600;text-decoration:none;transition:all .25s;border:1px solid transparent;}
.sb:hover{transform:translateY(-3px);box-shadow:0 8px 30px rgba(0,0,0,.4);}
.li{background:#0077b5;color:#fff;}.ig{background:linear-gradient(135deg,#833ab4,#fd1d1d,#fcb045);color:#fff;}.lc{background:#ffa116;color:#1a1a1a;}.ml{background:rgba(255,255,255,.06);color:var(--white);border-color:var(--border);}.vw{background:rgba(139,92,246,.15);color:var(--purple);border-color:var(--border);}
/* DIVIDER */
.div{height:1px;background:linear-gradient(90deg,transparent,var(--border),transparent);margin:44px 0;}
/* SECTION */
.sl{display:flex;align-items:center;gap:14px;margin-bottom:24px;}
.sl span{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--purple);letter-spacing:.12em;text-transform:uppercase;}
.sln{flex:1;height:1px;background:linear-gradient(90deg,var(--border),transparent);}
/* STATS */
.sg{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;}
@media(max-width:600px){.sg{grid-template-columns:1fr;}}
.sc{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:20px;text-align:center;transition:all .25s;}
.sc:hover{border-color:var(--cyan);box-shadow:var(--glow-c);transform:scale(1.04);}
.sn{font-size:32px;font-weight:700;font-family:'JetBrains Mono',monospace;background:linear-gradient(135deg,var(--cyan),var(--purple));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.sl2{font-size:12px;color:var(--muted);margin-top:4px;font-family:'JetBrains Mono',monospace;}
/* CODE */
.cc{background:#0d1117;border:1px solid rgba(139,92,246,.3);border-radius:16px;overflow:hidden;}
.ch{background:#161b22;padding:12px 20px;display:flex;align-items:center;gap:10px;border-bottom:1px solid rgba(255,255,255,.06);}
.dr{width:12px;height:12px;border-radius:50%;background:#ff5f57;}.dy{width:12px;height:12px;border-radius:50%;background:#ffbd2e;}.dg{width:12px;height:12px;border-radius:50%;background:#28c840;}
.cf{font-family:'JetBrains Mono',monospace;font-size:12px;color:var(--muted);margin-left:8px;}
.cb{padding:24px;font-family:'JetBrains Mono',monospace;font-size:13px;line-height:1.8;overflow-x:auto;}
.kw{color:#ff79c6;}.cls{color:#8be9fd;}.fn{color:#50fa7b;}.str{color:#f1fa8c;}.cm{color:#6272a4;}.num{color:#bd93f9;}
/* CARD */
.card{background:var(--card);border:1px solid var(--border);border-radius:16px;padding:28px;position:relative;overflow:hidden;transition:all .3s;}
.card::before{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,rgba(139,92,246,.6),transparent);}
.card:hover{border-color:rgba(139,92,246,.5);box-shadow:var(--glow-p);transform:translateY(-3px);}
/* BADGES */
.bg{display:flex;flex-wrap:wrap;gap:10px;}
.bdg{display:inline-flex;align-items:center;gap:7px;padding:8px 16px;border-radius:8px;font-size:13px;font-weight:600;border:1px solid transparent;transition:all .2s;cursor:default;}
.bdg:hover{transform:translateY(-2px) scale(1.04);box-shadow:0 6px 20px rgba(0,0,0,.4);}
.bst{font-size:11px;font-family:'JetBrains Mono',monospace;color:var(--muted);letter-spacing:.1em;text-transform:uppercase;margin-bottom:10px;margin-top:20px;}
.bst:first-child{margin-top:0;}
.bp{background:rgba(55,118,171,.2);border-color:rgba(55,118,171,.5);color:#4da6ff;}
.bc{background:rgba(0,89,196,.2);border-color:rgba(0,89,196,.5);color:#5599ff;}
.bq{background:rgba(248,161,0,.15);border-color:rgba(248,161,0,.4);color:#f8a100;}
.bh{background:rgba(227,76,38,.15);border-color:rgba(227,76,38,.4);color:#e34c26;}
.bcs{background:rgba(21,114,182,.15);border-color:rgba(21,114,182,.4);color:#1572b6;}
.bj{background:rgba(247,223,30,.12);border-color:rgba(247,223,30,.4);color:#f7df1e;}
.br{background:rgba(97,218,251,.12);border-color:rgba(97,218,251,.4);color:#61dafb;}
.bn{background:rgba(67,133,61,.15);border-color:rgba(67,133,61,.4);color:#68a063;}
.bm{background:rgba(77,179,61,.15);border-color:rgba(77,179,61,.4);color:#4db33d;}
.bx{background:rgba(255,255,255,.07);border-color:rgba(255,255,255,.2);color:#ccc;}
.baz{background:rgba(0,120,215,.15);border-color:rgba(0,120,215,.4);color:#0078d7;}
.bml{background:rgba(255,111,0,.15);border-color:rgba(255,111,0,.4);color:#ff8c42;}
.bvs{background:rgba(0,122,204,.15);border-color:rgba(0,122,204,.4);color:#007acc;}
.bgt{background:rgba(240,80,50,.15);border-color:rgba(240,80,50,.4);color:#f05032;}
.bpo{background:rgba(255,108,55,.15);border-color:rgba(255,108,55,.4);color:#ff6c37;}
.bci{background:rgba(27,160,215,.15);border-color:rgba(27,160,215,.4);color:#1ba0d7;}
/* PROJECT */
.pc{background:linear-gradient(135deg,rgba(139,92,246,.06),rgba(6,182,212,.04));border:1px solid rgba(139,92,246,.3);border-radius:20px;padding:32px;position:relative;overflow:hidden;transition:all .3s;}
.pc::after{content:'';position:absolute;top:-60px;right:-60px;width:200px;height:200px;border-radius:50%;background:radial-gradient(circle,rgba(139,92,246,.15),transparent 70%);pointer-events:none;}
.pc:hover{border-color:var(--purple);box-shadow:var(--glow-p);transform:translateY(-4px);}
.ptag{display:inline-block;background:rgba(139,92,246,.2);color:var(--purple);border:1px solid rgba(139,92,246,.4);border-radius:6px;font-size:11px;font-family:'JetBrains Mono',monospace;padding:3px 10px;margin:0 4px 8px 0;}
.ptit{font-size:22px;font-weight:700;margin:12px 0 10px;background:linear-gradient(90deg,var(--white),var(--purple));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.pd{color:#94a3b8;font-size:14px;line-height:1.7;margin-bottom:20px;}
.fg{display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:10px;margin-top:16px;}
.fi{background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.07);border-radius:10px;padding:12px 14px;font-size:13px;display:flex;align-items:flex-start;gap:8px;}
.fii{font-size:16px;flex-shrink:0;margin-top:1px;}.ft{color:#cbd5e1;}.fl{color:var(--purple);font-weight:600;font-size:11px;display:block;margin-bottom:2px;}
/* TIMELINE */
.tl{position:relative;padding-left:32px;}
.tl::before{content:'';position:absolute;left:8px;top:0;bottom:0;width:2px;background:linear-gradient(to bottom,var(--purple),var(--cyan),transparent);}
.ti{position:relative;margin-bottom:28px;}
.ti::before{content:'';position:absolute;left:-28px;top:6px;width:12px;height:12px;border-radius:50%;background:var(--purple);box-shadow:0 0 12px var(--purple);border:2px solid var(--deep);}
.ty{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--cyan);letter-spacing:.1em;margin-bottom:4px;}
.tn{font-size:17px;font-weight:600;color:var(--white);margin-bottom:4px;}
.td{font-size:13px;color:var(--muted);display:flex;align-items:center;gap:10px;flex-wrap:wrap;}
.tg{display:inline-block;background:rgba(16,185,129,.15);border:1px solid rgba(16,185,129,.3);color:var(--green);border-radius:6px;padding:2px 10px;font-family:'JetBrains Mono',monospace;font-size:12px;}
/* CERTS */
.cg{display:grid;grid-template-columns:repeat(auto-fill,minmax(230px,1fr));gap:14px;}
.certc{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:20px;display:flex;gap:14px;align-items:flex-start;transition:all .25s;}
.certc:hover{border-color:var(--amber);box-shadow:0 0 20px rgba(245,158,11,.2);transform:translateY(-2px);}
.ci2{font-size:28px;flex-shrink:0;}.cn{font-size:14px;font-weight:600;color:var(--white);margin-bottom:4px;}.cis{font-size:12px;color:var(--muted);}.cd{font-size:11px;color:var(--amber);font-family:'JetBrains Mono',monospace;margin-top:4px;}
/* GH STATS */
.gs{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-bottom:14px;}
@media(max-width:640px){.gs{grid-template-columns:1fr;}}
.gs img,.gl img{width:100%;border-radius:12px;display:block;}
.gl{margin-bottom:14px;text-align:center;}.gl img{max-width:480px;display:inline-block;}
.gt img{width:100%;border-radius:12px;}
/* STRENGTHS */
.strg{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;}
@media(max-width:560px){.strg{grid-template-columns:1fr 1fr;}}
.strc{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:18px 14px;text-align:center;transition:all .25s;}
.strc:hover{border-color:var(--purple);background:rgba(139,92,246,.08);transform:scale(1.04);}
.stri{font-size:26px;margin-bottom:8px;}.strn{font-size:13px;font-weight:600;color:var(--white);}
/* FOOTER */
.footer{text-align:center;padding:40px 0 0;border-top:1px solid rgba(255,255,255,.06);margin-top:20px;}
.ft2{font-size:22px;font-weight:700;margin-bottom:6px;background:linear-gradient(90deg,var(--purple),var(--cyan));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.fs{font-size:13px;color:var(--muted);margin-bottom:24px;font-family:'JetBrains Mono',monospace;}
/* COPY */
.cpsec{text-align:center;margin-top:40px;padding:30px;background:rgba(139,92,246,.07);border:1px dashed rgba(139,92,246,.35);border-radius:16px;}
.cpbtn{display:inline-flex;align-items:center;gap:8px;background:linear-gradient(135deg,var(--purple),var(--cyan));color:#fff;border:none;border-radius:10px;padding:12px 28px;font-size:14px;font-weight:700;font-family:'Space Grotesk',sans-serif;cursor:pointer;transition:all .2s;letter-spacing:.03em;margin-top:12px;}
.cpbtn:hover{transform:scale(1.05);box-shadow:0 8px 30px rgba(139,92,246,.5);}
.cpnote{font-size:12px;color:var(--muted);font-family:'JetBrains Mono',monospace;margin-top:10px;}
/* REVEAL */
.rev{opacity:0;transform:translateY(30px);transition:all .6s cubic-bezier(.22,1,.36,1);}
.rev.vis{opacity:1;transform:translateY(0);}
/* LANG PILL */
.lp{display:inline-block;background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.12);border-radius:999px;padding:4px 14px;font-size:12px;color:var(--white);margin:4px;}
</style>
</head>
<body>
<canvas id="canvas"></canvas>
<div class="grid"></div>
<div class="orb o1"></div>
<div class="orb o2"></div>
<div class="orb o3"></div>

<div class="wrap">

<!-- HERO -->
<section class="hero">
  <div class="badge"><div class="dot"></div>OPEN TO INTERNSHIPS &amp; COLLABORATIONS</div>
  <h1 class="hero-name">CHEEDELLA JAYESH</h1>
  <p class="hero-sub"><span>B.Tech CSE</span> &middot; Parul University, Gujarat &middot; <span>jayeshcheedella@gmail.com</span></p>
  <div class="tw" id="tw"><span class="cur"></span></div>
  <div class="socials">
    <a href="https://www.linkedin.com/in/jayesh-cheedella-579285295/" class="sb li" target="_blank">&#128279; LinkedIn</a>
    <a href="https://instagram.com/jayesh36876" class="sb ig" target="_blank">&#128247; @jayesh36876 &middot; 362 followers</a>
    <a href="https://leetcode.com/u/jayesh234/" class="sb lc" target="_blank">&#9889; LeetCode</a>
    <a href="mailto:jayeshcheedella@gmail.com" class="sb ml">&#9993;&#65039; Email</a>
    <span class="sb vw">&#128065;&#65039; Profile Views: Live</span>
  </div>
</section>

<div class="div"></div>

<!-- QUICK STATS -->
<section class="rev">
  <div class="sl"><span>// overview</span><div class="sln"></div></div>
  <div class="sg">
    <div class="sc"><div class="sn">7.01</div><div class="sl2">CGPA &middot; Parul University</div></div>
    <div class="sc"><div class="sn">88.9%</div><div class="sl2">Intermediate &middot; SDR's</div></div>
    <div class="sc"><div class="sn">85%</div><div class="sl2">SSC &middot; Good Shepherd</div></div>
  </div>
</section>

<div class="div"></div>

<!-- ABOUT -->
<section class="rev">
  <div class="sl"><span>// about me</span><div class="sln"></div></div>
  <div class="cc">
    <div class="ch"><div class="dr"></div><div class="dy"></div><div class="dg"></div><span class="cf">jayesh.py</span></div>
    <div class="cb">
<span class="kw">class</span> <span class="cls">JayeshCheedella</span>:<br>
&nbsp;&nbsp;&nbsp;&nbsp;<span class="kw">def</span> <span class="fn">__init__</span>(self):<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;self.name&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; = <span class="str">"Cheedella Jayesh"</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;self.role&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; = <span class="str">"Final-Year CSE Student &amp; AI Developer"</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;self.university = <span class="str">"Parul University, Gujarat (2023&ndash;2027)"</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;self.location&nbsp;&nbsp; = <span class="str">"Andhra Pradesh, India &#127470;&#127475;"</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;self.cgpa&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; = <span class="num">7.01</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;self.languages&nbsp; = [<span class="str">"English"</span>, <span class="str">"Telugu"</span>, <span class="str">"Hindi"</span>]<br>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;<span class="kw">def</span> <span class="fn">get_skills</span>(self):<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="kw">return</span> {<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="str">"core"</span>&nbsp; : [<span class="str">"Python"</span>, <span class="str">"C"</span>, <span class="str">"SQL"</span>],<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="str">"web"</span>&nbsp;&nbsp; : [<span class="str">"React.js"</span>, <span class="str">"Node.js"</span>, <span class="str">"MongoDB"</span>, <span class="str">"HTML/CSS/JS"</span>],<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="str">"ai_ml"</span> : [<span class="str">"Machine Learning"</span>, <span class="str">"Computer Vision"</span>, <span class="str">"Azure"</span>],<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="str">"oops"</span>&nbsp; : [<span class="str">"Polymorphism"</span>, <span class="str">"Encapsulation"</span>, <span class="str">"Inheritance"</span>],<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}<br>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;<span class="kw">def</span> <span class="fn">currently_seeking</span>(self):<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="kw">return</span> <span class="str">"&#128640; Internships | AI/ML Roles | Software Development"</span>
    </div>
  </div>
</section>

<div class="div"></div>

<!-- TECH STACK -->
<section class="rev">
  <div class="sl"><span>// tech stack</span><div class="sln"></div></div>
  <div class="card">
    <p class="bst">&#128187; Programming Languages</p>
    <div class="bg">
      <span class="bdg bp">&#128013; Python</span>
      <span class="bdg bc">&#9881;&#65039; C</span>
      <span class="bdg bq">&#128196; SQL</span>
      <span class="bdg bh">&#127758; HTML5</span>
    </div>
    <p class="bst">&#127758; Web Technologies</p>
    <div class="bg">
      <span class="bdg bcs">&#127912; CSS3</span>
      <span class="bdg bj">&#9889; JavaScript</span>
      <span class="bdg br">&#9883;&#65039; React.js</span>
      <span class="bdg bn">&#128154; Node.js</span>
      <span class="bdg bm">&#127807; MongoDB</span>
      <span class="bdg bx">&#128739;&#65039; Express.js</span>
    </div>
    <p class="bst">&#129504; AI / ML &amp; Cloud</p>
    <div class="bg">
      <span class="bdg bml">&#129504; Machine Learning</span>
      <span class="bdg baz">&#9729;&#65039; Microsoft Azure</span>
      <span class="bdg bml">&#128065;&#65039; Computer Vision</span>
    </div>
    <p class="bst">&#128295; Tools &amp; Platforms</p>
    <div class="bg">
      <span class="bdg bvs">&#128187; VS Code</span>
      <span class="bdg bgt">&#128256; Git</span>
      <span class="bdg bx">&#128008; GitHub</span>
      <span class="bdg bpo">&#128140; Postman</span>
      <span class="bdg bci">&#128268; CISCO Packet Tracer</span>
      <span class="bdg baz">&#128202; MS Excel</span>
    </div>
    <p class="bst">&#127959;&#65039; OOP Concepts</p>
    <div class="bg">
      <span class="bdg bp">&#128257; Polymorphism</span>
      <span class="bdg bc">&#128230; Encapsulation</span>
      <span class="bdg br">&#129516; Inheritance</span>
      <span class="bdg bn">&#127917; Abstraction</span>
      <span class="bdg bm">&#9889; Method Overloading</span>
    </div>
  </div>
</section>

<div class="div"></div>

<!-- PROJECT -->
<section class="rev">
  <div class="sl"><span>// featured project</span><div class="sln"></div></div>
  <div class="pc">
    <div>
      <span class="ptag">AI/ML</span><span class="ptag">MERN Stack</span><span class="ptag">Python</span><span class="ptag">Computer Vision</span><span class="ptag">Real-time</span>
    </div>
    <div class="ptit">&#128308; Smart Crime Detection &amp; Analysis Using AI</div>
    <p class="pd">An AI-powered platform that revolutionizes public safety and law enforcement through intelligent crime monitoring, pattern detection, and real-time analysis. Built as a secure, scalable, full-stack application enabling data-driven decision-making for officers and analysts.</p>
    <div class="fg">
      <div class="fi"><span class="fii">&#129504;</span><div><span class="fl">AI CORE</span><span class="ft">Crime pattern detection &amp; hotspot identification</span></div></div>
      <div class="fi"><span class="fii">&#128202;</span><div><span class="fl">DASHBOARD</span><span class="ft">Real-time analytics with visualizations &amp; alerts</span></div></div>
      <div class="fi"><span class="fii">&#128274;</span><div><span class="fl">ACCESS CONTROL</span><span class="ft">Role-based: Users, Officers, Analysts</span></div></div>
      <div class="fi"><span class="fii">&#128221;</span><div><span class="fl">REPORTING</span><span class="ft">Incident &amp; cybercrime reporting + case management</span></div></div>
      <div class="fi"><span class="fii">&#9883;&#65039;</span><div><span class="fl">FRONTEND</span><span class="ft">React.js with dynamic UI</span></div></div>
      <div class="fi"><span class="fii">&#128154;</span><div><span class="fl">BACKEND</span><span class="ft">Node.js + Express + MongoDB</span></div></div>
    </div>
  </div>
</section>

<div class="div"></div>

<!-- EDUCATION -->
<section class="rev">
  <div class="sl"><span>// education</span><div class="sln"></div></div>
  <div class="card">
    <div class="tl">
      <div class="ti">
        <div class="ty">2023 &ndash; 2027 &middot; CURRENT</div>
        <div class="tn">B.Tech &mdash; Computer Science Engineering</div>
        <div class="td">&#128205; Parul University, Gujarat <span class="tg">CGPA: 7.01</span></div>
      </div>
      <div class="ti">
        <div class="ty">2021 &ndash; 2023</div>
        <div class="tn">Intermediate &mdash; MPC</div>
        <div class="td">&#128205; SDR's Junior College, Andhra Pradesh <span class="tg">88.9%</span></div>
      </div>
      <div class="ti">
        <div class="ty">2021</div>
        <div class="tn">SSC &mdash; Secondary School</div>
        <div class="td">&#128205; Good Shepherd English Medium School, AP <span class="tg">85%</span></div>
      </div>
    </div>
  </div>
</section>

<div class="div"></div>

<!-- CERTIFICATIONS -->
<section class="rev">
  <div class="sl"><span>// certifications</span><div class="sln"></div></div>
  <div class="cg">
    <div class="certc"><div class="ci2">&#129504;</div><div><div class="cn">Artificial Intelligence</div><div class="cis">Simplilearn</div><div class="cd">May 2025</div></div></div>
    <div class="certc"><div class="ci2">&#128013;</div><div><div class="cn">Complete Python Bootcamp</div><div class="cis">Udemy &mdash; Zero to Hero</div><div class="cd">Completed</div></div></div>
    <div class="certc"><div class="ci2">&#127758;</div><div><div class="cn">Team Experts Program</div><div class="cis">Tata Consultancy Services (TCS)</div><div class="cd">May 2025</div></div></div>
    <div class="certc"><div class="ci2">&#129504;</div><div><div class="cn">Machine Learning</div><div class="cis">Course Completion</div><div class="cd">March 2024</div></div></div>
  </div>
</section>

<div class="div"></div>

<!-- GITHUB STATS -->
<section class="rev">
  <div class="sl"><span>// github stats</span><div class="sln"></div></div>
  <div class="gs">
    <img src="https://github-readme-stats.vercel.app/api?username=jayesh982&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=8b5cf6&icon_color=06b6d4&text_color=f1f5f9&rank_icon=github" alt="GitHub Stats"/>
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=jayesh982&theme=tokyonight&hide_border=true&background=0D1117&stroke=8b5cf6&ring=06b6d4&fire=8b5cf6&currStreakLabel=f1f5f9" alt="Streak"/>
  </div>
  <div class="gl">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jayesh982&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=8b5cf6&text_color=f1f5f9&langs_count=8" alt="Top Languages"/>
  </div>
  <div class="gt">
    <img src="https://github-profile-trophy.vercel.app/?username=jayesh982&theme=darkhub&no-frame=true&no-bg=true&margin-w=6&column=6" alt="Trophies"/>
  </div>
</section>

<div class="div"></div>

<!-- STRENGTHS -->
<section class="rev">
  <div class="sl"><span>// strengths</span><div class="sln"></div></div>
  <div class="strg">
    <div class="strc"><div class="stri">&#129504;</div><div class="strn">Problem Solving</div></div>
    <div class="strc"><div class="stri">&#128269;</div><div class="strn">Attention to Detail</div></div>
    <div class="strc"><div class="stri">&#129309;</div><div class="strn">Teamwork</div></div>
    <div class="strc"><div class="stri">&#9889;</div><div class="strn">Quick Learning</div></div>
    <div class="strc"><div class="stri">&#128172;</div><div class="strn">Communication</div></div>
    <div class="strc"><div class="stri">&#127919;</div><div class="strn">Goal-Oriented</div></div>
  </div>
</section>

<div class="div"></div>

<!-- LANGUAGES -->
<section class="rev">
  <div class="sl"><span>// languages known</span><div class="sln"></div></div>
  <div style="text-align:center;padding:10px 0;">
    <span class="lp">&#127468;&#127463; English</span>
    <span class="lp">&#127470;&#127475; Telugu</span>
    <span class="lp">&#127470;&#127475; Hindi</span>
  </div>
</section>

<div class="div"></div>

<!-- COPY README -->
<section class="rev cpsec">
  <div style="font-size:18px;font-weight:700;margin-bottom:6px;">&#128203; Copy Your GitHub README.md</div>
  <div style="font-size:13px;color:var(--muted);margin-bottom:14px;font-family:'JetBrains Mono',monospace;">Paste into github.com/jayesh982/jayesh982 &rarr; Edit README.md &rarr; Commit</div>
  <button class="cpbtn" onclick="copyReadme()">&#128203; Copy GitHub README</button>
  <div class="cpnote" id="cpst">Click to copy the complete README.md</div>
</section>

<!-- FOOTER -->
<div class="footer rev">
  <div class="ft2">Let's Build Something Amazing &#128640;</div>
  <div class="fs">Open to internships &middot; AI/ML roles &middot; Software Development &middot; Collaborations</div>
  <div class="socials">
    <a href="https://www.linkedin.com/in/jayesh-cheedella-579285295/" class="sb li" target="_blank">LinkedIn</a>
    <a href="https://instagram.com/jayesh36876" class="sb ig" target="_blank">Instagram</a>
    <a href="https://leetcode.com/u/jayesh234/" class="sb lc" target="_blank">LeetCode</a>
    <a href="mailto:jayeshcheedella@gmail.com" class="sb ml">Email</a>
  </div>
  <p style="margin-top:28px;font-size:12px;color:#334155;font-family:'JetBrains Mono',monospace;">Made with &#128156; &middot; Cheedella Jayesh &middot; 2025</p>
</div>

</div>

<script>
// PARTICLES
const cv=document.getElementById("canvas"),ctx=cv.getContext("2d");
let W,H,pts=[];
function resize(){W=cv.width=window.innerWidth;H=cv.height=window.innerHeight;}
resize();window.addEventListener("resize",resize);
class P{
  constructor(){this.reset();}
  reset(){this.x=Math.random()*W;this.y=Math.random()*H;this.vx=(Math.random()-.5)*.35;this.vy=(Math.random()-.5)*.35;this.r=Math.random()*1.5+.4;const c=Math.random();if(c<.5)this.col=`rgba(139,92,246,${Math.random()*.6+.2})`;else if(c<.8)this.col=`rgba(6,182,212,${Math.random()*.5+.2})`;else this.col=`rgba(236,72,153,${Math.random()*.4+.15})`;}
  update(){this.x+=this.vx;this.y+=this.vy;if(this.x<0||this.x>W||this.y<0||this.y>H)this.reset();}
  draw(){ctx.beginPath();ctx.arc(this.x,this.y,this.r,0,Math.PI*2);ctx.fillStyle=this.col;ctx.fill();}
}
for(let i=0;i<140;i++)pts.push(new P());
function lines(){for(let i=0;i<pts.length;i++){for(let j=i+1;j<pts.length;j++){const dx=pts[i].x-pts[j].x,dy=pts[i].y-pts[j].y,d=Math.sqrt(dx*dx+dy*dy);if(d<110){ctx.beginPath();ctx.moveTo(pts[i].x,pts[i].y);ctx.lineTo(pts[j].x,pts[j].y);ctx.strokeStyle=`rgba(139,92,246,${.12*(1-d/110)})`;ctx.lineWidth=.5;ctx.stroke();}}}}
function anim(){ctx.clearRect(0,0,W,H);pts.forEach(p=>{p.update();p.draw();});lines();requestAnimationFrame(anim);}
anim();

// TYPEWRITER
const phr=["AI & Machine Learning Developer 🤖","MERN Stack Explorer 🌐","Python | C | SQL Engineer 🐍","Microsoft Azure Developer ☁️","Final Year CSE @ Parul University 🎓","Open to Internships 🚀"];
let pi=0,ci=0,del=false;
const tw=document.getElementById("tw");
function type(){const p=phr[pi];if(!del){ci++;tw.innerHTML=p.slice(0,ci)+'<span class="cur"></span>';if(ci===p.length){del=true;setTimeout(type,1800);return;}setTimeout(type,65);}else{ci--;tw.innerHTML=p.slice(0,ci)+'<span class="cur"></span>';if(ci===0){del=false;pi=(pi+1)%phr.length;setTimeout(type,400);return;}setTimeout(type,38);}}
type();

// REVEAL
const revs=document.querySelectorAll(".rev");
const io=new IntersectionObserver(e=>{e.forEach(x=>{if(x.isIntersecting)x.target.classList.add("vis");});},{threshold:.1});
revs.forEach(r=>io.observe(r));

// README CONTENT
const rm=`<!-- PROFILE VIEWS -->
<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=jayesh982&color=blueviolet&style=for-the-badge&label=PROFILE+VIEWS)

</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,30:6E40C9,60:A855F7,100:06B6D4&height=220&section=header&text=CHEEDELLA%20JAYESH&fontSize=52&fontColor=ffffff&fontAlignY=40&desc=AI%20Developer%20%7C%20CSE%20Student%20%7C%20Python%20%7C%20MERN%20Stack&descAlignY=62&descAlign=50&animation=fadeIn" width="100%"/>
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1000&color=A855F7&center=true&vCenter=true&width=700&height=55&lines=🤖+AI+%26+Machine+Learning+Developer;🌐+MERN+Stack+Explorer;🐍+Python+%7C+C+%7C+SQL+Engineer;☁️+Microsoft+Azure+Cognitive+Services;🎓+Final+Year+CSE+%40+Parul+University;🚀+Open+to+Internships+%26+Collaborations" alt="Typing SVG"/>
</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jayesh-cheedella-579285295/)
[![Instagram](https://img.shields.io/badge/Instagram-@jayesh36876-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/jayesh36876)
[![LeetCode](https://img.shields.io/badge/LeetCode-jayesh234-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/jayesh234/)
[![Email](https://img.shields.io/badge/Email-jayeshcheedella@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jayeshcheedella@gmail.com)

</div>

---

## 🐍 Contribution Snake

<div align="center">
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</div>

---

## 👨‍💻 About Me

\\`\\`\\`python
class JayeshCheedella:
    def __init__(self):
        self.name       = "Cheedella Jayesh"
        self.role       = "Final-Year CSE Student & AI Developer"
        self.university = "Parul University, Gujarat (2023–2027)"
        self.location   = "Andhra Pradesh, India"
        self.cgpa       = 7.01
        self.languages  = ["English", "Telugu", "Hindi"]

    def get_skills(self):
        return {
            "core"  : ["Python", "C", "SQL"],
            "web"   : ["React.js", "Node.js", "MongoDB", "HTML/CSS/JS"],
            "ai_ml" : ["Machine Learning", "Computer Vision", "Azure Cognitive Services"],
            "oops"  : ["Polymorphism", "Encapsulation", "Inheritance", "Abstraction"],
            "tools" : ["VS Code", "Postman", "CISCO Packet Tracer", "MS Excel"],
        }

    def currently_seeking(self):
        return "Internships | AI/ML Roles | Software Development"
\\`\\`\\`

---

## 🛠️ Tech Stack

### 💻 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

### 🌐 Web Technologies
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white)

### 🤖 AI / ML & Cloud
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-5C2D91?style=for-the-badge&logo=microsoft&logoColor=white)

### 🔧 Tools
![VS Code](https://img.shields.io/badge/VS%20Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![CISCO](https://img.shields.io/badge/CISCO-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)

---

## 🔴 Featured Project

### Smart Crime Detection & Analysis Using Artificial Intelligence

> AI-powered platform revolutionizing public safety through intelligent crime monitoring and real-time analysis.

| Feature | Details |
|---|---|
| 🤖 AI Core | Crime pattern detection & hotspot identification |
| 📊 Dashboard | Real-time analytics with visualizations & alerts |
| 🔐 Access Control | Role-based: Users, Officers, Analysts |
| 📝 Reporting | Incident & cybercrime reporting + case management |
| 🛠️ Tech Stack | React.js, Node.js, MongoDB, Python, ML Libraries |

---

## 🎓 Education

\\`\\`\\`
2023–2027  ──►  B.Tech CSE · Parul University, Gujarat        CGPA: 7.01
2021–2023  ──►  Intermediate · SDR's Junior College, AP       Grade: 88.9%
2021       ──►  SSC · Good Shepherd English Medium School     Grade: 85%
\\`\\`\\`

---

## 🏅 Certifications

| Certification | Issuer | Date |
|---|---|---|
| 🤖 Artificial Intelligence | Simplilearn | May 2025 |
| 🐍 Complete Python Bootcamp | Udemy | Completed |
| 🌐 Team Experts Program | TCS | May 2025 |
| 🧠 Machine Learning | Course Completion | Mar 2024 |

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=jayesh982&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A855F7&icon_color=06B6D4&text_color=ffffff" width="48%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=jayesh982&theme=tokyonight&hide_border=true&background=0D1117&ring=A855F7&fire=06B6D4" width="48%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jayesh982&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A855F7&text_color=ffffff" width="50%"/>

</div>

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=jayesh982&theme=darkhub&no-frame=true&margin-w=6&column=6" width="100%"/>
</div>

---

## 💪 Strengths

| 🧠 Problem Solving | 🔍 Attention to Detail | 🤝 Teamwork |
|---|---|---|
| ⚡ Quick Learning | 💬 Communication | 🎯 Goal-Oriented |

---

## 🌐 Languages Known

English &nbsp; Telugu &nbsp; Hindi

---

<div align="center">

### 🚀 Let's Build Something Amazing!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jayesh-cheedella-579285295/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/jayesh36876)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/jayesh234/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jayeshcheedella@gmail.com)

</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,50:A855F7,100:0D1117&height=120&section=footer" width="100%"/>
</div>`;

function copyReadme(){
  navigator.clipboard.writeText(rm).then(()=>{
    const b=document.querySelector(".cpbtn"),s=document.getElementById("cpst");
    b.textContent="✅ Copied!";b.style.background="linear-gradient(135deg,#10b981,#06b6d4)";
    s.textContent="README copied! Go to github.com/jayesh982/jayesh982 → Edit README.md → Paste → Commit";
    s.style.color="#10b981";
    setTimeout(()=>{b.innerHTML="📋 Copy GitHub README";b.style.background="";s.textContent="Click to copy the complete README.md";s.style.color="";},4500);
  });
}
</script>
</body>
</html>
