cat > /mnt/user-data/outputs/nexus-planner.html << 'HTMLEOF'
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NEXUS — Monthly Planner OS</title>
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Rajdhani:wght@300;400;500;600;700&family=Share+Tech+Mono&display=swap" rel="stylesheet">
<style>
:root {
  --black:#050508;--deep:#080b14;--panel:rgba(10,15,30,0.78);
  --blue:#00c8ff;--blue2:#0080ff;--purple:#b040ff;--purple2:#7020cc;
  --cyan:#00ffe0;--pink:#ff4da6;--rose:#ff2d78;--lavender:#c9a0ff;
  --emerald:#00ffaa;--silver:#c8d8f0;--gold:#ffd060;
  --text:#e0eaff;--muted:#6a7fa8;
  --border:rgba(0,200,255,0.15);--border2:rgba(176,64,255,0.2);
  --glow-blue:0 0 12px rgba(0,200,255,0.35),0 0 30px rgba(0,200,255,0.12);
  --glow-purple:0 0 12px rgba(176,64,255,0.4),0 0 30px rgba(176,64,255,0.15);
  --glow-pink:0 0 12px rgba(255,77,166,0.38),0 0 28px rgba(255,45,120,0.12);
  --glow-emerald:0 0 10px rgba(0,255,170,0.3);
}
*{box-sizing:border-box;margin:0;padding:0;}
body{background:var(--black);color:var(--text);font-family:'Rajdhani',sans-serif;min-height:100vh;overflow-x:hidden;}
/* BG */
.bg{position:fixed;inset:0;z-index:0;overflow:hidden;
  background:radial-gradient(ellipse 120% 80% at 15% 20%,rgba(0,80,200,0.1) 0%,transparent 60%),
  radial-gradient(ellipse 80% 60% at 85% 75%,rgba(140,30,220,0.1) 0%,transparent 55%),
  linear-gradient(160deg,#050508 0%,#08091a 40%,#060412 70%,#050508 100%);}
.bg-grid{position:absolute;inset:0;
  background-image:linear-gradient(rgba(0,150,255,0.04) 1px,transparent 1px),linear-gradient(90deg,rgba(0,150,255,0.04) 1px,transparent 1px);
  background-size:48px 48px;}
.bg-glow{position:absolute;border-radius:50%;filter:blur(80px);pointer-events:none;}
.bg-glow-1{width:500px;height:300px;top:-80px;left:-100px;background:rgba(0,100,255,0.07);}
.bg-glow-2{width:400px;height:400px;bottom:100px;right:-100px;background:rgba(140,30,220,0.08);}
/* PARTICLES */
.particles{position:fixed;inset:0;z-index:0;pointer-events:none;}
.particle{position:absolute;width:2px;height:2px;border-radius:50%;opacity:0;animation:float-particle linear infinite;}
@keyframes float-particle{0%{opacity:0;transform:translateY(100vh) scale(0);}10%{opacity:.5;}90%{opacity:.2;}100%{opacity:0;transform:translateY(-20px) scale(1.5);}}
/* LAYOUT */
.page{position:relative;z-index:1;max-width:1440px;margin:0 auto;padding:22px 20px 48px;}
/* HEADER */
.header{display:flex;align-items:center;justify-content:space-between;margin-bottom:20px;padding:14px 24px;
  background:rgba(8,12,28,0.85);border:1px solid var(--border);border-radius:18px;
  backdrop-filter:blur(20px);box-shadow:var(--glow-blue),inset 0 1px 0 rgba(255,255,255,0.04);}
.logo{font-family:'Orbitron',sans-serif;font-size:24px;font-weight:900;
  background:linear-gradient(135deg,var(--blue),var(--purple),var(--cyan));
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;letter-spacing:4px;
  filter:drop-shadow(0 0 8px rgba(0,200,255,0.35));}
.logo-sub{font-family:'Share Tech Mono',monospace;font-size:9px;color:var(--muted);letter-spacing:3px;margin-top:2px;}
.header-center{text-align:center;}
.header-month{font-family:'Orbitron',sans-serif;font-size:13px;letter-spacing:5px;color:var(--blue);cursor:pointer;transition:color .2s;}
.header-month:hover{color:var(--cyan);}
.header-sub{font-family:'Share Tech Mono',monospace;font-size:9px;color:var(--muted);letter-spacing:2px;margin-top:3px;}
.header-right{display:flex;align-items:center;gap:12px;}
.status-dot{width:8px;height:8px;border-radius:50%;background:var(--emerald);
  box-shadow:0 0 8px var(--emerald),0 0 16px rgba(0,255,170,0.3);animation:pulse-dot 2s ease-in-out infinite;}
@keyframes pulse-dot{0%,100%{transform:scale(1);opacity:1;}50%{transform:scale(1.4);opacity:.7;}}
.h-stat{font-family:'Share Tech Mono',monospace;font-size:10px;color:var(--muted);cursor:pointer;}
.h-stat span{color:var(--cyan);}
/* BTN ROW */
.btn-row{display:flex;gap:10px;margin-bottom:20px;flex-wrap:wrap;}
.btn{padding:8px 18px;border-radius:10px;font-family:'Orbitron',sans-serif;font-size:9px;
  letter-spacing:2px;font-weight:700;cursor:pointer;border:1px solid;transition:all .2s;text-transform:uppercase;}
.btn-blue{background:rgba(0,200,255,0.1);border-color:rgba(0,200,255,0.35);color:var(--blue);}
.btn-blue:hover{background:rgba(0,200,255,0.2);box-shadow:var(--glow-blue);}
.btn-red{background:rgba(255,45,120,0.1);border-color:rgba(255,45,120,0.35);color:var(--rose);}
.btn-red:hover{background:rgba(255,45,120,0.2);box-shadow:var(--glow-pink);}
.btn-purple{background:rgba(176,64,255,0.1);border-color:rgba(176,64,255,0.35);color:var(--lavender);}
.btn-purple:hover{background:rgba(176,64,255,0.2);box-shadow:var(--glow-purple);}
.btn-emerald{background:rgba(0,255,170,0.08);border-color:rgba(0,255,170,0.25);color:var(--emerald);}
.btn-emerald:hover{background:rgba(0,255,170,0.15);box-shadow:var(--glow-emerald);}
/* SCORE ROW */
.score-row{display:flex;gap:10px;margin-bottom:18px;}
.score-badge{flex:1;padding:14px 10px;text-align:center;border-radius:14px;position:relative;overflow:hidden;cursor:pointer;transition:transform .2s;}
.score-badge:hover{transform:translateY(-2px);}
.score-num{font-family:'Orbitron',monospace;font-size:26px;font-weight:900;line-height:1;}
.score-lbl{font-size:8px;color:var(--muted);letter-spacing:2px;margin-top:4px;}
.score-input-overlay{position:absolute;inset:0;display:flex;align-items:center;justify-content:center;
  background:rgba(0,0,0,0.7);border-radius:14px;opacity:0;transition:opacity .2s;pointer-events:none;}
.score-input-overlay input{background:transparent;border:none;border-bottom:1px solid var(--blue);
  color:var(--blue);font-family:'Orbitron',monospace;font-size:22px;font-weight:900;
  width:60px;text-align:center;outline:none;}
.score-badge:hover .score-input-overlay,.score-badge.editing .score-input-overlay{opacity:1;pointer-events:all;}
/* GRID */
.grid-master{display:grid;grid-template-columns:1fr 1fr 1fr;gap:16px;}
/* PANEL */
.panel{background:var(--panel);border:1px solid var(--border);border-radius:18px;padding:20px;
  backdrop-filter:blur(24px);position:relative;overflow:hidden;transition:transform .25s,box-shadow .25s;}
.panel:hover{transform:translateY(-2px);}
.panel::before{content:'';position:absolute;top:0;left:0;right:0;height:1px;
  background:linear-gradient(90deg,transparent,rgba(0,200,255,0.45),transparent);}
.panel-purple{border-color:var(--border2);}
.panel-purple::before{background:linear-gradient(90deg,transparent,rgba(176,64,255,0.45),transparent);}
.panel-purple:hover{box-shadow:var(--glow-purple);}
.panel-pink{border-color:rgba(255,77,166,0.18);}
.panel-pink::before{background:linear-gradient(90deg,transparent,rgba(255,77,166,0.45),transparent);}
.panel-emerald{border-color:rgba(0,255,170,0.13);}
.panel-emerald::before{background:linear-gradient(90deg,transparent,rgba(0,255,170,0.35),transparent);}
.panel-glow-bg{position:absolute;top:-40px;right:-40px;width:160px;height:160px;border-radius:50%;filter:blur(60px);pointer-events:none;opacity:.22;}
.panel-title{font-family:'Orbitron',sans-serif;font-size:9px;letter-spacing:3px;text-transform:uppercase;
  color:var(--muted);margin-bottom:14px;display:flex;align-items:center;gap:8px;}
.panel-title .icon{font-size:13px;}
.ptl{flex:1;height:1px;background:linear-gradient(90deg,var(--border),transparent);}
.col-span-2{grid-column:span 2;}
.col-span-3{grid-column:span 3;}
/* EDITABLE text */
[contenteditable]{outline:none;transition:background .15s,box-shadow .15s;border-radius:4px;min-width:10px;}
[contenteditable]:focus{background:rgba(0,200,255,0.07);box-shadow:0 0 0 1px rgba(0,200,255,0.25);padding:1px 4px;}
[contenteditable]:empty:before{content:attr(data-ph);color:var(--muted);opacity:.5;font-style:italic;}
/* CALENDAR */
.cal-header{display:flex;justify-content:space-between;align-items:center;margin-bottom:14px;}
.cal-month-name{font-family:'Orbitron',sans-serif;font-size:20px;font-weight:700;
  background:linear-gradient(135deg,var(--blue),var(--lavender));-webkit-background-clip:text;-webkit-text-fill-color:transparent;}
.cal-year-num{font-family:'Share Tech Mono',monospace;font-size:12px;color:var(--muted);letter-spacing:2px;}
.cal-nav{display:flex;gap:8px;align-items:center;}
.cal-nav-btn{width:26px;height:26px;border-radius:8px;background:rgba(0,200,255,0.08);
  border:1px solid rgba(0,200,255,0.2);color:var(--blue);cursor:pointer;font-size:13px;
  display:flex;align-items:center;justify-content:center;transition:all .15s;}
.cal-nav-btn:hover{background:rgba(0,200,255,0.18);box-shadow:var(--glow-blue);}
.cal-days-hdr{display:grid;grid-template-columns:repeat(7,1fr);gap:3px;margin-bottom:6px;}
.cdn{text-align:center;font-family:'Share Tech Mono',monospace;font-size:8px;letter-spacing:1px;color:var(--muted);padding:3px 0;}
.cal-grid{display:grid;grid-template-columns:repeat(7,1fr);gap:4px;}
.cal-day{aspect-ratio:1;display:flex;flex-direction:column;align-items:center;justify-content:flex-start;
  padding:4px 3px;background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.04);
  border-radius:9px;cursor:pointer;transition:all .15s;position:relative;overflow:hidden;}
.cal-day:hover{background:rgba(0,200,255,0.06);border-color:rgba(0,200,255,0.18);}
.cal-day.today{background:linear-gradient(135deg,rgba(0,128,255,0.22),rgba(176,64,255,0.16));
  border-color:rgba(0,200,255,0.45);box-shadow:0 0 10px rgba(0,200,255,0.18);}
.cal-day.has-event::after{content:'';position:absolute;bottom:3px;width:4px;height:4px;
  border-radius:50%;background:var(--pink);box-shadow:0 0 5px var(--pink);}
.cal-day.marked{background:rgba(0,255,170,0.05);border-color:rgba(0,255,170,0.18);}
.cal-day.empty{background:transparent;border-color:transparent;pointer-events:none;}
.cal-day-num{font-family:'Orbitron',sans-serif;font-size:10px;font-weight:700;color:var(--silver);line-height:1;}
.cal-day.today .cal-day-num{color:var(--blue);text-shadow:0 0 6px var(--blue);}
.cal-day-note{font-size:7px;color:var(--muted);text-align:center;word-break:break-all;line-height:1.2;margin-top:1px;}
/* EVENT POPUP */
.popup-overlay{position:fixed;inset:0;background:rgba(0,0,0,0.7);z-index:1000;display:none;
  align-items:center;justify-content:center;backdrop-filter:blur(6px);}
.popup-overlay.show{display:flex;}
.popup{background:rgba(8,12,28,0.98);border:1px solid var(--border);border-radius:18px;padding:24px;
  width:320px;box-shadow:var(--glow-blue);}
.popup-title{font-family:'Orbitron',sans-serif;font-size:11px;letter-spacing:3px;color:var(--blue);margin-bottom:16px;}
.popup label{font-size:10px;color:var(--muted);letter-spacing:1px;display:block;margin-bottom:4px;}
.popup input,.popup textarea,.popup select{width:100%;background:rgba(255,255,255,0.04);border:1px solid rgba(0,200,255,0.2);
  border-radius:8px;color:var(--text);font-family:'Rajdhani',sans-serif;font-size:13px;
  padding:8px 12px;outline:none;margin-bottom:12px;transition:border-color .15s;}
.popup input:focus,.popup textarea:focus,.popup select:focus{border-color:var(--blue);}
.popup textarea{resize:vertical;min-height:60px;}
.popup-btns{display:flex;gap:8px;margin-top:4px;}
/* GOALS */
.goal-item{margin-bottom:12px;padding:11px 13px;background:rgba(255,255,255,0.025);border-radius:11px;border:1px solid rgba(255,255,255,0.05);}
.goal-header{display:flex;justify-content:space-between;align-items:center;margin-bottom:6px;}
.goal-name{font-size:12px;font-weight:600;color:var(--text);}
.goal-pct{font-family:'Orbitron',monospace;font-size:11px;color:var(--cyan);}
.goal-rank{font-family:'Share Tech Mono',monospace;font-size:8px;color:var(--muted);letter-spacing:1px;margin-bottom:6px;}
.progress-track{height:5px;background:rgba(255,255,255,0.06);border-radius:99px;overflow:visible;position:relative;cursor:pointer;}
.progress-fill{height:100%;border-radius:99px;position:relative;transition:width .4s;}
.pf-blue{background:linear-gradient(90deg,var(--blue2),var(--cyan));}
.pf-purple{background:linear-gradient(90deg,var(--purple2),var(--lavender));}
.pf-pink{background:linear-gradient(90deg,var(--rose),var(--pink));}
.pf-emerald{background:linear-gradient(90deg,#00cc80,var(--emerald));}
.pf-gold{background:linear-gradient(90deg,#cc8800,var(--gold));}
/* HABIT */
.habit-row{display:flex;align-items:center;gap:8px;margin-bottom:9px;}
.habit-icon{font-size:13px;width:20px;text-align:center;cursor:pointer;}
.habit-label{font-size:11px;font-weight:600;color:var(--silver);width:115px;flex-shrink:0;}
.habit-boxes{display:flex;gap:3px;flex-wrap:wrap;}
.hb{width:15px;height:15px;border-radius:4px;border:1px solid rgba(255,255,255,0.08);
  background:rgba(255,255,255,0.02);cursor:pointer;transition:all .12s;}
.hb:hover{transform:scale(1.2);}
.hb.done{border-color:transparent;}
.hb.done-blue{background:var(--blue);box-shadow:0 0 5px rgba(0,200,255,0.5);}
.hb.done-purple{background:var(--purple);box-shadow:0 0 5px rgba(176,64,255,0.5);}
.hb.done-pink{background:var(--pink);box-shadow:0 0 5px rgba(255,77,166,0.5);}
.hb.done-emerald{background:var(--emerald);box-shadow:0 0 5px rgba(0,255,170,0.5);}
.hb.done-gold{background:var(--gold);box-shadow:0 0 5px rgba(255,208,96,0.5);}
.streak-badge{font-family:'Orbitron',monospace;font-size:8px;font-weight:700;color:var(--gold);
  background:rgba(255,208,96,0.1);border:1px solid rgba(255,208,96,0.2);padding:2px 6px;border-radius:20px;margin-left:auto;letter-spacing:1px;}
.add-habit-row{display:flex;gap:8px;align-items:center;margin-top:8px;}
.add-habit-row input{flex:1;background:rgba(255,255,255,0.04);border:1px solid rgba(0,200,255,0.15);
  border-radius:8px;color:var(--text);font-family:'Rajdhani',sans-serif;font-size:12px;padding:6px 10px;outline:none;}
.add-habit-row input:focus{border-color:var(--blue);}
/* RINGS */
.rings-row{display:flex;justify-content:space-around;align-items:center;}
.ring-wrap{text-align:center;}
.ring-svg{transform:rotate(-90deg);cursor:pointer;}
.ring-bg{fill:none;stroke:rgba(255,255,255,0.06);}
.ring-fill{fill:none;stroke-linecap:round;}
.ring-label{font-family:'Orbitron',monospace;font-size:8px;letter-spacing:1px;color:var(--muted);margin-top:6px;text-transform:uppercase;}
/* STAT CARDS */
.stat-grid{display:grid;grid-template-columns:1fr 1fr;gap:8px;}
.stat-card{padding:11px 13px;background:rgba(255,255,255,0.025);border-radius:11px;border:1px solid rgba(255,255,255,0.05);position:relative;overflow:hidden;}
.stat-card::before{content:'';position:absolute;left:0;top:0;bottom:0;width:3px;border-radius:4px;}
.stat-blue::before{background:var(--blue);box-shadow:0 0 6px var(--blue);}
.stat-purple::before{background:var(--purple);}
.stat-pink::before{background:var(--pink);}
.stat-emerald::before{background:var(--emerald);}
.stat-gold::before{background:var(--gold);}
.stat-num{font-family:'Orbitron',monospace;font-size:18px;font-weight:700;line-height:1;color:var(--text);}
.stat-lbl{font-size:9px;color:var(--muted);letter-spacing:.5px;margin-top:3px;}
.stat-delta{font-family:'Share Tech Mono',monospace;font-size:9px;color:var(--emerald);margin-top:2px;}
/* QUOTE */
.quote-block{border-left:2px solid var(--purple);padding:9px 13px;background:rgba(176,64,255,0.06);
  border-radius:0 9px 9px 0;font-style:italic;font-size:12px;color:var(--lavender);line-height:1.5;margin-bottom:12px;}
.quote-attr{font-family:'Share Tech Mono',monospace;font-size:8px;color:var(--muted);letter-spacing:2px;text-align:right;margin-top:5px;}
/* DETOX */
.detox-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:7px;margin-bottom:12px;}
.detox-item{text-align:center;padding:9px 6px;background:rgba(255,255,255,0.025);border-radius:9px;border:1px solid rgba(255,255,255,0.05);}
.detox-icon{font-size:17px;margin-bottom:3px;}
.detox-val{font-family:'Orbitron',monospace;font-size:12px;font-weight:700;color:var(--text);}
.detox-lbl{font-size:8px;color:var(--muted);}
/* METER */
.meter-row{display:flex;align-items:center;gap:10px;margin-bottom:9px;}
.meter-name{font-size:11px;color:var(--silver);width:85px;flex-shrink:0;}
.meter-bar{flex:1;height:7px;border-radius:99px;background:rgba(255,255,255,0.05);overflow:hidden;cursor:pointer;}
.meter-fill{height:100%;border-radius:99px;}
.meter-val{font-family:'Orbitron',monospace;font-size:10px;color:var(--muted);width:32px;text-align:right;}
/* FINANCE CHART */
.fin-chart{display:flex;align-items:flex-end;gap:5px;height:72px;margin-bottom:12px;}
.fin-col{flex:1;display:flex;flex-direction:column;align-items:stretch;}
.fin-bar{border-radius:5px 5px 0 0;position:relative;cursor:pointer;transition:opacity .2s;}
.fin-bar:hover{opacity:.8;}
.fin-bar-income{background:linear-gradient(180deg,var(--emerald),rgba(0,200,120,0.25));}
.fin-bar-expense{background:linear-gradient(180deg,var(--pink),rgba(255,45,120,0.25));}
.fin-bar-save{background:linear-gradient(180deg,var(--blue),rgba(0,128,255,0.25));}
.fin-month-label{font-family:'Share Tech Mono',monospace;font-size:7px;color:var(--muted);text-align:center;margin-top:3px;}
/* REFLECTION */
.reflect-block{padding:12px;background:rgba(255,255,255,0.02);border-radius:11px;border:1px solid rgba(255,255,255,0.04);margin-bottom:9px;}
.reflect-prompt{font-size:9px;color:var(--muted);letter-spacing:1px;text-transform:uppercase;margin-bottom:6px;font-family:'Share Tech Mono',monospace;}
.reflect-area{width:100%;min-height:48px;background:transparent;border:none;resize:none;
  color:var(--silver);font-family:'Rajdhani',sans-serif;font-size:12px;outline:none;line-height:1.6;}
.reflect-area::placeholder{color:rgba(106,127,168,0.4);}
/* WATER */
.water-grid{display:flex;gap:5px;flex-wrap:wrap;margin-bottom:8px;}
.water-drop{font-size:17px;cursor:pointer;filter:grayscale(.7);transition:filter .15s,transform .15s;}
.water-drop.filled{filter:grayscale(0) drop-shadow(0 0 4px rgba(0,200,255,0.5));transform:scale(1.06);}
/* SLEEP */
.sleep-row{display:flex;gap:4px;align-items:flex-end;height:56px;margin-bottom:6px;}
.sleep-bar-wrap{flex:1;display:flex;flex-direction:column;align-items:center;}
.sleep-bar{width:100%;border-radius:4px 4px 0 0;background:linear-gradient(180deg,var(--purple),rgba(112,32,200,.25));cursor:pointer;transition:height .3s;}
.sleep-day{font-family:'Share Tech Mono',monospace;font-size:7px;color:var(--muted);margin-top:2px;}
/* SUBJECT TAGS */
.subject-tags{display:flex;flex-wrap:wrap;gap:5px;margin-bottom:12px;}
.tag{padding:3px 11px;border-radius:20px;font-size:10px;letter-spacing:.4px;font-weight:600;cursor:pointer;}
.tag-blue{background:rgba(0,200,255,0.1);border:1px solid rgba(0,200,255,0.28);color:var(--blue);}
.tag-purple{background:rgba(176,64,255,0.1);border:1px solid rgba(176,64,255,0.28);color:var(--lavender);}
.tag-pink{background:rgba(255,77,166,0.1);border:1px solid rgba(255,77,166,0.28);color:var(--pink);}
.tag-emerald{background:rgba(0,255,170,0.08);border:1px solid rgba(0,255,170,0.22);color:var(--emerald);}
.tag-gold{background:rgba(255,208,96,0.08);border:1px solid rgba(255,208,96,0.22);color:var(--gold);}
/* FOCUS BLOCKS */
.focus-blocks{display:flex;gap:5px;margin-bottom:9px;}
.focus-block{flex:1;height:34px;border-radius:7px;display:flex;align-items:center;justify-content:center;
  font-family:'Orbitron',monospace;font-size:8px;letter-spacing:1px;color:var(--muted);
  background:rgba(255,255,255,0.025);border:1px solid rgba(255,255,255,0.06);cursor:pointer;transition:all .15s;}
.focus-block.active{background:rgba(0,200,255,0.1);border-color:rgba(0,200,255,0.35);color:var(--blue);box-shadow:0 0 8px rgba(0,200,255,0.12);}
.focus-block.done-f{background:rgba(0,255,170,0.07);border-color:rgba(0,255,170,0.2);color:var(--emerald);}
/* COUNTDOWN */
.countdown-grid{display:grid;grid-template-columns:1fr 1fr;gap:7px;margin-bottom:10px;}
.countdown-item{padding:9px 10px;background:rgba(255,45,120,0.05);border-radius:9px;border:1px solid rgba(255,45,120,0.13);text-align:center;}
.cd-num{font-family:'Orbitron',monospace;font-size:19px;font-weight:900;color:var(--rose);text-shadow:0 0 12px rgba(255,45,120,0.45);}
.cd-lbl{font-size:8px;color:var(--muted);letter-spacing:1px;}
/* CHECKLIST */
.check-item{display:flex;align-items:center;gap:8px;padding:7px 0;border-bottom:1px solid rgba(255,255,255,0.04);font-size:12px;color:var(--silver);cursor:pointer;}
.check-item:last-child{border-bottom:none;}
.check-box{width:13px;height:13px;border-radius:4px;border:1px solid rgba(0,200,255,0.28);flex-shrink:0;display:flex;align-items:center;justify-content:center;transition:all .15s;}
.check-box.checked{background:rgba(0,200,255,0.18);border-color:var(--blue);}
.check-box.checked::after{content:'✓';font-size:8px;color:var(--blue);}
.check-item.done{color:var(--muted);text-decoration:line-through;}
/* CHIPS */
.glow-chip{display:inline-flex;align-items:center;gap:4px;padding:2px 9px;border-radius:20px;font-family:'Share Tech Mono',monospace;font-size:8px;letter-spacing:1px;}
.chip-blue{background:rgba(0,200,255,0.08);border:1px solid rgba(0,200,255,0.22);color:var(--blue);}
.chip-purple{background:rgba(176,64,255,0.08);border:1px solid rgba(176,64,255,0.22);color:var(--lavender);}
.chip-emerald{background:rgba(0,255,170,0.07);border:1px solid rgba(0,255,170,0.18);color:var(--emerald);}
.chip-pink{background:rgba(255,77,166,0.08);border:1px solid rgba(255,77,166,0.22);color:var(--pink);}
.chip-gold{background:rgba(255,208,96,0.07);border:1px solid rgba(255,208,96,0.18);color:var(--gold);}
/* AI BADGE */
.ai-badge{display:inline-flex;align-items:center;gap:5px;background:linear-gradient(90deg,rgba(0,200,255,0.08),rgba(176,64,255,0.08));
  border:1px solid rgba(0,200,255,0.18);padding:3px 11px;border-radius:20px;font-family:'Share Tech Mono',monospace;font-size:8px;color:var(--cyan);letter-spacing:2px;margin-bottom:10px;}
.ai-dot{width:5px;height:5px;border-radius:50%;background:var(--cyan);animation:pulse-dot 1.5s infinite;}
/* DIVIDER */
.divider{height:1px;background:linear-gradient(90deg,transparent,var(--border),transparent);margin:10px 0;}
/* INSIGHT */
.insight-text{font-size:12px;color:var(--silver);line-height:1.6;}
.insight-text em{color:var(--cyan);font-style:normal;}
/* SCORE A */
.score-a{background:linear-gradient(135deg,rgba(0,200,255,0.1),rgba(0,128,255,0.07));border:1px solid rgba(0,200,255,0.22);}
.score-a .score-num{color:var(--blue);text-shadow:0 0 14px rgba(0,200,255,0.45);}
.score-b{background:linear-gradient(135deg,rgba(176,64,255,0.1),rgba(112,32,200,0.07));border:1px solid rgba(176,64,255,0.22);}
.score-b .score-num{color:var(--lavender);text-shadow:0 0 14px rgba(176,64,255,0.45);}
.score-c{background:linear-gradient(135deg,rgba(0,255,170,0.08),rgba(0,200,120,0.05));border:1px solid rgba(0,255,170,0.18);}
.score-c .score-num{color:var(--emerald);text-shadow:0 0 14px rgba(0,255,170,0.35);}
.score-d{background:linear-gradient(135deg,rgba(255,77,166,0.1),rgba(255,45,120,0.07));border:1px solid rgba(255,77,166,0.22);}
.score-d .score-num{color:var(--pink);text-shadow:0 0 14px rgba(255,77,166,0.45);}
.score-e{background:linear-gradient(135deg,rgba(255,208,96,0.08),rgba(200,150,0,0.05));border:1px solid rgba(255,208,96,0.18);}
.score-e .score-num{color:var(--gold);text-shadow:0 0 14px rgba(255,208,96,0.35);}
/* TOAST */
.toast{position:fixed;bottom:30px;left:50%;transform:translateX(-50%) translateY(20px);
  background:rgba(8,12,28,0.95);border:1px solid rgba(0,200,255,0.3);border-radius:12px;
  padding:10px 22px;font-family:'Share Tech Mono',monospace;font-size:11px;color:var(--cyan);
  letter-spacing:2px;z-index:2000;opacity:0;transition:all .3s;pointer-events:none;}
.toast.show{opacity:1;transform:translateX(-50%) translateY(0);}
/* FOOTER */
.footer{margin-top:18px;padding:11px 22px;background:rgba(8,12,28,0.72);border:1px solid var(--border);
  border-radius:14px;backdrop-filter:blur(20px);display:flex;justify-content:space-between;align-items:center;}
.footer-text{font-family:'Share Tech Mono',monospace;font-size:8px;color:var(--muted);letter-spacing:2px;}
/* CONFIRM MODAL */
.confirm-modal{position:fixed;inset:0;background:rgba(0,0,0,0.8);z-index:1500;display:none;
  align-items:center;justify-content:center;backdrop-filter:blur(8px);}
.confirm-modal.show{display:flex;}
.confirm-box{background:rgba(8,12,28,0.98);border:1px solid rgba(255,45,120,0.35);border-radius:18px;
  padding:28px;width:340px;text-align:center;box-shadow:var(--glow-pink);}
.confirm-title{font-family:'Orbitron',sans-serif;font-size:13px;letter-spacing:3px;color:var(--rose);margin-bottom:10px;}
.confirm-text{font-size:13px;color:var(--muted);margin-bottom:20px;line-height:1.6;}
.confirm-btns{display:flex;gap:10px;justify-content:center;}
@media(max-width:1100px){.grid-master{grid-template-columns:1fr 1fr;}.col-span-3{grid-column:span 2;}}
@media(max-width:700px){.grid-master{grid-template-columns:1fr;}.col-span-2,.col-span-3{grid-column:span 1;}.score-row{flex-wrap:wrap;}}
::-webkit-scrollbar{width:5px;}::-webkit-scrollbar-track{background:var(--black);}::-webkit-scrollbar-thumb{background:rgba(0,200,255,0.18);border-radius:3px;}
</style>
</head>
<body>
<div class="bg"><div class="bg-grid"></div><div class="bg-glow bg-glow-1"></div><div class="bg-glow bg-glow-2"></div></div>
<div class="particles" id="particles"></div>

<!-- DAY EVENT POPUP -->
<div class="popup-overlay" id="dayPopup">
  <div class="popup">
    <div class="popup-title" id="popupTitle">DAY · 00</div>
    <label>NOTE / EVENT</label>
    <textarea id="popupNote" placeholder="Add a note or event..."></textarea>
    <label>MARK AS</label>
    <select id="popupMark">
      <option value="">Normal</option>
      <option value="has-event">Has Event 🔴</option>
      <option value="marked">Completed ✅</option>
      <option value="today">Today 💎</option>
    </select>
    <div class="popup-btns">
      <button class="btn btn-blue" onclick="saveDay()">SAVE</button>
      <button class="btn btn-red" onclick="clearDay()">CLEAR</button>
      <button class="btn btn-purple" onclick="closePopup()">CANCEL</button>
    </div>
  </div>
</div>

<!-- CONFIRM MODAL -->
<div class="confirm-modal" id="confirmModal">
  <div class="confirm-box">
    <div class="confirm-title">⚠ RESET NEXUS</div>
    <div class="confirm-text">This will clear <em style="color:var(--rose)">ALL data</em> — habits, goals, reflections, notes, and scores.<br>This cannot be undone.</div>
    <div class="confirm-btns">
      <button class="btn btn-red" onclick="executeReset()">CONFIRM RESET</button>
      <button class="btn btn-purple" onclick="closeConfirm()">CANCEL</button>
    </div>
  </div>
</div>

<!-- TOAST -->
<div class="toast" id="toast"></div>

<div class="page">
  <!-- HEADER -->
  <div class="header">
    <div style="display:flex;align-items:center;gap:14px;">
      <div>
        <div class="logo" contenteditable="true" data-ph="NEXUS">NEXUS</div>
        <div class="logo-sub" contenteditable="true" data-ph="Personal OS · v2.6">Personal OS · v2.6</div>
      </div>
    </div>
    <div class="header-center">
      <div class="header-month" id="headerMonth">✦ JUNE 2026 ✦</div>
      <div class="header-sub">MONTHLY COMMAND DASHBOARD</div>
    </div>
    <div class="header-right">
      <div class="h-stat">FOCUS <span id="focusVal" contenteditable="true">87</span>%</div>
      <div class="h-stat">STREAK <span id="streakVal" contenteditable="true">14</span>d</div>
      <div class="status-dot"></div>
    </div>
  </div>

  <!-- BUTTON ROW -->
  <div class="btn-row">
    <button class="btn btn-blue" onclick="addGoal()">＋ ADD GOAL</button>
    <button class="btn btn-blue" onclick="addHabit()">＋ ADD HABIT</button>
    <button class="btn btn-blue" onclick="addCheckItem()">＋ ADD TASK</button>
    <button class="btn btn-emerald" onclick="saveToStorage()">💾 SAVE</button>
    <button class="btn btn-purple" onclick="exportHTML()">⬇ EXPORT</button>
    <button class="btn btn-red" style="margin-left:auto" onclick="showConfirm()">🗑 CLEAR ALL</button>
  </div>

  <!-- SCORES -->
  <div class="score-row">
    <div class="score-badge score-a" onclick="editScore(this,'score-PRODUCTIVITY')">
      <div class="score-num" id="score-PRODUCTIVITY">87</div><div class="score-lbl">PRODUCTIVITY</div>
      <div class="score-input-overlay"><input type="number" min="0" max="100" onblur="finishScore(this,'score-PRODUCTIVITY')" onkeydown="if(event.key==='Enter')this.blur()"></div>
    </div>
    <div class="score-badge score-b" onclick="editScore(this,'score-DISCIPLINE')">
      <div class="score-num" id="score-DISCIPLINE">92</div><div class="score-lbl">DISCIPLINE</div>
      <div class="score-input-overlay"><input type="number" min="0" max="100" onblur="finishScore(this,'score-DISCIPLINE')" onkeydown="if(event.key==='Enter')this.blur()"></div>
    </div>
    <div class="score-badge score-c" onclick="editScore(this,'score-WELLNESS')">
      <div class="score-num" id="score-WELLNESS">76</div><div class="score-lbl">WELLNESS</div>
      <div class="score-input-overlay"><input type="number" min="0" max="100" onblur="finishScore(this,'score-WELLNESS')" onkeydown="if(event.key==='Enter')this.blur()"></div>
    </div>
    <div class="score-badge score-d" onclick="editScore(this,'score-MINDSET')">
      <div class="score-num" id="score-MINDSET">94</div><div class="score-lbl">MINDSET</div>
      <div class="score-input-overlay"><input type="number" min="0" max="100" onblur="finishScore(this,'score-MINDSET')" onkeydown="if(event.key==='Enter')this.blur()"></div>
    </div>
    <div class="score-badge score-e" onclick="editScore(this,'score-FINANCE')">
      <div class="score-num" id="score-FINANCE">81</div><div class="score-lbl">FINANCE</div>
      <div class="score-input-overlay"><input type="number" min="0" max="100" onblur="finishScore(this,'score-FINANCE')" onkeydown="if(event.key==='Enter')this.blur()"></div>
    </div>
  </div>

  <!-- GRID -->
  <div class="grid-master">

    <!-- CALENDAR -->
    <div class="panel col-span-2">
      <div class="panel-glow-bg" style="background:rgba(0,128,255,.28)"></div>
      <div class="panel-title"><span class="icon">📅</span>Monthly Calendar<div class="ptl"></div><span class="glow-chip chip-blue" id="calChip">JUN 2026</span></div>
      <div class="cal-header">
        <div class="cal-nav">
          <button class="cal-nav-btn" onclick="changeMonth(-1)">‹</button>
          <div>
            <div class="cal-month-name" id="calMonthName">JUNE</div>
            <div class="cal-year-num" id="calYearNum">2026</div>
          </div>
          <button class="cal-nav-btn" onclick="changeMonth(1)">›</button>
        </div>
        <div style="display:flex;gap:6px;align-items:center;">
          <span class="glow-chip chip-pink">● EVENT</span>
          <span class="glow-chip chip-emerald">● DONE</span>
          <span class="glow-chip chip-blue">● TODAY</span>
        </div>
      </div>
      <div class="cal-days-hdr">
        <div class="cdn">SUN</div><div class="cdn">MON</div><div class="cdn">TUE</div>
        <div class="cdn">WED</div><div class="cdn">THU</div><div class="cdn">FRI</div><div class="cdn">SAT</div>
      </div>
      <div class="cal-grid" id="calGrid"></div>
    </div>

    <!-- GOALS -->
    <div class="panel panel-purple">
      <div class="panel-glow-bg" style="background:rgba(176,64,255,.28)"></div>
      <div class="panel-title"><span class="icon">🎯</span>Monthly Goals<div class="ptl"></div><span class="glow-chip chip-purple">TOP 5</span></div>
      <div id="goalsList"></div>
    </div>

    <!-- STUDY -->
    <div class="panel">
      <div class="panel-glow-bg" style="background:rgba(0,200,255,.22)"></div>
      <div class="panel-title"><span class="icon">📚</span>Study Command<div class="ptl"></div></div>
      <div class="ai-badge"><div class="ai-dot"></div>AI ANALYTICS ACTIVE</div>
      <div class="subject-tags" id="subjectTags">
        <span class="tag tag-blue" contenteditable="true">Mathematics</span>
        <span class="tag tag-purple" contenteditable="true">Physics</span>
        <span class="tag tag-emerald" contenteditable="true">Code</span>
        <span class="tag tag-pink" contenteditable="true">Design</span>
        <span class="tag tag-gold" contenteditable="true">Finance</span>
        <span class="tag tag-blue" style="cursor:pointer;opacity:.6" onclick="addSubject()">＋</span>
      </div>
      <div class="countdown-grid">
        <div class="countdown-item"><div class="cd-num" contenteditable="true">12</div><div class="cd-lbl" contenteditable="true">DAYS · EXAM 1</div></div>
        <div class="countdown-item"><div class="cd-num" contenteditable="true">28</div><div class="cd-lbl" contenteditable="true">DAYS · EXAM 2</div></div>
      </div>
      <div class="panel-title" style="margin-bottom:7px">Focus Sessions</div>
      <div class="focus-blocks" id="focusBlocks">
        <div class="focus-block done-f" onclick="toggleFocus(this)">✓ 9AM</div>
        <div class="focus-block done-f" onclick="toggleFocus(this)">✓ 11AM</div>
        <div class="focus-block active" onclick="toggleFocus(this)">2PM</div>
        <div class="focus-block" onclick="toggleFocus(this)">4PM</div>
        <div class="focus-block" onclick="toggleFocus(this)">7PM</div>
      </div>
      <div class="divider"></div>
      <div class="meter-row"><div class="meter-name">Deep Work</div><div class="meter-bar" onclick="editMeter(this)"><div class="meter-fill" style="width:72%;background:linear-gradient(90deg,var(--blue2),var(--cyan))"></div></div><div class="meter-val" style="color:var(--cyan)" contenteditable="true">4.3h</div></div>
      <div class="meter-row"><div class="meter-name">Productivity</div><div class="meter-bar" onclick="editMeter(this)"><div class="meter-fill" style="width:87%;background:linear-gradient(90deg,var(--purple2),var(--lavender))"></div></div><div class="meter-val" style="color:var(--lavender)" contenteditable="true">87%</div></div>
      <div class="meter-row"><div class="meter-name">Review Queue</div><div class="meter-bar" onclick="editMeter(this)"><div class="meter-fill" style="width:45%;background:linear-gradient(90deg,#cc8800,var(--gold))"></div></div><div class="meter-val" style="color:var(--gold)" contenteditable="true">18</div></div>
    </div>

    <!-- FITNESS -->
    <div class="panel panel-emerald">
      <div class="panel-glow-bg" style="background:rgba(0,255,170,.18)"></div>
      <div class="panel-title"><span class="icon">🏋️</span>Fitness & Health<div class="ptl"></div></div>
      <div class="rings-row" style="margin-bottom:14px">
        <div class="ring-wrap">
          <svg width="66" height="66" class="ring-svg" onclick="editRing(this,0)">
            <circle class="ring-bg" cx="33" cy="33" r="26" stroke-width="5"/>
            <circle class="ring-fill" cx="33" cy="33" r="26" stroke-width="5" stroke="url(#rg1)" stroke-dasharray="163.4" id="ring0" stroke-dashoffset="41"/>
            <defs><linearGradient id="rg1" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#00cc80"/><stop offset="100%" stop-color="#00ffaa"/></linearGradient></defs>
          </svg>
          <div class="ring-label">MOVE</div>
        </div>
        <div class="ring-wrap">
          <svg width="66" height="66" class="ring-svg" onclick="editRing(this,1)">
            <circle class="ring-bg" cx="33" cy="33" r="26" stroke-width="5"/>
            <circle class="ring-fill" cx="33" cy="33" r="26" stroke-width="5" stroke="url(#rg2)" stroke-dasharray="163.4" id="ring1" stroke-dashoffset="82"/>
            <defs><linearGradient id="rg2" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#0060cc"/><stop offset="100%" stop-color="#00c8ff"/></linearGradient></defs>
          </svg>
          <div class="ring-label">ACTIVE</div>
        </div>
        <div class="ring-wrap">
          <svg width="66" height="66" class="ring-svg" onclick="editRing(this,2)">
            <circle class="ring-bg" cx="33" cy="33" r="26" stroke-width="5"/>
            <circle class="ring-fill" cx="33" cy="33" r="26" stroke-width="5" stroke="url(#rg3)" stroke-dasharray="163.4" id="ring2" stroke-dashoffset="24"/>
            <defs><linearGradient id="rg3" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#cc0060"/><stop offset="100%" stop-color="#ff4da6"/></linearGradient></defs>
          </svg>
          <div class="ring-label">STAND</div>
        </div>
      </div>
      <div class="divider"></div>
      <div class="panel-title" style="margin-bottom:6px">💧 Water Intake</div>
      <div class="water-grid" id="waterDrops"></div>
      <div class="divider"></div>
      <div class="panel-title" style="margin-bottom:6px">🌙 Sleep (hrs)</div>
      <div class="sleep-row" id="sleepBars"></div>
      <div class="stat-grid" style="margin-top:9px">
        <div class="stat-card stat-emerald"><div class="stat-num" contenteditable="true">2,847</div><div class="stat-lbl">Calories</div><div class="stat-delta" contenteditable="true">↑ +3% goal</div></div>
        <div class="stat-card stat-blue"><div class="stat-num" contenteditable="true">168g</div><div class="stat-lbl">Protein</div><div class="stat-delta" contenteditable="true">✓ On track</div></div>
      </div>
    </div>

    <!-- HABITS -->
    <div class="panel col-span-2">
      <div class="panel-glow-bg" style="background:rgba(0,200,255,.13)"></div>
      <div class="panel-title"><span class="icon">🔥</span>Habit Tracker<div class="ptl"></div><span class="glow-chip chip-gold" id="globalStreakBadge">🔥 STREAK</span></div>
      <div id="habitRows"></div>
    </div>

    <!-- FINANCE -->
    <div class="panel panel-emerald">
      <div class="panel-glow-bg" style="background:rgba(0,255,170,.18)"></div>
      <div class="panel-title"><span class="icon">💰</span>Money & Business<div class="ptl"></div></div>
      <div class="stat-grid" style="margin-bottom:12px">
        <div class="stat-card stat-emerald"><div class="stat-num" contenteditable="true">$8.4k</div><div class="stat-lbl">Income</div><div class="stat-delta" contenteditable="true">↑ +12%</div></div>
        <div class="stat-card stat-pink"><div class="stat-num" contenteditable="true">$3.1k</div><div class="stat-lbl">Expenses</div><div class="stat-delta" contenteditable="true">↓ -8%</div></div>
        <div class="stat-card stat-blue"><div class="stat-num" contenteditable="true">$3.1k</div><div class="stat-lbl">Saved</div><div class="stat-delta" contenteditable="true">62% goal</div></div>
        <div class="stat-card stat-gold"><div class="stat-num" contenteditable="true">$2.2k</div><div class="stat-lbl">Invested</div><div class="stat-delta" contenteditable="true">↑ +5.4%</div></div>
      </div>
      <div class="panel-title" style="margin-bottom:7px">📈 Monthly Overview</div>
      <div class="fin-chart" id="finChart"></div>
      <div style="display:flex;gap:6px;margin-top:3px">
        <span class="glow-chip chip-emerald">● INCOME</span>
        <span class="glow-chip chip-pink">● EXPENSE</span>
        <span class="glow-chip chip-blue">● SAVINGS</span>
      </div>
    </div>

    <!-- MINDSET -->
    <div class="panel panel-purple">
      <div class="panel-glow-bg" style="background:rgba(176,64,255,.28)"></div>
      <div class="panel-title"><span class="icon">🧠</span>Mindset & Focus<div class="ptl"></div></div>
      <div class="quote-block">
        <span contenteditable="true" id="quoteText">"The man who moves a mountain begins by carrying away small stones."</span>
        <div class="quote-attr" contenteditable="true" id="quoteAttr">— CONFUCIUS</div>
      </div>
      <div class="detox-grid">
        <div class="detox-item"><div class="detox-icon">📵</div><div class="detox-val" contenteditable="true">14</div><div class="detox-lbl">No Scroll</div></div>
        <div class="detox-item"><div class="detox-icon">📱</div><div class="detox-val" contenteditable="true">1.2h</div><div class="detox-lbl">Screen</div></div>
        <div class="detox-item"><div class="detox-icon">🧘</div><div class="detox-val" contenteditable="true">21</div><div class="detox-lbl">Med. Days</div></div>
        <div class="detox-item"><div class="detox-icon">⚡</div><div class="detox-val" contenteditable="true">94</div><div class="detox-lbl">Clarity</div></div>
      </div>
      <div class="meter-row"><div class="meter-name">Focus</div><div class="meter-bar" onclick="editMeter(this)"><div class="meter-fill" style="width:87%;background:linear-gradient(90deg,var(--purple2),var(--lavender))"></div></div><div class="meter-val" style="color:var(--lavender)" contenteditable="true">87</div></div>
      <div class="meter-row"><div class="meter-name">Mental Energy</div><div class="meter-bar" onclick="editMeter(this)"><div class="meter-fill" style="width:74%;background:linear-gradient(90deg,#0060cc,var(--cyan))"></div></div><div class="meter-val" style="color:var(--cyan)" contenteditable="true">74</div></div>
      <div class="meter-row"><div class="meter-name">Discipline</div><div class="meter-bar" onclick="editMeter(this)"><div class="meter-fill" style="width:92%;background:linear-gradient(90deg,#cc0060,var(--pink))"></div></div><div class="meter-val" style="color:var(--pink)" contenteditable="true">92</div></div>
      <div class="divider"></div>
      <div class="ai-badge"><div class="ai-dot" style="background:var(--purple)"></div>AI INSIGHT</div>
      <div class="insight-text" contenteditable="true">Your focus is <em>18% higher</em> than last month. Peak performance: <em>9–11 AM</em>. Schedule deep work then. ✨</div>
    </div>

    <!-- REFLECTION -->
    <div class="panel col-span-2" style="background:rgba(5,6,16,.88);border-color:rgba(176,64,255,.13)">
      <div class="panel-glow-bg" style="background:rgba(112,32,200,.18)"></div>
      <div class="panel-title"><span class="icon">🌙</span>Night Reflection<div class="ptl"></div><span class="glow-chip chip-purple">MONTHLY RESET</span></div>
      <div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:10px">
        <div class="reflect-block"><div class="reflect-prompt">✨ Wins This Month</div><textarea class="reflect-area" placeholder="Write your wins..."></textarea></div>
        <div class="reflect-block"><div class="reflect-prompt">💎 Lessons Learned</div><textarea class="reflect-area" placeholder="What did you learn..."></textarea></div>
        <div class="reflect-block"><div class="reflect-prompt">🙏 Gratitude</div><textarea class="reflect-area" placeholder="I am grateful for..."></textarea></div>
        <div class="reflect-block"><div class="reflect-prompt">🚀 Next Month Focus</div><textarea class="reflect-area" placeholder="My focus next month..."></textarea></div>
        <div class="reflect-block"><div class="reflect-prompt">🔥 Do Different</div><textarea class="reflect-area" placeholder="I would change..."></textarea></div>
        <div class="reflect-block" style="display:flex;flex-direction:column;align-items:center;justify-content:center;">
          <div class="reflect-prompt">⚡ Self-Rating /10</div>
          <div style="font-family:'Orbitron',monospace;font-size:40px;font-weight:900;color:var(--purple);text-shadow:0 0 20px rgba(176,64,255,.5);cursor:pointer;" contenteditable="true">8.4</div>
          <div style="font-size:8px;color:var(--muted);letter-spacing:2px;margin-top:4px">OVERALL SCORE</div>
        </div>
      </div>
    </div>

    <!-- CHECKLIST -->
    <div class="panel">
      <div class="panel-glow-bg" style="background:rgba(0,200,255,.18)"></div>
      <div class="panel-title"><span class="icon">📝</span>Task Checklist<div class="ptl"></div></div>
      <div class="checklist" id="checklist"></div>
    </div>

  </div>

  <div class="footer">
    <div class="footer-text" contenteditable="true">NEXUS PERSONAL OS · JUNE 2026 · CONFIDENTIAL</div>
    <div style="display:flex;gap:8px;">
      <span class="glow-chip chip-blue">📅 PLANNER</span>
      <span class="glow-chip chip-purple">🧠 AI POWERED</span>
      <span class="glow-chip chip-emerald">⚡ ACTIVE</span>
    </div>
  </div>
</div>

<script>
// ── STATE ──────────────────────────────────────────────
let state = {
  calYear: 2026, calMonth: 5, // 0-indexed month
  calDayData: {}, // key: "YYYY-M-D" => {note, mark}
  goals: [
    {name:'🚀 Launch SaaS MVP', pct:78, priority:'P1', color:'pf-blue'},
    {name:'📚 Complete ML Course', pct:55, priority:'P2', color:'pf-purple'},
    {name:'💪 5kg Lean Mass', pct:40, priority:'P2', color:'pf-emerald'},
    {name:'💰 Save $5,000', pct:62, priority:'P3', color:'pf-gold'},
    {name:'🧘 30-Day No Scroll', pct:90, priority:'P1', color:'pf-pink'},
  ],
  habits: [
    {icon:'🌅', name:'Morning Routine', color:'done-gold', days:new Array(31).fill(0)},
    {icon:'📖', name:'Read 30 min', color:'done-blue', days:new Array(31).fill(0)},
    {icon:'🏋️', name:'Workout', color:'done-emerald', days:new Array(31).fill(0)},
    {icon:'🧘', name:'Meditate', color:'done-purple', days:new Array(31).fill(0)},
    {icon:'📵', name:'No Social Media', color:'done-pink', days:new Array(31).fill(0)},
    {icon:'💧', name:'Hydrate 2L', color:'done-blue', days:new Array(31).fill(0)},
  ],
  checklist: [
    {text:'Review Chapter 12 — Calculus', done:true},
    {text:'Complete 3 past papers', done:true},
    {text:'Revise Quantum Physics notes', done:false},
    {text:'Mock test — Data Structures', done:false},
    {text:'Summarize ML models ch.4-6', done:false},
    {text:'Finance reading: DCF models', done:true},
    {text:'Update Anki flashcard deck', done:false},
  ],
  water: 6,
  sleep: [42,56,38,50,60,44,52], // px heights
  rings: [41, 82, 24], // stroke-dashoffset values
  finData: [62,70,55,80,75,95], // % heights income
  scores: {PRODUCTIVITY:87,DISCIPLINE:92,WELLNESS:76,MINDSET:94,FINANCE:81},
};

const MONTH_NAMES = ['JANUARY','FEBRUARY','MARCH','APRIL','MAY','JUNE','JULY','AUGUST','SEPTEMBER','OCTOBER','NOVEMBER','DECEMBER'];
const MONTH_SHORT = ['JAN','FEB','MAR','APR','MAY','JUN','JUL','AUG','SEP','OCT','NOV','DEC'];

// ── PARTICLES ──────────────────────────────────────────
(function(){
  const c=document.getElementById('particles');
  const cols=['#00c8ff','#b040ff','#00ffe0','#ff4da6','#c9a0ff'];
  for(let i=0;i<35;i++){
    const p=document.createElement('div');p.className='particle';
    p.style.cssText=`left:${Math.random()*100}%;width:${Math.random()*2+1}px;height:${Math.random()*2+1}px;background:${cols[Math.floor(Math.random()*cols.length)]};animation-duration:${Math.random()*12+8}s;animation-delay:${Math.random()*10}s;`;
    c.appendChild(p);
  }
})();

// ── TOAST ──────────────────────────────────────────────
function toast(msg){
  const t=document.getElementById('toast');
  t.textContent=msg;t.classList.add('show');
  setTimeout(()=>t.classList.remove('show'),2200);
}

// ── CALENDAR ──────────────────────────────────────────
let activeDay=null;

function buildCalendar(){
  const {calYear,calMonth}=state;
  document.getElementById('calMonthName').textContent=MONTH_NAMES[calMonth];
  document.getElementById('calYearNum').textContent=calYear;
  document.getElementById('calChip').textContent=MONTH_SHORT[calMonth]+' '+calYear;
  document.getElementById('headerMonth').textContent='✦ '+MONTH_NAMES[calMonth]+' '+calYear+' ✦';
  document.querySelector('.footer-text').textContent='NEXUS PERSONAL OS · '+MONTH_SHORT[calMonth]+' '+calYear+' · CONFIDENTIAL';

  const grid=document.getElementById('calGrid');
  grid.innerHTML='';
  const firstDay=new Date(calYear,calMonth,1).getDay();
  const total=new Date(calYear,calMonth+1,0).getDate();
  const todayReal=new Date();
  const isCurrentMonth=(calYear===todayReal.getFullYear()&&calMonth===todayReal.getMonth());

  for(let i=0;i<firstDay;i++){const e=document.createElement('div');e.className='cal-day empty';grid.appendChild(e);}
  for(let d=1;d<=total;d++){
    const key=calYear+'-'+calMonth+'-'+d;
    const data=state.calDayData[key]||{};
    const cell=document.createElement('div');
    let cls='cal-day';
    if(data.mark) cls+=' '+data.mark;
    else if(isCurrentMonth&&d===todayReal.getDate()) cls+=' today';
    cell.className=cls;
    cell.innerHTML=`<div class="cal-day-num">${d}</div>${data.note?'<div class="cal-day-note">'+data.note.substring(0,12)+'</div>':''}`;
    cell.onclick=()=>openDayPopup(d,key,data);
    grid.appendChild(cell);
  }
  buildHabitRows(); // Rebuild so day count matches
}

function changeMonth(dir){
  state.calMonth+=dir;
  if(state.calMonth>11){state.calMonth=0;state.calYear++;}
  if(state.calMonth<0){state.calMonth=11;state.calYear--;}
  buildCalendar();
}

function openDayPopup(d,key,data){
  activeDay=key;
  document.getElementById('popupTitle').textContent='DAY · '+String(d).padStart(2,'0');
  document.getElementById('popupNote').value=data.note||'';
  document.getElementById('popupMark').value=data.mark||'';
  document.getElementById('dayPopup').classList.add('show');
}

function saveDay(){
  if(!activeDay)return;
  state.calDayData[activeDay]={
    note:document.getElementById('popupNote').value,
    mark:document.getElementById('popupMark').value
  };
  closePopup();buildCalendar();toast('DAY SAVED ✓');
}
function clearDay(){if(activeDay)delete state.calDayData[activeDay];closePopup();buildCalendar();toast('DAY CLEARED');}
function closePopup(){document.getElementById('dayPopup').classList.remove('show');activeDay=null;}
document.getElementById('dayPopup').addEventListener('click',function(e){if(e.target===this)closePopup();});

// ── GOALS ──────────────────────────────────────────────
function buildGoals(){
  const container=document.getElementById('goalsList');
  container.innerHTML='';
  state.goals.forEach((g,i)=>{
    const div=document.createElement('div');
    div.className='goal-item';
    div.innerHTML=`
      <div class="goal-header">
        <span class="goal-name" contenteditable="true" onblur="state.goals[${i}].name=this.textContent">${g.name}</span>
        <span class="goal-pct" contenteditable="true" onblur="updateGoalPct(${i},this.textContent)">${g.pct}%</span>
      </div>
      <div class="goal-rank" contenteditable="true" onblur="state.goals[${i}].priority=this.textContent">PRIORITY · ${g.priority}</div>
      <div class="progress-track" onclick="clickGoalBar(event,${i})">
        <div class="progress-fill ${g.color}" style="width:${g.pct}%" id="gbar${i}"></div>
      </div>
      <button onclick="removeGoal(${i})" style="background:none;border:none;color:var(--muted);font-size:10px;cursor:pointer;margin-top:5px;letter-spacing:1px;font-family:'Share Tech Mono',monospace;">✕ REMOVE</button>
    `;
    container.appendChild(div);
  });
}

function clickGoalBar(e,i){
  const rect=e.currentTarget.getBoundingClientRect();
  const pct=Math.round(((e.clientX-rect.left)/rect.width)*100);
  state.goals[i].pct=Math.min(100,Math.max(0,pct));
  document.getElementById('gbar'+i).style.width=state.goals[i].pct+'%';
  e.currentTarget.previousElementSibling.querySelector('.goal-pct').textContent=state.goals[i].pct+'%';
}

function updateGoalPct(i,val){const n=parseInt(val);if(!isNaN(n)){state.goals[i].pct=Math.min(100,Math.max(0,n));document.getElementById('gbar'+i).style.width=state.goals[i].pct+'%';}}

function addGoal(){
  const colors=['pf-blue','pf-purple','pf-emerald','pf-gold','pf-pink'];
  state.goals.push({name:'🎯 New Goal',pct:0,priority:'P3',color:colors[state.goals.length%colors.length]});
  buildGoals();toast('GOAL ADDED ✓');
}

function removeGoal(i){state.goals.splice(i,1);buildGoals();toast('GOAL REMOVED');}

// ── HABITS ──────────────────────────────────────────────
function getDaysInMonth(){return new Date(state.calYear,state.calMonth+1,0).getDate();}

function buildHabitRows(){
  const container=document.getElementById('habitRows');
  container.innerHTML='';
  const days=getDaysInMonth();
  state.habits.forEach((h,hi)=>{
    if(h.days.length<days) h.days=[...h.days,...new Array(days-h.days.length).fill(0)];
    const streak=h.days.filter(Boolean).length;
    const row=document.createElement('div');row.className='habit-row';
    const boxesHTML=h.days.slice(0,days).map((d,di)=>
      `<div class="hb ${d?'done '+h.color:''}" onclick="toggleHabit(${hi},${di})"></div>`
    ).join('');
    row.innerHTML=`
      <div class="habit-icon" title="Click to change" onclick="changeHabitIcon(${hi})">${h.icon}</div>
      <div class="habit-label" contenteditable="true" onblur="state.habits[${hi}].name=this.textContent">${h.name}</div>
      <div class="habit-boxes">${boxesHTML}</div>
      <div class="streak-badge">🔥 ${streak}</div>
      <button onclick="removeHabit(${hi})" style="background:none;border:none;color:var(--muted);font-size:11px;cursor:pointer;margin-left:4px;">✕</button>
    `;
    container.appendChild(row);
  });
  // Add habit button row
  const addRow=document.createElement('div');
  addRow.className='add-habit-row';
  addRow.innerHTML=`<input id="newHabitInput" placeholder="New habit name..." /><button class="btn btn-blue" style="padding:6px 14px;font-size:8px" onclick="confirmAddHabit()">＋ ADD</button>`;
  container.appendChild(addRow);
}

function toggleHabit(hi,di){
  state.habits[hi].days[di]=state.habits[hi].days[di]?0:1;
  buildHabitRows();
}

function addHabit(){
  const colors=['done-blue','done-purple','done-emerald','done-pink','done-gold'];
  const icons=['⭐','🎵','📐','🌿','🏃','💡','🎯','🔑'];
  state.habits.push({icon:icons[Math.floor(Math.random()*icons.length)],name:'New Habit',color:colors[state.habits.length%colors.length],days:new Array(31).fill(0)});
  buildHabitRows();toast('HABIT ADDED ✓');
}

function confirmAddHabit(){
  const inp=document.getElementById('newHabitInput');
  const name=inp.value.trim();
  if(!name)return;
  const colors=['done-blue','done-purple','done-emerald','done-pink','done-gold'];
  state.habits.push({icon:'⭐',name,color:colors[state.habits.length%colors.length],days:new Array(31).fill(0)});
  buildHabitRows();toast('HABIT ADDED ✓');
}

function removeHabit(i){state.habits.splice(i,1);buildHabitRows();toast('HABIT REMOVED');}

function changeHabitIcon(i){
  const icons=['🌅','📖','🏋️','🧘','📵','💧','⭐','🎵','🏃','💡','🎯','🔑','🍎','🛏️','💊','📝'];
  const cur=icons.indexOf(state.habits[i].icon);
  state.habits[i].icon=icons[(cur+1)%icons.length];
  buildHabitRows();
}

// ── CHECKLIST ──────────────────────────────────────────
function buildChecklist(){
  const container=document.getElementById('checklist');
  container.innerHTML='';
  state.checklist.forEach((item,i)=>{
    const div=document.createElement('div');
    div.className='check-item'+(item.done?' done':'');
    div.innerHTML=`
      <div class="check-box ${item.done?'checked':''}" onclick="toggleCheck(${i})"></div>
      <span contenteditable="true" onblur="state.checklist[${i}].text=this.textContent">${item.text}</span>
      <button onclick="removeCheck(${i})" style="background:none;border:none;color:var(--muted);font-size:11px;cursor:pointer;margin-left:auto;">✕</button>
    `;
    container.appendChild(div);
  });
}

function toggleCheck(i){state.checklist[i].done=!state.checklist[i].done;buildChecklist();}
function removeCheck(i){state.checklist.splice(i,1);buildChecklist();}
function addCheckItem(){
  state.checklist.push({text:'New Task',done:false});
  buildChecklist();
  const items=document.querySelectorAll('.check-item');
  const last=items[items.length-1];
  if(last){const span=last.querySelector('span');if(span){span.focus();const r=document.createRange();r.selectNodeContents(span);const s=window.getSelection();s.removeAllRanges();s.addRange(r);}}
  toast('TASK ADDED ✓');
}

// ── WATER ──────────────────────────────────────────────
function buildWater(){
  const c=document.getElementById('waterDrops');c.innerHTML='';
  for(let i=0;i<8;i++){
    const d=document.createElement('span');
    d.className='water-drop'+(i<state.water?' filled':'');
    d.textContent='💧';
    d.onclick=()=>{state.water=(i<state.water?i:i+1);buildWater();};
    c.appendChild(d);
  }
  const lbl=document.createElement('div');
  lbl.style.cssText='width:100%;font-family:"Share Tech Mono",monospace;font-size:8px;color:var(--muted);letter-spacing:1px;margin-top:3px';
  lbl.textContent=state.water+'/8 GLASSES · '+(state.water*250)+'ml';
  c.appendChild(lbl);
}

// ── SLEEP ──────────────────────────────────────────────
const DAYS=['M','T','W','T','F','S','S'];
function buildSleep(){
  const c=document.getElementById('sleepBars');c.innerHTML='';
  state.sleep.forEach((h,i)=>{
    const w=document.createElement('div');w.className='sleep-bar-wrap';
    const b=document.createElement('div');b.className='sleep-bar';b.style.height=h+'px';
    b.title='Click to edit';
    b.onclick=()=>{const v=prompt('Sleep hours (0-12):',Math.round(h/6));if(v!==null&&!isNaN(v)){state.sleep[i]=Math.min(72,Math.max(0,parseFloat(v)*6));buildSleep();}};
    const l=document.createElement('div');l.className='sleep-day';l.textContent=DAYS[i];
    w.appendChild(b);w.appendChild(l);c.appendChild(w);
  });
}

// ── RINGS ──────────────────────────────────────────────
function editRing(svg,i){
  const circ=163.4;
  const pct=Math.round((1-(state.rings[i]/circ))*100);
  const v=prompt('Ring value (0-100%):',pct);
  if(v!==null&&!isNaN(v)){
    const np=Math.min(100,Math.max(0,parseInt(v)));
    state.rings[i]=circ*(1-np/100);
    document.getElementById('ring'+i).setAttribute('stroke-dashoffset',state.rings[i]);
  }
}

// ── METERS ──────────────────────────────────────────────
function editMeter(bar){
  const fill=bar.querySelector('.meter-fill');
  const cur=parseInt(fill.style.width);
  const v=prompt('Set value (0-100):',cur);
  if(v!==null&&!isNaN(v)){fill.style.width=Math.min(100,Math.max(0,parseInt(v)))+'%';}
}

// ── SCORES ──────────────────────────────────────────────
function editScore(badge,id){
  badge.classList.add('editing');
  const inp=badge.querySelector('input');
  inp.value=document.getElementById(id).textContent;
  inp.focus();inp.select();
}
function finishScore(inp,id){
  const badge=inp.closest('.score-badge');
  badge.classList.remove('editing');
  const v=parseInt(inp.value);
  if(!isNaN(v)){document.getElementById(id).textContent=Math.min(100,Math.max(0,v));}
}

// ── FOCUS BLOCKS ──────────────────────────────────────
function toggleFocus(el){
  if(el.classList.contains('done-f')){el.classList.remove('done-f');el.textContent=el.textContent.replace('✓ ','');}
  else if(el.classList.contains('active')){el.classList.remove('active');el.classList.add('done-f');el.textContent='✓ '+el.textContent;}
  else{el.classList.add('active');}
}

// ── FINANCE CHART ──────────────────────────────────────
function buildFinChart(){
  const c=document.getElementById('finChart');c.innerHTML='';
  state.finData.forEach((v,i)=>{
    const col=document.createElement('div');col.className='fin-col';
    const bar=document.createElement('div');bar.className='fin-bar fin-bar-income';
    bar.style.height=v+'%';
    if(i===state.finData.length-1) bar.style.boxShadow='0 0 10px rgba(0,255,170,.3)';
    bar.onclick=()=>{const nv=prompt('Bar height % (0-100):',v);if(nv!==null&&!isNaN(nv)){state.finData[i]=Math.min(100,Math.max(0,parseInt(nv)));buildFinChart();}};
    const lbl=document.createElement('div');lbl.className='fin-month-label';
    const months=['JAN','FEB','MAR','APR','MAY','JUN','JUL','AUG','SEP','OCT','NOV','DEC'];
    lbl.textContent=months[(state.calMonth-5+i+12)%12]||months[i];
    if(i===state.finData.length-1)lbl.style.color='var(--emerald)';
    col.appendChild(bar);col.appendChild(lbl);c.appendChild(col);
  });
}

// ── SUBJECTS ──────────────────────────────────────────
function addSubject(){
  const colors=['tag-blue','tag-purple','tag-emerald','tag-pink','tag-gold'];
  const tags=document.getElementById('subjectTags');
  const addBtn=tags.lastElementChild;
  const span=document.createElement('span');
  const c=colors[tags.children.length%colors.length];
  span.className='tag '+c;span.contenteditable='true';span.textContent='Subject';
  tags.insertBefore(span,addBtn);
  span.focus();const r=document.createRange();r.selectNodeContents(span);const s=window.getSelection();s.removeAllRanges();s.addRange(r);
}

// ── SAVE / LOAD / EXPORT ──────────────────────────────
function saveToStorage(){
  try{localStorage.setItem('nexus_state',JSON.stringify(state));toast('SAVED TO BROWSER ✓');}
  catch(e){toast('SAVE FAILED');}
}

function loadFromStorage(){
  try{
    const raw=localStorage.getItem('nexus_state');
    if(raw){state=JSON.parse(raw);toast('DATA LOADED ✓');}
  }catch(e){}
}

function exportHTML(){
  const blob=new Blob([document.documentElement.outerHTML],{type:'text/html'});
  const a=document.createElement('a');a.href=URL.createObjectURL(blob);
  a.download='nexus-planner-'+MONTH_SHORT[state.calMonth]+state.calYear+'.html';
  a.click();toast('EXPORTED ✓');
}

// ── RESET ──────────────────────────────────────────────
function showConfirm(){document.getElementById('confirmModal').classList.add('show');}
function closeConfirm(){document.getElementById('confirmModal').classList.remove('show');}

function executeReset(){
  // Clear habits
  state.habits.forEach(h=>{h.days=new Array(31).fill(0);});
  // Clear goals pct
  state.goals.forEach(g=>{g.pct=0;});
  // Clear checklist done
  state.checklist.forEach(c=>{c.done=false;});
  // Clear cal data
  state.calDayData={};
  // Reset water
  state.water=0;
  // Reset sleep
  state.sleep=[0,0,0,0,0,0,0];
  // Reset scores
  Object.keys(state.scores).forEach(k=>state.scores[k]=0);
  // Clear reflections
  document.querySelectorAll('.reflect-area').forEach(a=>{a.value='';});
  // Clear localStorage
  try{localStorage.removeItem('nexus_state');}catch(e){}
  closeConfirm();
  // Rebuild all
  buildAll();
  // Reset score displays
  ['PRODUCTIVITY','DISCIPLINE','WELLNESS','MINDSET','FINANCE'].forEach(k=>{
    const el=document.getElementById('score-'+k);if(el)el.textContent='0';
  });
  toast('🔄 ALL DATA CLEARED');
}

// ── BUILD ALL ──────────────────────────────────────────
function buildAll(){
  buildCalendar();
  buildGoals();
  buildHabitRows();
  buildChecklist();
  buildWater();
  buildSleep();
  buildFinChart();
}

// ── INIT ──────────────────────────────────────────────
loadFromStorage();
buildAll();
</script>
</body>
</html>
HTMLEOF
echo "Done"