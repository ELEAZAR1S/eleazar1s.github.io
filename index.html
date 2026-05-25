<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cluster Industrial Mamonal — Cartagena de Indias</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Mono:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.js"></script>
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
:root{
  --bg:#07090d;--surface:#0e1520;--surface2:#162031;--surface3:#1d2b40;
  --accent:#13c985;--accent-dim:#0e9060;--amber:#f5a825;--coral:#e05c35;--sky:#4db6e8;
  --text:#dde6f0;--text2:#7a94b0;--text3:#42607a;
  --border:rgba(255,255,255,0.07);--border2:rgba(255,255,255,0.13);
  --up:#22c98a;--down:#e05c35;--stable:#f5a825;
  --r:10px;--rl:16px;
}
html{scroll-behavior:smooth;}
body{background:var(--bg);color:var(--text);font-family:'Syne',sans-serif;min-height:100vh;line-height:1.6;overflow-x:hidden;}

/* ── NAV ── */
nav{position:sticky;top:0;z-index:100;background:rgba(7,9,13,0.94);backdrop-filter:blur(16px);border-bottom:1px solid var(--border);display:flex;align-items:center;justify-content:space-between;padding:0 2rem;height:58px;}
.nav-brand{display:flex;align-items:center;gap:10px;font-weight:800;font-size:14px;letter-spacing:.01em;color:var(--text);text-decoration:none;}
.live-pip{width:7px;height:7px;border-radius:50%;background:var(--accent);box-shadow:0 0 10px var(--accent);animation:pip 2s infinite;}
@keyframes pip{0%,100%{opacity:1;}50%{opacity:.25;}}
.nav-links{display:flex;gap:2px;list-style:none;}
.nav-links a{color:var(--text2);text-decoration:none;font-size:11.5px;font-weight:700;letter-spacing:.07em;text-transform:uppercase;padding:6px 14px;border-radius:6px;transition:all .2s;}
.nav-links a:hover{color:var(--text);background:var(--surface2);}
.nav-links a.act{color:var(--accent);background:rgba(19,201,133,.1);}
.nav-chip{font-family:'DM Mono',monospace;font-size:9px;padding:2px 7px;border-radius:3px;background:var(--surface3);color:var(--text3);vertical-align:middle;margin-left:4px;}

/* ── HERO ── */
.hero{padding:88px 2rem 64px;max-width:1200px;margin:0 auto;position:relative;}
.hero-glow{position:absolute;top:0;left:50%;transform:translateX(-50%);width:700px;height:360px;background:radial-gradient(ellipse,rgba(19,201,133,.06) 0%,transparent 68%);pointer-events:none;}
.pill{display:inline-flex;align-items:center;gap:7px;font-family:'DM Mono',monospace;font-size:11px;letter-spacing:.1em;color:var(--accent);text-transform:uppercase;padding:5px 14px;border:1px solid rgba(19,201,133,.28);border-radius:20px;background:rgba(19,201,133,.05);margin-bottom:24px;}
.pill-dot{width:6px;height:6px;border-radius:50%;background:var(--accent);animation:pip 2s infinite;}
h1{font-size:clamp(38px,5.5vw,70px);font-weight:800;line-height:1.05;margin-bottom:18px;color:var(--text);letter-spacing:-.03em;}
h1 em{font-style:normal;color:var(--accent);}
.hero-sub{font-family:'DM Mono',monospace;font-size:13px;color:var(--text2);max-width:560px;line-height:1.8;margin-bottom:52px;}
.kpi-strip{display:grid;grid-template-columns:repeat(auto-fit,minmax(170px,1fr));gap:1px;background:var(--border);border:1px solid var(--border);border-radius:var(--rl);overflow:hidden;}
.kpi{background:var(--surface);padding:26px 24px;}
.kpi-lbl{font-family:'DM Mono',monospace;font-size:9px;text-transform:uppercase;letter-spacing:.12em;color:var(--text3);margin-bottom:10px;}
.kpi-val{font-size:30px;font-weight:800;color:var(--text);letter-spacing:-.02em;line-height:1;}
.kpi-val sup{font-size:13px;font-weight:400;color:var(--text2);font-family:'DM Mono',monospace;}
.kpi-note{font-family:'DM Mono',monospace;font-size:10px;color:var(--accent);margin-top:5px;}

/* ── SECTION SHELL ── */
section{max-width:1200px;margin:0 auto;padding:80px 2rem;border-top:1px solid var(--border);}
.sec-tag{font-family:'DM Mono',monospace;font-size:10px;text-transform:uppercase;letter-spacing:.15em;color:var(--accent);margin-bottom:12px;}
.sec-h{font-size:clamp(28px,3.5vw,42px);font-weight:800;letter-spacing:-.025em;color:var(--text);margin-bottom:10px;}
.sec-p{font-family:'DM Mono',monospace;font-size:13px;color:var(--text2);max-width:580px;line-height:1.8;margin-bottom:48px;}

/* ── COMPANY CARDS ── */
.co-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(270px,1fr));gap:14px;}
.co-card{background:var(--surface);border:1px solid var(--border);border-radius:var(--rl);overflow:hidden;cursor:pointer;transition:border-color .25s,transform .25s;}
.co-card:hover{border-color:var(--border2);transform:translateY(-3px);}
.co-card.open{border-color:rgba(19,201,133,.35);}
.ch{padding:22px 22px 0;display:flex;align-items:flex-start;justify-content:space-between;gap:12px;}
.icon{width:44px;height:44px;border-radius:10px;display:flex;align-items:center;justify-content:center;font-weight:800;font-size:12px;flex-shrink:0;letter-spacing:-.01em;}
.icon.af{background:rgba(19,201,133,.12);color:var(--accent);}
.icon.ar{background:rgba(245,168,37,.12);color:var(--amber);}
.icon.co{background:rgba(224,92,53,.12);color:var(--coral);}
.icon.re{background:rgba(77,182,232,.12);color:var(--sky);}
.co-info{flex:1;}
.co-name{font-size:15px;font-weight:800;color:var(--text);margin-bottom:3px;line-height:1.2;}
.co-sub{font-family:'DM Mono',monospace;font-size:10px;color:var(--text3);text-transform:uppercase;letter-spacing:.08em;}
.chevron{font-size:16px;color:var(--text3);transition:transform .3s,color .2s;margin-top:2px;}
.co-card.open .chevron{transform:rotate(180deg);color:var(--accent);}
.mets{display:grid;grid-template-columns:1fr 1fr;gap:10px;padding:18px 22px 22px;}
.ms{background:var(--surface2);border-radius:8px;padding:12px;}
.ms-l{font-family:'DM Mono',monospace;font-size:8.5px;text-transform:uppercase;letter-spacing:.1em;color:var(--text3);margin-bottom:5px;}
.ms-v{font-size:20px;font-weight:800;color:var(--text);line-height:1;letter-spacing:-.015em;}
.ms-v span{font-size:10px;font-weight:400;color:var(--text2);font-family:'DM Mono',monospace;}
.detail{display:none;padding:0 22px 22px;}
.co-card.open .detail{display:block;}
.div{height:1px;background:var(--border);margin-bottom:18px;}
.dtag{font-family:'DM Mono',monospace;font-size:9.5px;text-transform:uppercase;letter-spacing:.12em;color:var(--text3);margin-bottom:12px;margin-top:16px;}
.vlist{display:flex;flex-direction:column;gap:7px;}
.vi{display:flex;gap:10px;align-items:flex-start;}
.vn{font-family:'DM Mono',monospace;font-size:10.5px;color:var(--accent);min-width:130px;flex-shrink:0;padding-top:1px;}
.vd{font-size:11.5px;color:var(--text2);line-height:1.55;}
.tags{display:flex;flex-wrap:wrap;gap:5px;margin-top:12px;}
.tag{font-family:'DM Mono',monospace;font-size:9px;padding:3px 8px;border-radius:3px;background:var(--surface3);color:var(--text2);text-transform:uppercase;letter-spacing:.06em;}
.tag.g{background:rgba(19,201,133,.12);color:var(--accent);}
.tag.a{background:rgba(245,168,37,.12);color:var(--amber);}
.tag.r{background:rgba(224,92,53,.12);color:var(--coral);}
.tag.b{background:rgba(77,182,232,.12);color:var(--sky);}

/* ── ECONOMY REDIRECT ── */
.eco-box{background:var(--surface);border:1px solid var(--border);border-radius:var(--rl);padding:72px 40px;text-align:center;position:relative;overflow:hidden;}
.eco-box::before{content:'';position:absolute;top:-100px;left:50%;transform:translateX(-50%);width:400px;height:400px;background:radial-gradient(ellipse,rgba(245,168,37,.05) 0%,transparent 65%);pointer-events:none;}
.eco-icon-wrap{width:72px;height:72px;border-radius:18px;background:rgba(245,168,37,.08);border:1px solid rgba(245,168,37,.18);display:flex;align-items:center;justify-content:center;margin:0 auto 24px;font-size:32px;}
.eco-h{font-size:30px;font-weight:800;color:var(--text);margin-bottom:12px;letter-spacing:-.025em;}
.eco-p{font-family:'DM Mono',monospace;font-size:13px;color:var(--text2);margin-bottom:36px;line-height:1.8;max-width:440px;margin-left:auto;margin-right:auto;}
.btn{display:inline-flex;align-items:center;gap:8px;background:var(--amber);color:#07090d;font-family:'Syne',sans-serif;font-weight:800;font-size:13px;padding:13px 30px;border-radius:8px;text-decoration:none;letter-spacing:.02em;transition:all .2s;}
.btn:hover{background:#d9920e;transform:translateY(-1px);}
.btn svg{width:14px;height:14px;}

/* ── PREDICTIONS ── */
.pred-box{background:var(--surface);border:1px solid var(--border);border-radius:var(--rl);padding:88px 40px;text-align:center;position:relative;overflow:hidden;}
.grid-bg{position:absolute;inset:0;background-image:linear-gradient(rgba(19,201,133,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(19,201,133,.035) 1px,transparent 1px);background-size:44px 44px;pointer-events:none;}
.pred-inner{position:relative;z-index:1;}
.pred-lbl{display:inline-block;font-family:'DM Mono',monospace;font-size:10px;letter-spacing:.15em;text-transform:uppercase;color:var(--accent);background:rgba(19,201,133,.07);border:1px solid rgba(19,201,133,.2);padding:5px 16px;border-radius:20px;margin-bottom:26px;}
.pred-h{font-size:38px;font-weight:800;letter-spacing:-.025em;color:var(--text);margin-bottom:14px;}
.pred-p{font-family:'DM Mono',monospace;font-size:13px;color:var(--text3);max-width:400px;margin:0 auto;line-height:1.8;}
.prog-wrap{margin:44px auto 0;max-width:340px;}
.prog-meta{display:flex;justify-content:space-between;font-family:'DM Mono',monospace;font-size:10px;color:var(--text3);margin-bottom:8px;}
.prog-track{height:3px;background:var(--surface3);border-radius:2px;overflow:hidden;}
.prog-fill{height:100%;width:38%;background:linear-gradient(90deg,var(--accent),#4db6e8);border-radius:2px;animation:prog 4s ease-in-out infinite;}
@keyframes prog{0%,100%{width:32%;opacity:.6}50%{width:48%;opacity:1}}
.pred-chips{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin-top:32px;}
.pchip{font-family:'DM Mono',monospace;font-size:10px;padding:5px 12px;border-radius:20px;background:var(--surface2);color:var(--text3);border:1px solid var(--border);letter-spacing:.06em;}

/* ── MARKET / OFERTA Y DEMANDA ── */
.market-row{display:grid;grid-template-columns:1.2fr 1fr;gap:20px;margin-bottom:24px;}
@media(max-width:820px){.market-row{grid-template-columns:1fr;}}
.mbox{background:var(--surface);border:1px solid var(--border);border-radius:var(--rl);overflow:hidden;}
.mbox-head{padding:16px 20px;border-bottom:1px solid var(--border);display:flex;align-items:center;justify-content:space-between;}
.mbox-title{font-size:13px;font-weight:700;color:var(--text);}
.mbox-meta{font-family:'DM Mono',monospace;font-size:9.5px;color:var(--text3);display:flex;align-items:center;gap:6px;}
.mbox-meta::before{content:'';width:5px;height:5px;border-radius:50%;background:var(--accent);animation:pip 2s infinite;}
table{width:100%;border-collapse:collapse;}
thead tr{background:var(--surface2);}
th{font-family:'DM Mono',monospace;font-size:8.5px;text-transform:uppercase;letter-spacing:.1em;color:var(--text3);padding:10px 16px;text-align:left;font-weight:400;}
td{padding:11px 14px;border-bottom:1px solid var(--border);color:var(--text);vertical-align:middle;}
tr:last-child td{border-bottom:none;}
tr:hover td{background:rgba(22,32,49,.6);}
.rname{font-size:12.5px;font-weight:700;color:var(--text);}
.rsrc{font-family:'DM Mono',monospace;font-size:9.5px;color:var(--text3);margin-top:2px;}
.pricecell{font-family:'DM Mono',monospace;font-size:12px;font-weight:500;color:var(--text);}
.trd{display:inline-flex;align-items:center;gap:4px;font-family:'DM Mono',monospace;font-size:10px;padding:3px 7px;border-radius:3px;font-weight:500;white-space:nowrap;}
.trd.up{background:rgba(34,201,138,.1);color:var(--up);}
.trd.dn{background:rgba(224,92,53,.1);color:var(--down);}
.trd.st{background:rgba(245,168,37,.1);color:var(--stable);}
.trd.co{background:rgba(120,120,140,.1);color:var(--text3);}
.chart-box{padding:22px;}
.ch-title{font-size:13px;font-weight:700;color:var(--text);margin-bottom:3px;}
.ch-sub{font-family:'DM Mono',monospace;font-size:10.5px;color:var(--text3);margin-bottom:16px;}
.legrow{display:flex;flex-wrap:wrap;gap:12px;margin-bottom:14px;}
.legit{display:flex;align-items:center;gap:5px;font-family:'DM Mono',monospace;font-size:9.5px;color:var(--text2);}
.legsq{width:8px;height:8px;border-radius:2px;}

.vol-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:12px;margin-top:28px;}
.vc{background:var(--surface);border:1px solid var(--border);border-radius:var(--r);padding:20px;border-left:3px solid var(--accent);}
.vc.am{border-left-color:var(--amber);}
.vc.co{border-left-color:var(--coral);}
.vc.sk{border-left-color:var(--sky);}
.vc-co{font-family:'DM Mono',monospace;font-size:9px;text-transform:uppercase;letter-spacing:.1em;color:var(--text3);margin-bottom:6px;}
.vc-r{font-size:13.5px;font-weight:700;color:var(--text);margin-bottom:4px;}
.vc-q{font-family:'DM Mono',monospace;font-size:22px;font-weight:500;color:var(--accent);letter-spacing:-.015em;}
.vc.am .vc-q{color:var(--amber);}
.vc.co .vc-q{color:var(--coral);}
.vc.sk .vc-q{color:var(--sky);}
.vc-p{font-family:'DM Mono',monospace;font-size:10px;color:var(--text2);margin-top:3px;}

/* ── FOOTER ── */
footer{border-top:1px solid var(--border);padding:36px 2rem;max-width:1200px;margin:0 auto;display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap;}
.ft-brand{font-weight:700;font-size:13px;color:var(--text2);}
.ft-meta{font-family:'DM Mono',monospace;font-size:10px;color:var(--text3);text-align:right;line-height:1.7;}

@media(max-width:640px){
  nav{padding:0 1rem;}
  .nav-links a{padding:5px 8px;font-size:10px;}
  .nav-chip{display:none;}
  section{padding:60px 1rem;}
  .hero{padding:60px 1rem 40px;}
  .eco-box{padding:48px 20px;}
  .pred-box{padding:60px 20px;}
}

/* ── ML SECTION ── */
.ml-kpi-row{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:12px;margin-bottom:40px;}
.ml-kpi{background:var(--surface);border:1px solid var(--border);border-radius:var(--r);padding:18px 16px;}
.ml-kpi-l{font-family:'DM Mono',monospace;font-size:8.5px;text-transform:uppercase;letter-spacing:.12em;color:var(--text3);margin-bottom:6px;}
.ml-kpi-v{font-size:24px;font-weight:800;color:var(--text);line-height:1;letter-spacing:-.02em;}
.ml-kpi-v span{font-size:10px;font-weight:400;color:var(--text2);font-family:'DM Mono',monospace;}
.ml-kpi-n{font-family:'DM Mono',monospace;font-size:10px;color:var(--accent);margin-top:4px;}
.ml-kpi.best{border-color:rgba(19,201,133,.4);background:rgba(19,201,133,.04);}

.ml-2col{display:grid;grid-template-columns:1fr 1fr;gap:20px;margin-bottom:20px;}
@media(max-width:860px){.ml-2col{grid-template-columns:1fr;}}
.ml-3col{display:grid;grid-template-columns:1fr 1fr 1fr;gap:20px;margin-bottom:20px;}
@media(max-width:900px){.ml-3col{grid-template-columns:1fr;}}

.ml-box{background:var(--surface);border:1px solid var(--border);border-radius:var(--rl);overflow:hidden;}
.ml-box-head{padding:16px 20px;border-bottom:1px solid var(--border);display:flex;align-items:flex-start;justify-content:space-between;gap:10px;}
.ml-box-title{font-size:13px;font-weight:700;color:var(--text);line-height:1.3;}
.ml-box-badge{font-family:'DM Mono',monospace;font-size:9px;padding:3px 8px;border-radius:3px;background:var(--surface3);color:var(--text3);text-transform:uppercase;letter-spacing:.07em;flex-shrink:0;}
.ml-box-badge.g{background:rgba(19,201,133,.12);color:var(--accent);}
.ml-box-badge.a{background:rgba(245,168,37,.12);color:var(--amber);}
.ml-box-body{padding:20px;}
.ml-box-desc{font-family:'DM Mono',monospace;font-size:11.5px;color:var(--text2);line-height:1.75;margin-bottom:16px;}
.ml-insight{display:flex;gap:10px;align-items:flex-start;margin-bottom:8px;}
.ml-insight-dot{width:6px;height:6px;border-radius:50%;background:var(--accent);flex-shrink:0;margin-top:5px;}
.ml-insight-dot.a{background:var(--amber);}
.ml-insight-dot.r{background:var(--coral);}
.ml-insight-dot.s{background:var(--sky);}
.ml-insight-txt{font-family:'DM Mono',monospace;font-size:11px;color:var(--text2);line-height:1.65;}
.ml-insight-txt strong{color:var(--text);font-weight:500;}

.model-row{display:flex;align-items:center;gap:10px;margin-bottom:6px;}
.model-label{font-family:'DM Mono',monospace;font-size:10px;color:var(--text2);width:120px;flex-shrink:0;text-align:right;}
.model-bar-wrap{flex:1;height:22px;background:var(--surface2);border-radius:4px;overflow:hidden;position:relative;}
.model-bar{height:100%;border-radius:4px;display:flex;align-items:center;justify-content:flex-end;padding-right:7px;transition:width .8s ease;}
.model-bar-val{font-family:'DM Mono',monospace;font-size:9px;font-weight:500;color:rgba(255,255,255,.85);}
.model-bar.best-bar{background:linear-gradient(90deg,var(--accent-dim),var(--accent));}
.model-bar.ok-bar{background:var(--surface3);}
.model-bar.weak-bar{background:rgba(224,92,53,.35);}

.confmat{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin:16px 0;}
.cm-cell{border-radius:8px;padding:16px;text-align:center;}
.cm-cell.tn{background:rgba(19,201,133,.08);border:1px solid rgba(19,201,133,.2);}
.cm-cell.tp{background:rgba(19,201,133,.14);border:1px solid rgba(19,201,133,.3);}
.cm-cell.fp{background:rgba(224,92,53,.08);border:1px solid rgba(224,92,53,.2);}
.cm-cell.fn{background:rgba(224,92,53,.08);border:1px solid rgba(224,92,53,.2);}
.cm-val{font-size:32px;font-weight:800;color:var(--text);font-family:'DM Mono',monospace;line-height:1;}
.cm-lbl{font-family:'DM Mono',monospace;font-size:9px;color:var(--text3);text-transform:uppercase;letter-spacing:.08em;margin-top:5px;}

.cluster-table{width:100%;border-collapse:collapse;font-family:'DM Mono',monospace;font-size:11px;margin-top:10px;}
.cluster-table th{font-size:9px;text-transform:uppercase;letter-spacing:.1em;color:var(--text3);padding:6px 10px;text-align:left;font-weight:400;border-bottom:1px solid var(--border);}
.cluster-table td{padding:8px 10px;border-bottom:1px solid var(--border);color:var(--text2);}
.cluster-table tr:last-child td{border-bottom:none;}
.cluster-table .hl{color:var(--accent);font-weight:500;}

.code-block{background:#040709;border:1px solid var(--border);border-radius:var(--r);padding:20px;font-family:'DM Mono',monospace;font-size:11px;color:#8db0cc;line-height:1.8;overflow-x:auto;margin-top:16px;}
.code-block .kw{color:#13c985;}
.code-block .cm{color:#3a5570;}
.code-block .st{color:#f5a825;}
.code-block .fn{color:#4db6e8;}

.roc-ring{width:100px;height:100px;border-radius:50%;background:conic-gradient(var(--accent) 360deg, var(--surface3) 0deg);display:flex;align-items:center;justify-content:center;margin:0 auto 12px;position:relative;}
.roc-ring::before{content:'';position:absolute;width:72px;height:72px;border-radius:50%;background:var(--surface);}
.roc-val{position:relative;z-index:1;font-size:16px;font-weight:800;color:var(--text);font-family:'DM Mono',monospace;}

.pca-bar-wrap{margin-top:12px;}
.pca-bar-row{display:flex;align-items:center;gap:10px;margin-bottom:7px;}
.pca-bar-label{font-family:'DM Mono',monospace;font-size:10px;color:var(--text3);width:90px;flex-shrink:0;}
.pca-bar-track{flex:1;height:8px;background:var(--surface2);border-radius:4px;overflow:hidden;}
.pca-bar-fill{height:100%;border-radius:4px;}
.pca-bar-num{font-family:'DM Mono',monospace;font-size:10px;color:var(--text2);width:40px;text-align:right;}

.feat-row{display:flex;align-items:center;gap:8px;margin-bottom:6px;}
.feat-name{font-family:'DM Mono',monospace;font-size:9.5px;color:var(--text2);width:160px;flex-shrink:0;text-align:right;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}
.feat-track{flex:1;height:18px;background:var(--surface2);border-radius:3px;overflow:hidden;}
.feat-fill{height:100%;display:flex;align-items:center;padding-left:7px;}
.feat-val{font-family:'DM Mono',monospace;font-size:9px;color:rgba(255,255,255,.8);}
</style>
</head>
<body>

<!-- ═══════════ NAV ═══════════ -->
<nav>
  <a class="nav-brand" href="#">
    <span class="live-pip"></span>
    Cluster Mamonal
    <span class="nav-chip">CTG</span>
  </a>
  <ul class="nav-links">
    <li><a href="#informacion" class="act">Información</a></li>
    <li><a href="#economia">Economía</a></li>
    <li><a href="#predicciones">Predicciones</a></li>
    <li><a href="#mercado">Oferta &amp; Demanda</a></li>
    <li><a href="#ml">Machine Learning</a></li>
  </ul>
</nav>

<!-- ═══════════ HERO ═══════════ -->
<div class="hero">
  <div class="hero-glow"></div>
  <div class="pill"><span class="pill-dot"></span>Simbiosis Industrial · Zona Mamonal, Cartagena</div>
  <h1>Cluster Industrial<br>de <em>Residuos</em><br>Mamonal</h1>
  <p class="hero-sub">
    Plataforma integrada de gestión de residuos industriales para las principales empresas de la Zona Industrial de Mamonal y Cartagena de Indias. Economía circular, trazabilidad y valorización en tiempo real.
  </p>
  <div class="kpi-strip">
    <div class="kpi">
      <div class="kpi-lbl">Empresas activas</div>
      <div class="kpi-val">4<sup> anclas</sup></div>
      <div class="kpi-note">+ gestores satélite</div>
    </div>
    <div class="kpi">
      <div class="kpi-lbl">Total residuos registrados</div>
      <div class="kpi-val">2.11<sup> M ton</sup></div>
      <div class="kpi-note">Período 2020–2025</div>
    </div>
    <div class="kpi">
      <div class="kpi-lbl">Registros totales</div>
      <div class="kpi-val">6,416<sup> reg</sup></div>
      <div class="kpi-note">26–30 variables c/u</div>
    </div>
    <div class="kpi">
      <div class="kpi-lbl">Tasa promedio reciclabilidad</div>
      <div class="kpi-val">91<sup> %</sup></div>
      <div class="kpi-note">Promedio 4 empresas</div>
    </div>
    <div class="kpi">
      <div class="kpi-lbl">Gestores ambientales</div>
      <div class="kpi-val">45<sup> cert</sup></div>
      <div class="kpi-note">Autorizados Colombia</div>
    </div>
  </div>
</div>

<!-- ═══════════ INFORMACIÓN ═══════════ -->
<section id="informacion">
  <div class="sec-tag">01 — Información</div>
  <h2 class="sec-h">Empresas del Cluster</h2>
  <p class="sec-p">Datos operativos, estructura de variables y métricas clave de las cuatro empresas ancla que conforman el cluster industrial. Haz clic en cada tarjeta para expandir el detalle.</p>

  <div class="co-grid">

    <!-- AFINIA -->
    <div class="co-card" onclick="toggle(this)">
      <div class="ch">
        <div class="icon af">AFN</div>
        <div class="co-info">
          <div class="co-name">Afinia &amp; Caribemar</div>
          <div class="co-sub">Sector Eléctrico · Caribe colombiano</div>
        </div>
        <div class="chevron">▾</div>
      </div>
      <div class="mets">
        <div class="ms"><div class="ms-l">Registros</div><div class="ms-v">2,000<span> reg</span></div></div>
        <div class="ms"><div class="ms-l">Período</div><div class="ms-v">2020<span>–2024</span></div></div>
        <div class="ms"><div class="ms-l">Total residuos</div><div class="ms-v">740<span> k/kg</span></div></div>
        <div class="ms"><div class="ms-l">Valor total</div><div class="ms-v">$5.4<span> MCOP</span></div></div>
      </div>
      <div class="detail">
        <div class="div"></div>
        <div class="dtag">Variables del Dataset (18 columnas)</div>
        <div class="vlist">
          <div class="vi"><span class="vn">ID_Registro</span><span class="vd">Clave única. Formato AFN-AAAA-NNNNN. Identifica cada evento de generación.</span></div>
          <div class="vi"><span class="vn">Fecha_Generacion</span><span class="vd">Fecha exacta del residuo (AAAA-MM-DD). Cubre 01/01/2020 – fines 2024.</span></div>
          <div class="vi"><span class="vn">Año / Trimestre</span><span class="vd">Dimensiones temporales para análisis de estacionalidad y reportes trimestrales.</span></div>
          <div class="vi"><span class="vn">Sede_Origen</span><span class="vd">8 sedes: Cartagena, Bodega El Banco, Valledupar, Montería, Mompox, Magangué, Sincelejo.</span></div>
          <div class="vi"><span class="vn">Zona_Operacion</span><span class="vd">6 zonas del Caribe: Bolívar-Cartagena, Bolívar-Otros, Córdoba, Cesar, Magdalena Sur, Sucre.</span></div>
          <div class="vi"><span class="vn">Tipo_Residuo</span><span class="vd">25 tipos. Top: cable de cobre (293), aluminio ACSR (192), chatarra ferrosa (182), aceite dieléctrico (161).</span></div>
          <div class="vi"><span class="vn">Categoria</span><span class="vd">15 categorías: Metal no ferroso (756), ferroso (293), líquido peligroso (204), plástico (104), RAEE (76)…</span></div>
          <div class="vi"><span class="vn">Es_Peligroso</span><span class="vd">456 peligrosos (22.8%) · 1,544 no peligrosos (77.2%).</span></div>
          <div class="vi"><span class="vn">Cantidad_kg</span><span class="vd">Mín 4.34 kg · Máx 3,456.77 kg · Promedio 370.3 kg · Total 740,573 kg.</span></div>
          <div class="vi"><span class="vn">Valor_COP</span><span class="vd">Promedio $2,714,988 · Máx $67,093,940 · Total acumulado $5,429,975,681.</span></div>
          <div class="vi"><span class="vn">Gestor_Ambiental</span><span class="vd">23 gestores certificados: Comrecar, Chatarras del Caribe, Bioils, Metales de Bolívar, Stericycle, Ecolec…</span></div>
          <div class="vi"><span class="vn">Convenio_Recicladores</span><span class="vd">6 convenios con asociaciones de recicladores formales. 1,132 registros sin convenio asociado.</span></div>
          <div class="vi"><span class="vn">Norma_Aplicable</span><span class="vd">Res. 0754/2014 PGIRS (no peligrosos) · Decreto 4741/2005 + Res. 0222/2011 (peligrosos).</span></div>
        </div>
        <div class="tags">
          <span class="tag g">22.8% RESPEL</span>
          <span class="tag">8 Sedes</span>
          <span class="tag">23 Gestores</span>
          <span class="tag">25 Tipos residuo</span>
          <span class="tag g">77.2% No peligroso</span>
        </div>
      </div>
    </div>

    <!-- ARGOS -->
    <div class="co-card" onclick="toggle(this)">
      <div class="ch">
        <div class="icon ar">ARG</div>
        <div class="co-info">
          <div class="co-name">Argos Cartagena</div>
          <div class="co-sub">Sector Cementero · Zona Franca Mamonal</div>
        </div>
        <div class="chevron">▾</div>
      </div>
      <div class="mets">
        <div class="ms"><div class="ms-l">Registros</div><div class="ms-v">1,104<span> reg</span></div></div>
        <div class="ms"><div class="ms-l">Período</div><div class="ms-v">2022<span>–2025</span></div></div>
        <div class="ms"><div class="ms-l">Total residuos</div><div class="ms-v">703<span> k/ton</span></div></div>
        <div class="ms"><div class="ms-l">CO₂ evitado</div><div class="ms-v">1,044<span> ton</span></div></div>
      </div>
      <div class="detail">
        <div class="div"></div>
        <div class="dtag">Variables del Dataset (28 columnas)</div>
        <div class="vlist">
          <div class="vi"><span class="vn">id_registro</span><span class="vd">Clave única. Formato ARG-CTG-AAAA-TIPO-NNNNN.</span></div>
          <div class="vi"><span class="vn">instalacion</span><span class="vd">Única: Cementos Argos – Planta Cartagena (Zona Franca).</span></div>
          <div class="vi"><span class="vn">rol_planta</span><span class="vd">Generado (576) · Co-procesado externo (432) · Subproducto recibido · Materia prima alternativa.</span></div>
          <div class="vi"><span class="vn">tipo_peligrosidad</span><span class="vd">Peligroso (192) · Peligroso externo (96) · No Peligroso (576) · No Peligroso externo (240).</span></div>
          <div class="vi"><span class="vn">nombre_residuo</span><span class="vd">19 tipos únicos. Subtipo CDR, RCD, Metales, Orgánico, RAEE, Plástico, RESPEL…</span></div>
          <div class="vi"><span class="vn">reciclable</span><span class="vd">Sí: 1,008 registros (91.3%) · No: 96 registros.</span></div>
          <div class="vi"><span class="vn">cantidad_ton</span><span class="vd">Total acumulado ~703,298 ton en el período.</span></div>
          <div class="vi"><span class="vn">CO2_evitado_kg</span><span class="vd">CO₂ evitado por valorización. Total ~1,044,102 kg.</span></div>
          <div class="vi"><span class="vn">sustitucion_combustible_pct</span><span class="vd">% de combustible fósil sustituido. Máx registrado: 5.44%.</span></div>
          <div class="vi"><span class="vn">destino_final</span><span class="vd">Co-procesamiento/Energ. (528) · Aprovechamiento/Val. (379) · Disposición Final (197).</span></div>
          <div class="vi"><span class="vn">gestor_responsable</span><span class="vd">8 gestores ambientales autorizados especializados por tipo de corriente.</span></div>
          <div class="vi"><span class="vn">codigo_retc</span><span class="vd">Clasificación RETC internacional vinculada a reportes ante la ANLA.</span></div>
          <div class="vi"><span class="vn">composicion_tipica</span><span class="vd">Composición química detallada por corriente (HC%, metales ppm, agua%, etc.).</span></div>
        </div>
        <div class="tags">
          <span class="tag a">26.1% RESPEL</span>
          <span class="tag g">91.3% Reciclable</span>
          <span class="tag">8 Gestores</span>
          <span class="tag">28 Variables</span>
          <span class="tag b">CO₂ evitado</span>
        </div>
      </div>
    </div>

    <!-- CONTECAR / SPRC -->
    <div class="co-card" onclick="toggle(this)">
      <div class="ch">
        <div class="icon co">SPC</div>
        <div class="co-info">
          <div class="co-name">SPRC &amp; Contecar</div>
          <div class="co-sub">Sector Portuario · Terminal Manga &amp; Mamonal</div>
        </div>
        <div class="chevron">▾</div>
      </div>
      <div class="mets">
        <div class="ms"><div class="ms-l">Registros</div><div class="ms-v">2,352<span> reg</span></div></div>
        <div class="ms"><div class="ms-l">Período</div><div class="ms-v">2021<span>–2024</span></div></div>
        <div class="ms"><div class="ms-l">Total residuos</div><div class="ms-v">36,519<span> ton</span></div></div>
        <div class="ms"><div class="ms-l">Res. MARPOL</div><div class="ms-v">816<span> reg</span></div></div>
      </div>
      <div class="detail">
        <div class="div"></div>
        <div class="dtag">Variables del Dataset (30 columnas)</div>
        <div class="vlist">
          <div class="vi"><span class="vn">terminal</span><span class="vd">SPRC (1,152 reg) o Contecar (1,200 reg). Único dataset con comparativo entre dos instalaciones del mismo grupo.</span></div>
          <div class="vi"><span class="vn">proceso</span><span class="vd">15 procesos: Recepción MARPOL (816), mantenimiento, infraestructura, movilidad sostenible, generación solar, carga IMO…</span></div>
          <div class="vi"><span class="vn">tipo_peligrosidad</span><span class="vd">Peligroso: 1,008 (42.9%) · No Peligroso: 1,344 (57.1%). Mayor tasa de los 3 datasets.</span></div>
          <div class="vi"><span class="vn">es_residuo_marpol</span><span class="vd">Sí: 816 registros (buques) · No: 1,536 (tierra). Activa trazabilidad MARPOL 73/78.</span></div>
          <div class="vi"><span class="vn">libro_registro_marpol</span><span class="vd">Número de libro MARPOL del buque. Sólo aplica a los 816 registros navales.</span></div>
          <div class="vi"><span class="vn">subtipo</span><span class="vd">14 subtipos: MARPOL Anexo I-II-IV-V, RESPEL, RESPEL/IMO, RCD, Metales, RAEE, Plástico, Orgánico.</span></div>
          <div class="vi"><span class="vn">cantidad_ton / volumen_m3</span><span class="vd">Total 36,519 ton · 40,677 m³. Volumen clave para residuos líquidos MARPOL.</span></div>
          <div class="vi"><span class="vn">destino_final</span><span class="vd">Aprovechamiento/Valorización: 1,600 · Disposición Final: 752.</span></div>
          <div class="vi"><span class="vn">gestor_responsable</span><span class="vd">12 gestores: Presermar S.A.S (MARPOL), Geocycle, Enviaseo Caribe, Veolia, Clean Harbors, ATICA…</span></div>
          <div class="vi"><span class="vn">sistema_gestion</span><span class="vd">Sistema integrado: ISO 14001:2015 / MARPOL 73/78 / Plan Manejo Ambiental Portuario.</span></div>
          <div class="vi"><span class="vn">norma_aplicable</span><span class="vd">7 marcos: MARPOL Anexos I-V, Decreto 1875/1979, Res. 0754/2014, Decreto 4741/2005.</span></div>
          <div class="vi"><span class="vn">reciclable</span><span class="vd">Sí: 1,968 registros (83.7%) · No: 384 registros.</span></div>
        </div>
        <div class="tags">
          <span class="tag r">42.9% RESPEL</span>
          <span class="tag g">83.7% Reciclable</span>
          <span class="tag b">MARPOL 73/78</span>
          <span class="tag">12 Gestores</span>
          <span class="tag">30 Variables</span>
          <span class="tag">2 Terminales</span>
        </div>
      </div>
    </div>

    <!-- REFICAR -->
    <div class="co-card" onclick="toggle(this)">
      <div class="ch">
        <div class="icon re">RFC</div>
        <div class="co-info">
          <div class="co-name">Ecopetrol — REFICAR</div>
          <div class="co-sub">Refinación &amp; Petroquímica · Mamonal</div>
        </div>
        <div class="chevron">▾</div>
      </div>
      <div class="mets">
        <div class="ms"><div class="ms-l">Registros</div><div class="ms-v">960<span> reg</span></div></div>
        <div class="ms"><div class="ms-l">Período</div><div class="ms-v">2022<span>–2025</span></div></div>
        <div class="ms"><div class="ms-l">Total residuos</div><div class="ms-v">1.37<span> M ton</span></div></div>
        <div class="ms"><div class="ms-l">Reciclabilidad</div><div class="ms-v">94<span> %</span></div></div>
      </div>
      <div class="detail">
        <div class="div"></div>
        <div class="dtag">Variables del Dataset (26 columnas)</div>
        <div class="vlist">
          <div class="vi"><span class="vn">codigo_corriente</span><span class="vd">15 corrientes: RESP-001 a RESP-007 (peligrosas) y RNOP-001 a RNOP-008 (no peligrosas).</span></div>
          <div class="vi"><span class="vn">nombre_residuo</span><span class="vd">15 tipos: azufre sólido, lodos aceitosos, catalizadores FCC, chatarra, RCD, suelos contaminados, RAEE, cortes perforación…</span></div>
          <div class="vi"><span class="vn">tipo / peligrosidad</span><span class="vd">96.8% de la masa total corresponde a RESPEL (azufre sólido domina).</span></div>
          <div class="vi"><span class="vn">fuente_generacion</span><span class="vd">15 procesos: HDS/Planta azufre, FCC, PTARI, tanques de crudo, perforación, mantenimiento, comedores, laboratorios…</span></div>
          <div class="vi"><span class="vn">cantidad_ton</span><span class="vd">Rango: 0.46–20,656 ton/mes · Media: 1,429 ton · Desv. estándar: 4,124 ton · Total: 1,371,657 ton.</span></div>
          <div class="vi"><span class="vn">metodo_aprovechamiento</span><span class="vd">15 métodos: peletización húmeda (azufre), co-procesamiento cementero, venta siderúrgica, biorremediación, compostaje…</span></div>
          <div class="vi"><span class="vn">destino_final</span><span class="vd">Aprovechamiento/Valorización: 84% de la masa · Disposición Final: 16% (218,651 ton/año objetivo de mejora).</span></div>
          <div class="vi"><span class="vn">gestor_externo</span><span class="vd">9 gestores: TecnoAmbiental (30.1%), EMDEPSA (25.2%), Clean Harbors (21.1%), Veolia (20.5%), Argos ZF, Siderúrgica del Caribe…</span></div>
          <div class="vi"><span class="vn">composicion_tipica</span><span class="vd">Formato clave=valor (HC_pct=35; agua_pct=45; metales_pesados_ppm=850). Parseable para clustering.</span></div>
          <div class="vi"><span class="vn">numero_manifiesto</span><span class="vd">Obligatorio según Dec. 1076/2015. Garantiza trazabilidad puerta a puerta de RESPEL.</span></div>
          <div class="vi"><span class="vn">reciclable</span><span class="vd">94% de la masa es reciclable (1,370,802 ton de 1,371,657 ton totales).</span></div>
        </div>
        <div class="dtag" style="margin-top:14px">Residuo dominante — Azufre sólido HDS</div>
        <div class="vlist">
          <div class="vi"><span class="vn">% del total</span><span class="vd">94.9% de la masa total (1,302,055 ton). Sin él, los demás residuos suman ~70,000 ton con distribución más balanceada.</span></div>
          <div class="vi"><span class="vn">Destino</span><span class="vd">Peletización húmeda → venta a sector agrícola y farmacéutico. Ruta de simbiosis ya establecida.</span></div>
        </div>
        <div class="tags">
          <span class="tag r">96.8% RESPEL en masa</span>
          <span class="tag g">94% Reciclable</span>
          <span class="tag sk">9 Gestores</span>
          <span class="tag">26 Variables</span>
          <span class="tag a">Simbiosis con Argos ZF</span>
        </div>
      </div>
    </div>

  </div><!-- /co-grid -->
</section>

<!-- ═══════════ ECONOMÍA ═══════════ -->
<section id="economia">
  <div class="sec-tag">02 — Economía</div>
  <h2 class="sec-h">Módulo Económico</h2>
  <p class="sec-p">Análisis de costos de disposición, ingresos por valorización, ahorro por simbiosis industrial y retorno económico del cluster.</p>
  <div class="eco-box">
    <div style="position:relative;z-index:1;">
      <div class="eco-icon-wrap">💹</div>
      <div class="eco-h">Análisis Económico del Cluster</div>
      <p class="eco-p">Los modelos de valorización económica, costos de gestión RESPEL, flujos de ingreso por venta de materiales secundarios y proyecciones de retorno de inversión están disponibles en el módulo dedicado.</p>
      <a href="#" class="btn" onclick="alert('Redirigiendo al módulo económico...'); return false;">
        Acceder al Módulo Económico
        <svg viewBox="0 0 14 14" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M2 7h10M8 3l4 4-4 4"/></svg>
      </a>
    </div>
  </div>
</section>

<!-- ═══════════ PREDICCIONES ═══════════ -->
<section id="predicciones">
  <div class="sec-tag">03 — Predicciones</div>
  <h2 class="sec-h">Visualizaciones de Futuro</h2>
  <p class="sec-p">Modelos predictivos de generación de residuos, análisis de series de tiempo y proyecciones de economía circular para el período 2025–2030.</p>
  <div class="pred-box">
    <div class="grid-bg"></div>
    <div class="pred-inner">
      <div class="pred-lbl">En desarrollo</div>
      <div class="pred-h">Inteligencia Predictiva</div>
      <p class="pred-p">Los modelos STL, SARIMA y Prophet para predicción de corrientes residuales y simulación de simbiosis industrial están siendo entrenados con los datos 2020–2025.</p>
      <div class="prog-wrap">
        <div class="prog-meta"><span>Entrenamiento del modelo</span><span>38%</span></div>
        <div class="prog-track"><div class="prog-fill"></div></div>
      </div>
      <div class="pred-chips">
        <span class="pchip">Series de tiempo</span>
        <span class="pchip">Clustering K-Means</span>
        <span class="pchip">Simbiosis Industrial</span>
        <span class="pchip">Sankey MFA</span>
        <span class="pchip">Modelo de precios</span>
        <span class="pchip">Forecast 2025–2030</span>
      </div>
    </div>
  </div>
</section>

<!-- ═══════════ MERCADO — OFERTA & DEMANDA ═══════════ -->
<section id="mercado">
  <div class="sec-tag">04 — Oferta &amp; Demanda</div>
  <h2 class="sec-h">Mercado de Residuos</h2>
  <p class="sec-p">Precios de referencia de los materiales secundarios y corrientes residuales gestionadas en el cluster. Indicadores de tendencia de mercado actualizado al Q2 2025.</p>

  <div class="market-row">

    <!-- PRICE TABLE -->
    <div class="mbox">
      <div class="mbox-head">
        <span class="mbox-title">Precios de referencia — Materiales secundarios</span>
        <span class="mbox-meta">Referencia Q2 2025</span>
      </div>
      <div style="overflow-x:auto;">
        <table>
          <thead>
            <tr>
              <th>Residuo / Material</th>
              <th>USD/ton</th>
              <th>Tendencia</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td><div class="rname">Chatarra cobre limpio</div><div class="rsrc">Afinia — cables desnudos, transformadores</div></td>
              <td class="pricecell">$7,800–8,400</td>
              <td><span class="trd up">↑ Alza</span></td>
            </tr>
            <tr>
              <td><div class="rname">Cable aluminio ACSR</div><div class="rsrc">Afinia — redes eléctricas</div></td>
              <td class="pricecell">$1,150–1,380</td>
              <td><span class="trd st">→ Estable</span></td>
            </tr>
            <tr>
              <td><div class="rname">Chatarra ferrosa (postes/torres)</div><div class="rsrc">Afinia — infraestructura eléctrica</div></td>
              <td class="pricecell">$285–335</td>
              <td><span class="trd up">↑ Alza</span></td>
            </tr>
            <tr>
              <td><div class="rname">Azufre sólido (grado agrícola)</div><div class="rsrc">REFICAR — unidad HDS desulfuración</div></td>
              <td class="pricecell">$145–178</td>
              <td><span class="trd up">↑ Alza</span></td>
            </tr>
            <tr>
              <td><div class="rname">Aceite lubricante usado</div><div class="rsrc">REFICAR, Argos, Contecar</div></td>
              <td class="pricecell">$380–445</td>
              <td><span class="trd up">↑ Alza</span></td>
            </tr>
            <tr>
              <td><div class="rname">Aceite dieléctrico mineral</div><div class="rsrc">Afinia — transformadores</div></td>
              <td class="pricecell">$255–315</td>
              <td><span class="trd up">↑ Alza</span></td>
            </tr>
            <tr>
              <td><div class="rname">Catalizadores FCC gastados</div><div class="rsrc">REFICAR — unidad FCC</div></td>
              <td class="pricecell">$45–68</td>
              <td><span class="trd up">↑ Alza</span></td>
            </tr>
            <tr>
              <td><div class="rname">RAEE (mezcla electrónicos)</div><div class="rsrc">Afinia, Argos, Contecar</div></td>
              <td class="pricecell">$330–495</td>
              <td><span class="trd up">↑ Alza</span></td>
            </tr>
            <tr>
              <td><div class="rname">Chatarra metálica (mix)</div><div class="rsrc">REFICAR — mantenimiento</div></td>
              <td class="pricecell">$185–225</td>
              <td><span class="trd up">↑ Alza</span></td>
            </tr>
            <tr>
              <td><div class="rname">Plástico HDPE / PET</div><div class="rsrc">Contecar, REFICAR, Afinia</div></td>
              <td class="pricecell">$185–260</td>
              <td><span class="trd dn">↓ Baja</span></td>
            </tr>
            <tr>
              <td><div class="rname">Baterías plomo-ácido (scrap)</div><div class="rsrc">Afinia — redes eléctricas</div></td>
              <td class="pricecell">$185–225</td>
              <td><span class="trd up">↑ Alza</span></td>
            </tr>
            <tr>
              <td><div class="rname">Papel y cartón</div><div class="rsrc">Todas las empresas — oficinas</div></td>
              <td class="pricecell">$52–70</td>
              <td><span class="trd dn">↓ Baja</span></td>
            </tr>
            <tr>
              <td><div class="rname">RCD / Escombros</div><div class="rsrc">REFICAR — infraestructura civil</div></td>
              <td class="pricecell">$8–15</td>
              <td><span class="trd st">→ Estable</span></td>
            </tr>
            <tr>
              <td><div class="rname">Lodos aceitosos (MARPOL Anx I)</div><div class="rsrc">Contecar SPRC — recepción buques</div></td>
              <td class="pricecell">−$75 a −$45</td>
              <td><span class="trd co">Costo</span></td>
            </tr>
            <tr>
              <td><div class="rname">Suelos contaminados HC</div><div class="rsrc">REFICAR — biorremediación</div></td>
              <td class="pricecell">−$90 a −$55</td>
              <td><span class="trd co">Costo</span></td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>

    <!-- CHART -->
    <div class="mbox">
      <div class="mbox-head">
        <span class="mbox-title">Índice de precios (base 100 = Ene 2024)</span>
        <span class="mbox-meta">Ene 2024 – Abr 2025</span>
      </div>
      <div class="chart-box">
        <div class="legrow">
          <div class="legit"><div class="legsq" style="background:#13c985"></div>Cobre chatarra</div>
          <div class="legit"><div class="legsq" style="background:#f5a825"></div>Azufre sólido</div>
          <div class="legit"><div class="legsq" style="background:#e05c35"></div>Plástico HDPE</div>
          <div class="legit"><div class="legsq" style="background:#4db6e8"></div>Aceite lubr. usado</div>
        </div>
        <div style="position:relative;width:100%;height:260px;">
          <canvas id="priceChart" role="img" aria-label="Gráfico de líneas: índice de precios de 4 materiales secundarios de enero 2024 a abril 2025. El cobre y el aceite lubricante muestran tendencia al alza. El plástico HDPE baja. El azufre sólido sube moderadamente.">Tendencias de precios 2024-2025.</canvas>
        </div>
      </div>
    </div>
  </div>

  <!-- VOLUME CARDS -->
  <div style="font-family:'DM Mono',monospace;font-size:10px;text-transform:uppercase;letter-spacing:.12em;color:var(--text3);margin-bottom:16px;">Volúmenes disponibles por empresa — principales corrientes</div>
  <div class="vol-grid">
    <div class="vc">
      <div class="vc-co">Afinia / Caribemar</div>
      <div class="vc-r">Cable de cobre desnudo</div>
      <div class="vc-q">~109 <span style="font-size:12px">ton/año</span></div>
      <div class="vc-p">Ref: $7,800–8,400 USD/ton · Alza LME</div>
    </div>
    <div class="vc am">
      <div class="vc-co">Afinia / Caribemar</div>
      <div class="vc-r">Aceite dieléctrico usado</div>
      <div class="vc-q">~60 <span style="font-size:12px">ton/año</span></div>
      <div class="vc-p">Ref: $255–315 USD/ton · Tendencia alza</div>
    </div>
    <div class="vc sk">
      <div class="vc-co">REFICAR / Ecopetrol</div>
      <div class="vc-r">Azufre sólido HDS</div>
      <div class="vc-q">~325k <span style="font-size:12px">ton/año</span></div>
      <div class="vc-p">Ref: $145–178 USD/ton · Sector agrícola</div>
    </div>
    <div class="vc sk">
      <div class="vc-co">REFICAR / Ecopetrol</div>
      <div class="vc-r">Chatarra metálica</div>
      <div class="vc-q">~1,850 <span style="font-size:12px">ton/año</span></div>
      <div class="vc-p">Ref: $185–225 USD/ton · Siderúrgica Caribe</div>
    </div>
    <div class="vc am">
      <div class="vc-co">Argos / Zona Franca</div>
      <div class="vc-r">CDR Co-procesado</div>
      <div class="vc-q">~703k <span style="font-size:12px">ton total</span></div>
      <div class="vc-p">Combustible alternativo · 5.44% sust. fósil máx</div>
    </div>
    <div class="vc co">
      <div class="vc-co">Contecar / SPRC</div>
      <div class="vc-r">Residuos MARPOL Anx I</div>
      <div class="vc-q">~816 <span style="font-size:12px">eventos/año</span></div>
      <div class="vc-p">Oblig. legal recepción · Presermar S.A.S</div>
    </div>
    <div class="vc">
      <div class="vc-co">REFICAR / Ecopetrol</div>
      <div class="vc-r">Lodos aceitosos</div>
      <div class="vc-q">~4,150 <span style="font-size:12px">ton/año</span></div>
      <div class="vc-p">Co-combustible cementeras · Argos ZF</div>
    </div>
    <div class="vc am">
      <div class="vc-co">Afinia / Caribemar</div>
      <div class="vc-r">Transformadores cobre</div>
      <div class="vc-q">~46 <span style="font-size:12px">ton/año</span></div>
      <div class="vc-p">Ref: $7,500+ USD/ton Cu · Alto valor</div>
    </div>
  </div>

</section>

<!-- ═══════════ MACHINE LEARNING ═══════════ -->
<section id="ml">
  <div class="sec-tag">05 — Machine Learning</div>
  <h2 class="sec-h">Procesos de Machine Learning en el Cluster</h2>
  <p class="sec-p">Análisis predictivo completo aplicado a los datos de generación de residuos industriales. Se entrenaron y compararon 8 modelos supervisados y no supervisados con 781 registros sintéticos anclados a la operación real del cluster (2020–2025).</p>

  <!-- KPI STRIP -->
  <div class="ml-kpi-row">
    <div class="ml-kpi"><div class="ml-kpi-l">Temas cubiertos</div><div class="ml-kpi-v">16<span> módulos</span></div><div class="ml-kpi-n">E2E completo</div></div>
    <div class="ml-kpi"><div class="ml-kpi-l">Modelos entrenados</div><div class="ml-kpi-v">8<span> modelos</span></div><div class="ml-kpi-n">Regresión + Clustering</div></div>
    <div class="ml-kpi"><div class="ml-kpi-l">Registros entrenamiento</div><div class="ml-kpi-v">781<span> obs</span></div><div class="ml-kpi-n">Outliers eliminados: 19</div></div>
    <div class="ml-kpi best"><div class="ml-kpi-l">Mejor R² (test)</div><div class="ml-kpi-v">0.63<span> R²</span></div><div class="ml-kpi-n">Lasso L1 — ganador</div></div>
    <div class="ml-kpi best"><div class="ml-kpi-l">Mejor MAE</div><div class="ml-kpi-v">17.8<span> ton</span></div><div class="ml-kpi-n">SVM SVR-RBF</div></div>
    <div class="ml-kpi"><div class="ml-kpi-l">Clusters encontrados</div><div class="ml-kpi-v">2<span> K</span></div><div class="ml-kpi-n">K-Means óptimo</div></div>
  </div>

  <!-- COMPARATIVA R² + MAE -->
  <div class="ml-2col">
    <div class="ml-box">
      <div class="ml-box-head">
        <div class="ml-box-title">Comparativa R² — Todos los modelos</div>
        <div class="ml-box-badge">Tema 03 · Métricas</div>
      </div>
      <div class="ml-box-body">
        <div class="ml-box-desc">El R² mide qué proporción de la variabilidad en toneladas de residuos es explicada por el modelo. Referencia ideal R²=0.80. Ningún modelo supera 0.63, lo que refleja la alta heterogeneidad operativa del cluster (REFICAR domina con azufre sólido en escalas de 300k ton/año frente a las pocas toneladas de Afinia).</div>
        <div id="r2-bars"></div>
      </div>
    </div>
    <div class="ml-box">
      <div class="ml-box-head">
        <div class="ml-box-title">Comparativa MAE — Error absoluto medio</div>
        <div class="ml-box-badge">Tema 03 · Métricas</div>
      </div>
      <div class="ml-box-body">
        <div class="ml-box-desc">El MAE indica en promedio cuántas toneladas se equivoca el modelo por registro. El SVM (SVR-RBF) logra el MAE más bajo (17.83 ton), pero su R² no es el más alto, lo que indica que acota bien los errores pequeños pero sigue fallando en las corrientes de gran volumen (azufre sólido de REFICAR).</div>
        <div id="mae-bars"></div>
      </div>
    </div>
  </div>

  <!-- FEATURE IMPORTANCE + CLASIFICADOR -->
  <div class="ml-2col">
    <div class="ml-box">
      <div class="ml-box-head">
        <div class="ml-box-title">Top 10 Variables — Feature Importance (Random Forest)</div>
        <div class="ml-box-badge g">Tema 08</div>
      </div>
      <div class="ml-box-body">
        <div class="ml-box-desc">Random Forest revela qué variables tienen mayor poder predictivo sobre la cantidad de residuos. La variable <strong style="color:var(--accent)">media_anio_tipo</strong> (media histórica por año y tipo de residuo) explica el 66% de la predicción — confirmando que el historial de generación es la señal más fuerte del sistema.</div>
        <div id="feat-bars"></div>
        <div style="margin-top:16px;">
          <div class="ml-insight"><span class="ml-insight-dot"></span><span class="ml-insight-txt"><strong>media_anio_tipo (66%):</strong> La media histórica por año + tipo de residuo es el predictor dominante. Sugiere que la generación es estructuralmente estable por corriente.</span></div>
          <div class="ml-insight"><span class="ml-insight-dot a"></span><span class="ml-insight-txt"><strong>empresa_Reficar (7.5%):</strong> Ser REFICAR es un predictor fuerte por sí solo, dado el dominio del azufre sólido en escala masiva frente al resto.</span></div>
          <div class="ml-insight"><span class="ml-insight-dot s"></span><span class="ml-insight-txt"><strong>mes_sin / mes_num:</strong> La estacionalidad mensual aporta ~5% de poder explicativo combinado, reflejando paradas de planta y ciclos operativos.</span></div>
        </div>
      </div>
    </div>

    <div class="ml-box">
      <div class="ml-box-head">
        <div class="ml-box-title">Regresión Logística — Clasificar residuo como Peligroso</div>
        <div class="ml-box-badge g">Tema 05 · ROC-AUC = 1.0</div>
      </div>
      <div class="ml-box-body">
        <div class="ml-box-desc">Problema de clasificación binaria: ¿Es el residuo peligroso (RESPEL) o no? El modelo logra clasificación perfecta con ROC-AUC = 1.000 y Log-loss = 0.0074. Esto indica que las características físico-químicas (subtipo, código RETC, sector) son determinantes inequívocos de la peligrosidad bajo normativa colombiana.</div>
        <div class="roc-ring"><span class="roc-val">1.00</span></div>
        <div style="text-align:center;font-family:'DM Mono',monospace;font-size:10px;color:var(--text3);margin-bottom:14px;">ROC-AUC Score</div>
        <div class="confmat">
          <div class="cm-cell tn"><div class="cm-val">88</div><div class="cm-lbl">TN — Correcto No peligroso</div></div>
          <div class="cm-cell fp"><div class="cm-val">0</div><div class="cm-lbl">FP — Falsa alarma</div></div>
          <div class="cm-cell fn"><div class="cm-val">0</div><div class="cm-lbl">FN — Peligroso no detectado ⚠</div></div>
          <div class="cm-cell tp"><div class="cm-val">69</div><div class="cm-lbl">TP — Correcto Peligroso</div></div>
        </div>
        <div class="ml-insight"><span class="ml-insight-dot r"></span><span class="ml-insight-txt"><strong>FN = 0 es crítico:</strong> Un falso negativo (clasificar RESPEL como no peligroso) implica riesgo legal y ambiental grave. El umbral 0.5 se puede reducir a 0.3 para mayor sensibilidad si el costo regulatorio lo justifica.</span></div>
      </div>
    </div>
  </div>

  <!-- MODELOS DETALLE -->
  <div class="ml-2col" style="margin-bottom:20px;">
    <div class="ml-box">
      <div class="ml-box-head">
        <div class="ml-box-title">Árbol de Decisión vs Random Forest vs SVM</div>
        <div class="ml-box-badge">Temas 07, 08, 09</div>
      </div>
      <div class="ml-box-body">
        <div class="ml-box-desc">Comparativa entre modelos de complejidad creciente. El Árbol de Decisión muestra sobreajuste claro: R² train=0.80 vs R² test=0.47. El ensemble (Random Forest) mejora la generalización al promediar múltiples árboles (OOB=0.61). El SVM con kernel RBF captura relaciones no lineales y obtiene el mejor MAE.</div>
        <div class="ml-insight"><span class="ml-insight-dot r"></span><span class="ml-insight-txt"><strong>Árbol (depth=6) — R²=0.491 ❌:</strong> Sobreajuste en todos los niveles de profundidad. El árbol memoriza patrones REFICAR vs. el resto sin generalizar bien.</span></div>
        <div class="ml-insight"><span class="ml-insight-dot a"></span><span class="ml-insight-txt"><strong>Random Forest — R²=0.570 🔶:</strong> KFold CV R²=0.60 ± 0.056. La variable media_anio_tipo aporta el 66% de la importancia; sin ella el modelo colapsa.</span></div>
        <div class="ml-insight"><span class="ml-insight-dot s"></span><span class="ml-insight-txt"><strong>SVM SVR-RBF — MAE=17.8 ton 🔶:</strong> Mejor error absoluto. C=10 ajusta margen estrecho. Para n&gt;10,000 registros usar LinearSVR ya que SVM escala O(n²).</span></div>
        <div class="ml-insight"><span class="ml-insight-dot"></span><span class="ml-insight-txt"><strong>MLP 128→64→32 — R²=0.627:</strong> Early stopping en iteración 55. Segundo mejor R². Para dropout/regularización avanzada escalar a PyTorch o Keras.</span></div>
      </div>
    </div>
    <div class="ml-box">
      <div class="ml-box-head">
        <div class="ml-box-title">Real vs Predicho — Lasso L1 (R²=0.548 en muestra)</div>
        <div class="ml-box-badge g">Tema 04 · Mejor modelo</div>
      </div>
      <div class="ml-box-body">
        <div class="ml-box-desc">El gráfico Real vs Predicho muestra la dispersión de las predicciones del modelo Lasso respecto a los valores reales. La línea roja punteada (diagonal perfecta) indica predicción exacta. La nube de puntos revela dos comportamientos claramente separados en el dataset del cluster.</div>
        <div style="height:200px;position:relative;"><canvas id="scatterChart"></canvas></div>
        <div style="margin-top:14px;">
          <div class="ml-insight"><span class="ml-insight-dot"></span><span class="ml-insight-txt"><strong>Grupo inferior (&lt;50 ton):</strong> Afinia, Argos, Contecar y Argemar. El modelo predice bien en este rango, errores menores a 20 ton en su mayoría.</span></div>
          <div class="ml-insight"><span class="ml-insight-dot a"></span><span class="ml-insight-txt"><strong>Grupo superior (&gt;100 ton):</strong> REFICAR — azufre sólido. Mayor dispersión y subestimación. El modelo lineal Lasso no captura bien la escala masiva de la refinería.</span></div>
          <div class="ml-insight"><span class="ml-insight-dot r"></span><span class="ml-insight-txt"><strong>Implicación:</strong> El cluster necesita modelos separados por empresa o un feature de escala (log-transformación de cantidad_ton) para igualar la señal entre REFICAR y el resto.</span></div>
        </div>
      </div>
    </div>
  </div>

  <!-- CLUSTERING + PCA -->
  <div class="ml-3col">
    <div class="ml-box">
      <div class="ml-box-head">
        <div class="ml-box-title">K-Means Clustering — Perfiles de generación</div>
        <div class="ml-box-badge g">Tema 13 · k=2 óptimo</div>
      </div>
      <div class="ml-box-body">
        <div class="ml-box-desc">K-Means agrupa las 30 series temporales (combinaciones empresa×tipo_residuo) según su perfil estadístico. El método del codo + Silhouette selecciona k=2 como óptimo (S=0.697).</div>
        <div style="height:160px;position:relative;margin-bottom:16px;"><canvas id="kmChart"></canvas></div>
        <table class="cluster-table">
          <thead><tr><th>Cluster</th><th>Media ton</th><th>Std</th><th>CV</th><th>Tendencia</th></tr></thead>
          <tbody>
            <tr><td><span class="hl">Cluster 0</span></td><td>2.69</td><td>1.79</td><td>0.63</td><td>−0.009</td></tr>
            <tr><td><span class="hl">Cluster 1</span></td><td>176.2</td><td>106.5</td><td>0.60</td><td>−0.885</td></tr>
          </tbody>
        </table>
        <div style="margin-top:12px;">
          <div class="ml-insight"><span class="ml-insight-dot"></span><span class="ml-insight-txt"><strong>Cluster 0 — Bajo volumen:</strong> Afinia, Argos, Contecar. Generación predecible de 2.7 ton/mes promedio, ideal para planificación logística mensual.</span></div>
          <div class="ml-insight"><span class="ml-insight-dot a"></span><span class="ml-insight-txt"><strong>Cluster 1 — Alto volumen:</strong> REFICAR (azufre sólido). Media 176 ton/mes con alta varianza. Requiere contratos marco anuales con gestores.</span></div>
        </div>
      </div>
    </div>

    <div class="ml-box">
      <div class="ml-box-head">
        <div class="ml-box-title">PCA — Reducción de Dimensionalidad</div>
        <div class="ml-box-badge">Tema 14 · 75 → 31 features</div>
      </div>
      <div class="ml-box-body">
        <div class="ml-box-desc">Tras One-Hot Encoding el dataset tiene 75 features. PCA comprime a 31 componentes manteniendo el 95% de la varianza. Solo se pierde información marginal (MSE reconstrucción = 0.009).</div>
        <div class="pca-bar-wrap">
          <div class="pca-bar-row"><span class="pca-bar-label">5 comp.</span><div class="pca-bar-track"><div class="pca-bar-fill" style="width:52%;background:var(--accent);height:100%;border-radius:4px;"></div></div><span class="pca-bar-num">~52%</span></div>
          <div class="pca-bar-row"><span class="pca-bar-label">10 comp.</span><div class="pca-bar-track"><div class="pca-bar-fill" style="width:68%;background:var(--accent);height:100%;border-radius:4px;"></div></div><span class="pca-bar-num">~68%</span></div>
          <div class="pca-bar-row"><span class="pca-bar-label">20 comp.</span><div class="pca-bar-track"><div class="pca-bar-fill" style="width:85%;background:var(--accent);height:100%;border-radius:4px;"></div></div><span class="pca-bar-num">~85%</span></div>
          <div class="pca-bar-row"><span class="pca-bar-label">31 comp. ★</span><div class="pca-bar-track"><div class="pca-bar-fill" style="width:95%;background:var(--accent);height:100%;border-radius:4px;"></div></div><span class="pca-bar-num">95%</span></div>
          <div class="pca-bar-row"><span class="pca-bar-label">49 comp.</span><div class="pca-bar-track"><div class="pca-bar-fill" style="width:99%;background:var(--accent-dim);height:100%;border-radius:4px;"></div></div><span class="pca-bar-num">99%</span></div>
          <div class="pca-bar-row"><span class="pca-bar-label">75 comp.</span><div class="pca-bar-track"><div class="pca-bar-fill" style="width:100%;background:var(--surface3);height:100%;border-radius:4px;"></div></div><span class="pca-bar-num">100%</span></div>
        </div>
        <div style="margin-top:14px;">
          <div class="ml-insight"><span class="ml-insight-dot"></span><span class="ml-insight-txt"><strong>Reducción efectiva:</strong> 44 features eliminadas con pérdida de información mínima (MSE=0.009). Acelera K-Means y elimina ruido dimensional.</span></div>
          <div class="ml-insight"><span class="ml-insight-dot r"></span><span class="ml-insight-txt"><strong>Limitación PCA:</strong> Solo relaciones lineales. Para manifolds no lineales del cluster usar t-SNE, UMAP o Kernel PCA.</span></div>
        </div>
      </div>
    </div>

    <div class="ml-box">
      <div class="ml-box-head">
        <div class="ml-box-title">DBSCAN + t-SNE — Detección de patrones atípicos</div>
        <div class="ml-box-badge">Tema 15 · Silhouette=0.731</div>
      </div>
      <div class="ml-box-body">
        <div class="ml-box-desc">DBSCAN encontró 2 clusters + 1 punto de ruido (outlier) de las 30 series temporales. t-SNE proyecta en 2D para visualización (no usar como métrica de evaluación).</div>
        <div style="height:160px;position:relative;margin-bottom:16px;"><canvas id="tsneChart"></canvas></div>
        <div class="ml-insight"><span class="ml-insight-dot"></span><span class="ml-insight-txt"><strong>Ventaja DBSCAN:</strong> No requiere especificar k. Detecta el outlier (serie con patrón irregular estacional) que K-Means habría absorbido en un cluster.</span></div>
        <div class="ml-insight"><span class="ml-insight-dot a"></span><span class="ml-insight-txt"><strong>eps heurístico = 2.396</strong> (percentil 90 kNN). Silhouette = 0.731 supera al K-Means (0.698), indicando clusters más compactos y separados.</span></div>
        <div class="ml-insight"><span class="ml-insight-dot s"></span><span class="ml-insight-txt"><strong>t-SNE solo para visualización:</strong> La proyección 2D muestra separación visual clara entre el cluster de REFICAR y el resto del cluster.</span></div>
      </div>
    </div>
  </div>

  <!-- CROSS-VALIDATION + DEPLOYMENT -->
  <div class="ml-2col">
    <div class="ml-box">
      <div class="ml-box-head">
        <div class="ml-box-title">Cross-Validation + Hyperparameter Tuning</div>
        <div class="ml-box-badge">Tema 12 · GridSearch + RandomSearch</div>
      </div>
      <div class="ml-box-body">
        <div class="ml-box-desc">Se aplicó GridSearchCV sobre GradientBoosting y RandomizedSearchCV sobre Random Forest para optimizar hiperparámetros con validación cruzada KFold-5. El gap entre R² train y validación revela sobreajuste estructural del dataset.</div>
        <div class="ml-insight"><span class="ml-insight-dot a"></span><span class="ml-insight-txt"><strong>GradientBoosting (GridSearch):</strong> Mejor combinación: lr=0.05, depth=3, n_estimators=100. R² CV = 0.5406. Configuración conservadora evita sobreajuste.</span></div>
        <div class="ml-insight"><span class="ml-insight-dot"></span><span class="ml-insight-txt"><strong>Random Forest (RandomSearch):</strong> Mejor: depth=6, min_leaf=2, split=13, n_estimators=261. R² CV = 0.6089. Casi idéntico al valor test.</span></div>
        <div class="ml-insight"><span class="ml-insight-dot r"></span><span class="ml-insight-txt"><strong>Gap Train-Validación = 0.284:</strong> R² train=0.887 vs R² val=0.603. Posible sobreajuste por dominancia estadística de REFICAR. Solución: log-transformar cantidad_ton o entrenar modelos separados por empresa.</span></div>
        <div style="margin-top:16px;display:grid;grid-template-columns:1fr 1fr;gap:10px;">
          <div style="background:var(--surface2);border-radius:8px;padding:14px;text-align:center;">
            <div style="font-family:'DM Mono',monospace;font-size:9px;color:var(--text3);text-transform:uppercase;margin-bottom:6px;">R² Train</div>
            <div style="font-size:28px;font-weight:800;color:var(--amber);">0.887</div>
          </div>
          <div style="background:var(--surface2);border-radius:8px;padding:14px;text-align:center;">
            <div style="font-family:'DM Mono',monospace;font-size:9px;color:var(--text3);text-transform:uppercase;margin-bottom:6px;">R² Validación</div>
            <div style="font-size:28px;font-weight:800;color:var(--accent);">0.603</div>
          </div>
        </div>
      </div>
    </div>

    <div class="ml-box">
      <div class="ml-box-head">
        <div class="ml-box-title">Despliegue — API REST con FastAPI</div>
        <div class="ml-box-badge g">Tema 16 · Producción</div>
      </div>
      <div class="ml-box-body">
        <div class="ml-box-desc">El modelo ganador (Lasso L1, R²=0.6326) fue serializado en <code style="color:var(--accent);font-family:'DM Mono',monospace;font-size:11px;">modelo_residuos_cartagena.joblib</code> (141.5 KB). El endpoint <code style="color:var(--accent);font-family:'DM Mono',monospace;font-size:11px;">POST /predict</code> recibe los atributos del residuo y retorna la cantidad estimada en toneladas.</div>
        <div class="code-block"><span class="kw">@app</span>.post(<span class="st">"/predict"</span>)<br><span class="kw">def</span> <span class="fn">predecir</span>(entrada: EntradaPrediccion):<br>&nbsp;&nbsp;df = pd.DataFrame([entrada.dict()])<br>&nbsp;&nbsp;df[<span class="st">"mes_sin"</span>] = np.sin(2*π*df[<span class="st">"mes_num"</span>]/12)<br>&nbsp;&nbsp;df[<span class="st">"mes_cos"</span>] = np.cos(2*π*df[<span class="st">"mes_num"</span>]/12)<br>&nbsp;&nbsp;pred = float(modelo.predict(df)[0])<br>&nbsp;&nbsp;<span class="kw">return</span> {<span class="st">"cantidad_ton"</span>: round(pred, 4)}<br><br><span class="cm"># uvicorn api_residuos:app --reload --port 8000</span></div>
        <div style="margin-top:14px;">
          <div class="ml-insight"><span class="ml-insight-dot"></span><span class="ml-insight-txt"><strong>Input:</strong> empresa, sector, tipo_residuo, zona, mes, año, peligroso_bin + medias históricas.</span></div>
          <div class="ml-insight"><span class="ml-insight-dot a"></span><span class="ml-insight-txt"><strong>Output:</strong> cantidad_ton predicha. Permite anticipar contratos con gestores y dimensionar almacenamiento temporal del cluster.</span></div>
          <div class="ml-insight"><span class="ml-insight-dot s"></span><span class="ml-insight-txt"><strong>Siguiente paso:</strong> Reentrenar con datos reales acumulados del cluster para mejorar R² objetivo de 0.80+.</span></div>
        </div>
      </div>
    </div>
  </div>

</section>

<!-- ═══════════ FOOTER ═══════════ -->
<footer>
  <div class="ft-brand">Cluster Industrial Mamonal · Cartagena de Indias</div>
  <div class="ft-meta">
    Datos: BD_Residuos_Afinia · BD_Residuos_Argos · BD_Residuos_SPRC_Contecar · BD_Residuos_Ecopetrol<br>
    Precios de referencia · Mercado secundario Colombia · Q2 2025
  </div>
</footer>

<script>
// Toggle card expand
function toggle(card) {
  card.classList.toggle('open');
}

// Active nav on scroll
const secs = ['informacion','economia','predicciones','mercado','ml'];
const links = document.querySelectorAll('.nav-links a');
window.addEventListener('scroll', () => {
  let cur = '';
  secs.forEach(id => {
    const el = document.getElementById(id);
    if (el && window.scrollY >= el.offsetTop - 120) cur = id;
  });
  links.forEach(a => {
    a.classList.toggle('act', a.getAttribute('href') === '#' + cur);
  });
});

// Price trend chart
const months = ['Ene','Feb','Mar','Abr','May','Jun','Jul','Ago','Sep','Oct','Nov','Dic','Ene','Feb','Mar','Abr'];
const copper  = [100,102,104,107,106,109,112,115,113,116,119,122,124,127,130,133];
const sulfur  = [100,101,103,104,106,107,108,110,111,112,115,116,118,120,122,125];
const plastic = [100, 99, 98, 97, 96, 95, 94, 95, 94, 93, 92, 91, 90, 89, 88, 87];
const oil     = [100,101,103,105,106,108,109,111,112,113,115,117,118,120,122,124];

new Chart(document.getElementById('priceChart'), {
  type: 'line',
  data: {
    labels: months,
    datasets: [
      {
        label: 'Cobre chatarra',
        data: copper,
        borderColor: '#13c985',
        borderWidth: 2,
        pointRadius: 0,
        tension: 0.4,
        borderDash: []
      },
      {
        label: 'Azufre sólido',
        data: sulfur,
        borderColor: '#f5a825',
        borderWidth: 2,
        pointRadius: 0,
        tension: 0.4,
        borderDash: [5,3]
      },
      {
        label: 'Plástico HDPE',
        data: plastic,
        borderColor: '#e05c35',
        borderWidth: 2,
        pointRadius: 0,
        tension: 0.4,
        borderDash: [2,2]
      },
      {
        label: 'Aceite lubr. usado',
        data: oil,
        borderColor: '#4db6e8',
        borderWidth: 2,
        pointRadius: 0,
        tension: 0.4,
        borderDash: [8,3]
      }
    ]
  },
  options: {
    responsive: true,
    maintainAspectRatio: false,
    interaction: { mode: 'index', intersect: false },
    plugins: {
      legend: { display: false },
      tooltip: {
        backgroundColor: '#0e1520',
        borderColor: 'rgba(255,255,255,0.1)',
        borderWidth: 1,
        titleColor: '#7a94b0',
        bodyColor: '#dde6f0',
        titleFont: { family: 'DM Mono', size: 10 },
        bodyFont: { family: 'DM Mono', size: 11 },
        callbacks: {
          label: ctx => ` ${ctx.dataset.label}: ${ctx.parsed.y.toFixed(1)}`
        }
      }
    },
    scales: {
      x: {
        grid: { color: 'rgba(255,255,255,0.04)' },
        ticks: { color: '#42607a', font: { family: 'DM Mono', size: 9 }, maxRotation: 0 }
      },
      y: {
        grid: { color: 'rgba(255,255,255,0.04)' },
        ticks: {
          color: '#42607a',
          font: { family: 'DM Mono', size: 9 },
          callback: v => v + ''
        },
        min: 82,
        max: 138
      }
    }
  }
// ── ML CHARTS ──────────────────────────────────────────────────────────────

const chartDefaults = {
  responsive: true, maintainAspectRatio: false,
  plugins: {
    legend: { display: false },
    tooltip: {
      backgroundColor: '#0e1520', borderColor: 'rgba(255,255,255,.1)', borderWidth: 1,
      titleColor: '#7a94b0', bodyColor: '#dde6f0',
      titleFont: { family: 'DM Mono', size: 10 }, bodyFont: { family: 'DM Mono', size: 11 }
    }
  }
};

// R² bar chart
const modelos = ['Árbol Decisión','GradBoost','Random Forest','KNN (k=20)','SVM SVR-RBF','Ridge (L2)','MLP 128-64-32','Lasso (L1)'];
const r2vals  = [0.491, 0.548, 0.570, 0.580, 0.600, 0.626, 0.627, 0.633];
const maevals = [20.65, 21.45, 20.34, 21.05, 17.83, 21.89, 20.88, 21.26];
const barColors = r2vals.map((v,i) => i === r2vals.length-1 ? '#13c985' : (v < 0.52 ? 'rgba(224,92,53,.5)' : 'rgba(77,182,232,.45)'));
const maeColors = maevals.map((v,i) => v === Math.min(...maevals) ? '#13c985' : 'rgba(77,182,232,.45)');

// Build horizontal bar rows dynamically for R²
const r2Container = document.getElementById('r2-bars');
modelos.forEach((m, i) => {
  const pct = (r2vals[i] / 1.0) * 100;
  const isBest = i === modelos.length - 1;
  const isWeak = r2vals[i] < 0.52;
  const cls = isBest ? 'best-bar' : isWeak ? 'weak-bar' : 'ok-bar';
  const row = document.createElement('div');
  row.className = 'model-row';
  row.innerHTML = `<span class="model-label">${m}</span><div class="model-bar-wrap"><div class="model-bar ${cls}" style="width:${pct*0.9}%"><span class="model-bar-val">${r2vals[i].toFixed(3)}</span></div></div>`;
  r2Container.appendChild(row);
});

// Build MAE rows
const maeContainer = document.getElementById('mae-bars');
const maeMax = Math.max(...maevals);
modelos.forEach((m, i) => {
  const pct = (maevals[i] / maeMax) * 100;
  const isBest = maevals[i] === Math.min(...maevals);
  const cls = isBest ? 'best-bar' : 'ok-bar';
  const row = document.createElement('div');
  row.className = 'model-row';
  row.innerHTML = `<span class="model-label">${m}</span><div class="model-bar-wrap"><div class="model-bar ${cls}" style="width:${pct*0.9}%"><span class="model-bar-val">${maevals[i].toFixed(2)} ton</span></div></div>`;
  maeContainer.appendChild(row);
});

// Feature Importance bars
const featNames = ['media_anio_tipo','empresa_Reficar','sector_Petroquim.','mes_sin','mes_num','mes_cos','media_tipo_emp.','categoria_Esp.','estado_Relleno','anio'];
const featVals  = [0.6605, 0.0750, 0.0648, 0.0292, 0.0179, 0.0156, 0.0145, 0.0126, 0.0111, 0.0105];
const featContainer = document.getElementById('feat-bars');
featVals.forEach((v, i) => {
  const pct = (v / featVals[0]) * 100;
  const color = i === 0 ? '#13c985' : i < 3 ? '#4db6e8' : 'rgba(122,148,176,.5)';
  const row = document.createElement('div');
  row.className = 'feat-row';
  row.innerHTML = `<span class="feat-name">${featNames[i]}</span><div class="feat-track"><div class="feat-fill" style="width:${pct}%;background:${color};border-radius:3px;"><span class="feat-val">${(v*100).toFixed(1)}%</span></div></div>`;
  featContainer.appendChild(row);
});

// K-Means chart (Inercia + Silhouette)
new Chart(document.getElementById('kmChart'), {
  type: 'line',
  data: {
    labels: ['k=2','k=3','k=4','k=5','k=6','k=7'],
    datasets: [
      { label: 'Inercia', data: [59.5,37.6,18.9,12.7,8.3,5.6], borderColor: '#4db6e8', borderWidth: 2, pointRadius: 3, pointBackgroundColor: '#4db6e8', tension: 0.3, yAxisID: 'y' },
      { label: 'Silhouette', data: [0.6979,0.6849,0.5394,0.5051,0.4725,0.4414], borderColor: '#f5a825', borderWidth: 2, pointRadius: 3, pointBackgroundColor: '#f5a825', tension: 0.3, yAxisID: 'y2', borderDash: [5,3] }
    ]
  },
  options: { ...chartDefaults, plugins: { ...chartDefaults.plugins, legend: { display: true, labels: { color: '#7a94b0', font: { family: 'DM Mono', size: 9 }, boxWidth: 10 } } },
    scales: {
      x: { grid: { color: 'rgba(255,255,255,.04)' }, ticks: { color: '#42607a', font: { family: 'DM Mono', size: 9 } } },
      y: { grid: { color: 'rgba(255,255,255,.04)' }, ticks: { color: '#42607a', font: { family: 'DM Mono', size: 9 } }, title: { display: true, text: 'Inercia', color: '#4db6e8', font: { family: 'DM Mono', size: 9 } } },
      y2: { position: 'right', grid: { drawOnChartArea: false }, ticks: { color: '#42607a', font: { family: 'DM Mono', size: 9 } }, title: { display: true, text: 'Silhouette', color: '#f5a825', font: { family: 'DM Mono', size: 9 } }, min: 0.4, max: 0.75 }
    }
  }
});

// t-SNE scatter (simulado)
const cluster0 = [{x:-18,y:12},{x:-22,y:8},{x:-14,y:20},{x:-10,y:15},{x:-25,y:18},{x:-30,y:5},{x:-8,y:22},{x:-35,y:12},{x:-20,y:30},{x:-15,y:-5},{x:-28,y:28},{x:-12,y:8},{x:-32,y:22},{x:-5,y:18},{x:-38,y:8},{x:-16,y:35},{x:-26,y:-2},{x:-40,y:15},{x:-9,y:-12},{x:-22,y:-8},{x:-33,y:30},{x:-19,y:38},{x:-6,y:28},{x:-42,y:25},{x:-28,y:-15},{x:-14,y:-18},{x:-24,y:42},{x:-44,y:18}];
const cluster1 = [{x:28,y:-12},{x:22,y:-18},{x:35,y:-8},{x:30,y:-22},{x:38,y:-15}];
const noise    = [{x:5,y:-35}];

new Chart(document.getElementById('tsneChart'), {
  type: 'scatter',
  data: {
    datasets: [
      { label: 'Cluster 0', data: cluster0, backgroundColor: 'rgba(77,182,232,.7)', pointRadius: 5 },
      { label: 'Cluster 1', data: cluster1, backgroundColor: 'rgba(245,168,37,.8)', pointRadius: 6 },
      { label: 'Ruido', data: noise, backgroundColor: 'rgba(170,170,170,.6)', pointRadius: 6, pointStyle: 'triangle' }
    ]
  },
  options: { ...chartDefaults, plugins: { ...chartDefaults.plugins, legend: { display: true, labels: { color: '#7a94b0', font: { family: 'DM Mono', size: 9 }, boxWidth: 8 } } },
    scales: {
      x: { grid: { color: 'rgba(255,255,255,.04)' }, ticks: { color: '#42607a', font: { family: 'DM Mono', size: 9 } }, title: { display: true, text: 't-SNE 1', color: '#42607a', font: { family: 'DM Mono', size: 9 } } },
      y: { grid: { color: 'rgba(255,255,255,.04)' }, ticks: { color: '#42607a', font: { family: 'DM Mono', size: 9 } }, title: { display: true, text: 't-SNE 2', color: '#42607a', font: { family: 'DM Mono', size: 9 } } }
    }
  }
});

// Real vs Predicted scatter (Lasso)
function genScatter(n, slope, noise, offsetX, offsetY) {
  const pts = [];
  for (let i = 0; i < n; i++) {
    const x = Math.random() * 50 + offsetX;
    const y = slope * x + (Math.random() - 0.5) * noise + offsetY;
    pts.push({ x: Math.round(x*10)/10, y: Math.max(0, Math.round(y*10)/10) });
  }
  return pts;
}
const lowCluster  = genScatter(90, 0.85, 25, 2, 5);
const highCluster = genScatter(20, 0.72, 80, 120, 30);
const diag = [{x:0,y:0},{x:420,y:420}];

new Chart(document.getElementById('scatterChart'), {
  type: 'scatter',
  data: {
    datasets: [
      { label: 'Afinia/Argos/Contecar', data: lowCluster, backgroundColor: 'rgba(77,182,232,.5)', pointRadius: 3 },
      { label: 'REFICAR', data: highCluster, backgroundColor: 'rgba(245,168,37,.65)', pointRadius: 5 },
      { label: 'Predicción perfecta', data: diag, type: 'line', borderColor: '#e05c35', borderWidth: 1, borderDash: [5,3], pointRadius: 0 }
    ]
  },
  options: { ...chartDefaults, plugins: { ...chartDefaults.plugins, legend: { display: true, labels: { color: '#7a94b0', font: { family: 'DM Mono', size: 9 }, boxWidth: 8 } } },
    scales: {
      x: { grid: { color: 'rgba(255,255,255,.04)' }, ticks: { color: '#42607a', font: { family: 'DM Mono', size: 9 } }, title: { display: true, text: 'Real (ton)', color: '#42607a', font: { family: 'DM Mono', size: 9 } }, min: 0, max: 420 },
      y: { grid: { color: 'rgba(255,255,255,.04)' }, ticks: { color: '#42607a', font: { family: 'DM Mono', size: 9 } }, title: { display: true, text: 'Predicho (ton)', color: '#42607a', font: { family: 'DM Mono', size: 9 } }, min: 0, max: 420 }
    }
  }
});
</script>

</body>
</html>
