<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>DEXTER MORGAN — Guess The Text</title>
  <style>
    :root{
      --bg:#0c0f19;--fg:#eef2ff;--muted:#b6c2ff;--hot:#ff5ea1;--lime:#7af0b0;--amber:#ffd166;--card:#12172a;--accent:#7868e6;
    }
    @keyframes floaty{0%{transform:translateY(0)}50%{transform:translateY(-8px)}100%{transform:translateY(0)}}
    @keyframes glowPulse{0%{box-shadow:0 0 0 0 rgba(255,94,161,.7)}70%{box-shadow:0 0 25px 8px rgba(255,94,161,.2)}100%{box-shadow:0 0 0 0 rgba(255,94,161,0)}}
    @keyframes type{from{width:0}to{width:100%}}
    @keyframes slideUp{from{transform:translateY(30px);opacity:0}to{transform:translateY(0);opacity:1}}
    @keyframes badgePop{0%{transform:scale(.6);opacity:0}60%{transform:scale(1.08);opacity:1}100%{transform:scale(1)}}
    @keyframes heartBeat{0%{transform:scale(1)}25%{transform:scale(1.12)}40%{transform:scale(1)}60%{transform:scale(1.18)}100%{transform:scale(1)}}
    @keyframes walkOut{0%{transform:translateX(-20vw)}100%{transform:translateX(120vw)}}
    *{box-sizing:border-box}
    body{margin:0;font-family:ui-sans-serif,system-ui,Segoe UI,Roboto,Helvetica,Arial; background:radial-gradient(1200px 800px at 10% 10%,#1a2140 0%,#0c0f19 45%,#070a12 100%); color:var(--fg);}
    .container{min-height:100svh;display:flex;align-items:center;justify-content:center;padding:20px}
    .card{width:min(920px,95vw);background:linear-gradient(180deg,rgba(255,255,255,.06),rgba(255,255,255,.02));border:1px solid rgba(255,255,255,.08);border-radius:24px;padding:28px 22px;backdrop-filter: blur(8px); box-shadow:0 15px 60px rgba(0,0,0,.45)}
    h1{margin:0 0 6px;font-weight:800;letter-spacing:.6px;background:linear-gradient(90deg,var(--fg),var(--muted));-webkit-background-clip:text;background-clip:text;color:transparent}
    .subtitle{opacity:.82;margin-bottom:14px}
    .dexter{display:flex;gap:14px;align-items:center}
    .cat{font-size:42px;filter:drop-shadow(0 8px 18px rgba(122,240,176,.25));animation:floaty 3.5s ease-in-out infinite}
    .mono{font-family:ui-monospace, SFMono-Regular, Menlo, Consolas, "Liberation Mono", monospace}

    button{appearance:none;border:none;border-radius:16px;padding:14px 20px;font-weight:700;letter-spacing:.4px;cursor:pointer;background:linear-gradient(90deg,var(--hot),#8b5cf6); color:#0b0612; transition:transform .15s ease, box-shadow .2s ease; box-shadow:0 10px 24px rgba(139,92,246,.35)}
    button:hover{transform:translateY(-1px)}
    button:active{transform:translateY(1px)}

    .btn-ghost{background:transparent;color:var(--fg);border:1px dashed rgba(255,255,255,.25)}

    .screen{display:none}
    .screen.active{display:block;animation:slideUp .6s ease}

    .bubble{border-left:4px solid var(--hot); padding:14px 14px; background:rgba(255,255,255,.03); border-radius:12px}

    .inputWrap{display:flex;gap:10px;align-items:center;margin-top:16px}
    input, select{flex:1; background:#0b1020;border:1px solid rgba(255,255,255,.12); border-radius:12px; padding:12px 14px; color:var(--fg); font-size:16px}
    .feedback{margin-top:10px;font-weight:700}
    .bad{color:#ff8fab}
    .good{color:#7af0b0}

    .levelBadge{display:inline-flex;gap:8px;align-items:center;margin:14px 0;padding:10px 14px;border-radius:999px;background:linear-gradient(90deg,#1f2547,#151a33);border:1px solid rgba(255,255,255,.08);animation:badgePop .5s ease}
    .dot{width:10px;height:10px;border-radius:10px;background:var(--lime);box-shadow:0 0 16px rgba(122,240,176,.55)}

    .letters{display:grid;grid-template-columns:repeat(10,1fr);gap:8px;margin-top:8px}
    .slot{aspect-ratio:1/1.2; display:flex;align-items:center;justify-content:center;border-radius:14px;background:#0b1020;border:1px solid rgba(255,255,255,.08);font-weight:900;font-size:22px;opacity:.5}
    .slot.revealed{opacity:1;background:linear-gradient(180deg,#192045,#0e1430); box-shadow: inset 0 0 0 2px rgba(255,255,255,.06), 0 10px 30px rgba(120,104,230,.25)}

    .typeLine{overflow:hidden;white-space:nowrap;border-right:2px solid var(--muted);width:0;animation:type 3.6s steps(60,end) forwards}

    .confetti{pointer-events:none;position:fixed;inset:0;overflow:hidden}

    /* Walk-out finale */
    .overlay{position:fixed;inset:0;background: radial-gradient(1000px 600px at 50% 110%, rgba(0,0,0,.9), rgba(0,0,0,.98)); display:none;align-items:center;justify-content:center;z-index:50}
    .overlay.show{display:flex}
    .walker{position:absolute;left:-20vw;bottom:14vh;font-size:64px;filter:drop-shadow(0 6px 22px rgba(255,255,255,.2)); animation:walkOut 8s linear forwards}
    .magic{font-size: clamp(28px, 6vw, 72px); font-weight:900;letter-spacing:.18em;background:linear-gradient(90deg,#fff,#ffd6e6,#fff);-webkit-background-clip:text;background-clip:text;color:transparent;text-align:center;animation:heartBeat 2.4s ease infinite}
    .pulse{position:absolute;width:220px;height:220px;border-radius:999px;border:2px solid rgba(255,94,161,.6);animation:glowPulse 2.4s infinite}
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <div id="screen-welcome" class="screen active">
        <div class="dexter">
          <div class="cat">🐱‍👤</div>
          <div>
            <h1>Hi, I'm <span class="mono">DEXTER&nbsp;MORGAN</span> — the cat</h1>
            <p class="subtitle">Are you ready for an amazing trip ?? I'm a cat my name is <b>DEXTER MORGAN</b> and I'm going to ask you a few questions to check if you deserve to know the secret question 👻<br><b>are you ready RAHMA ⁉️</b></p>
          </div>
        </div>
        <div class="bubble" style="margin-top:12px">Press the shiny button when your heart says <b>ready</b>…</div>
        <div style="display:flex;gap:12px;margin-top:16px">
          <button id="btn-ready">READY ✅</button>
          <button class="btn-ghost" id="btn-preview">Peek letters</button>
        </div>
        <div style="margin-top:12px">
          <div class="letters" id="lettersBar"></div>
        </div>
      </div>

      <div id="screen-quiz" class="screen">
        <div class="levelBadge" id="levelBadge"><span class="dot"></span><span id="levelText">Level 1</span></div>
        <div id="question" style="font-size:20px;font-weight:700;margin:6px 0 8px"></div>
        <div class="inputWrap" id="inputWrap"></div>
        <div id="feedback" class="feedback"></div>
        <div id="afterMsg" style="margin-top:14px"></div>
        <div style="margin-top:18px;display:flex;gap:10px">
          <button id="btn-submit">Submit</button>
          <button class="btn-ghost" id="btn-skip">I feel lucky ✨</button>
        </div>
      </div>

      <div id="screen-final" class="screen">
        <div class="typeLine" style="font-size:18px;opacity:.85">Preparing something special… keep breathing 💓</div>
        <div style="margin-top:18px" class="letters" id="finalLetters"></div>
        <div style="margin-top:18px">
          <button id="btn-finale">Reveal the secret spell ✨</button>
        </div>
      </div>
    </div>
  </div>

  <div class="overlay" id="overlay">
    <div class="walker">🐾🐈‍⬛</div>
    <div style="display:flex;flex-direction:column;gap:16px;align-items:center">
      <div class="pulse"></div>
      <div class="magic">I&nbsp;LOVE&nbsp;YOU</div>
    </div>
    <canvas class="confetti" id="confetti"></canvas>
  </div>

<script>
const $ = (q)=>document.querySelector(q);
const lettersTarget = "I LOVE YOU"; 
const uniqueAwardPool = ['I','L','O','V','E','Y','O','U']; 
const awarded = new Set();

function initSlots(containerId){
  const bar = document.getElementById(containerId);
  bar.innerHTML='';
  [...lettersTarget].forEach(ch=>{
    const d=document.createElement('div');
    d.className='slot';
    d.dataset.char = ch;
    d.textContent = ch===' ' ? '·' : ''; // لا تظهر الحروف
    bar.appendChild(d);
  });
}
initSlots('lettersBar');
initSlots('finalLetters');

function revealLetter(letter, containerId){
  const slots = [...document.getElementById(containerId).children];
  for(const s of slots){
    if(!s.classList.contains('revealed') && s.dataset.char===letter){
      s.classList.add('revealed');
      s.textContent = letter;
      return true;
    }
  }
  return false;
}

function randomFrom(arr){return arr[Math.floor(Math.random()*arr.length)]}
function normalize(s){return (s||'').toString().normalize('NFKD').replace(/\s+/g,' ').trim().replace(/[,.'`’]/g,'').toLowerCase();}
function ld(a,b){a=normalize(a);b=normalize(b);const m=a.length,n=b.length;if(!m)return n;if(!n)return m;const dp=new Array(n+1);for(let j=0;j<=n;j++)dp[j]=j;for(let i=1;i<=m;i++){let prev=dp[0]++;for(let j=1;j<=n;j++){const tmp=dp[j];dp[j]=Math.min(dp[j]+1,dp[j-1]+1,prev+(a[i-1]===b[j-1]?0:1));prev=tmp;}}return dp[n];}
function approxEq(input,expected){if(/^-?\d+(?:[/.\-]\d+)*$/.test(expected)){const nums=input.replace(/\D/g,''),exp=expected.replace(/\D/g,'');return nums===exp;}if(expected==='YES'||expected==='NO'){return normalize(input).replace(/\s/g,'')===expected.toLowerCase();}const A=normalize(input),B=normalize(expected),dist=ld(A,B),tol=Math.max(1,Math.round(B.length*0.25));return dist<=tol||A.includes(B)||B.includes(A);}

const questions = [
  {q:"1) Which year was John F. Kennedy assassinated?",a:"1963",type:'input'},
  {q:"2) In which year was the Palestinian Nakba?",a:"1948",type:'input'},
  {q:"3) Did you kill John F. Kennedy? Use UPPERCASE to answer YES or NO 🤨",a:"YES",type:'choice',choices:['YES','NO']},
  {q:"4) When did you see the light for the first time? 😺 Use dd/mm/yyyy",a:"23/11/2007",type:'input'},
  {q:"5) Pick the best one: dark chocolate or milk chocolate?",a:"dark chocolate",type:'choice',choices:['dark chocolate','milk chocolate']},
  {q:"6) What's the name of your teddy bear? (lowercase please)",a:"doudou",type:'input'},
  {q:"7) How tall are you? 🙂",a:"154",type:'input'},
  {q:"FINAL LEVEL) Guess the name of this website developer 😁 ⁉️ hint: 4 letters & starts with L",a:"LIWA",type:'input'}
];

const congrats = [
  "congratulations — you've unlocked a new level & a shiny letter… can you guess the next one?",
  "amazing! new stage opened + bonus letter. what comes after this?",
  "wow! level up achieved. a fresh letter joined your quest—ready for the next riddle?",
  "sweet victory! another level, another letter. shall we chase the next secret?",
  "legendary move! gates unlocked & letter granted. dare to continue?"
];

let idx = 0;

function show(screenId){document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));document.getElementById(screenId).classList.add('active');}

function setupQuestion(){
  const {q,type,choices} = questions[idx];
  $('#question').textContent = q;
  $('#feedback').textContent = '';
  $('#afterMsg').textContent = '';
  $('#levelText').textContent = idx+1 < questions.length ? `Level ${idx+1}` : 'Final Level';

  const wrap = $('#inputWrap');
  wrap.innerHTML='';
  if(type==='choice'){
    const sel = document.createElement('select');
    for(const c of choices){ const o=document.createElement('option'); o.value=c; o.textContent=c; sel.appendChild(o); }
    wrap.appendChild(sel);
  } else {
    const inp = document.createElement('input');
    inp.placeholder = 'Type your answer here…';
    wrap.appendChild(inp);
  }
}

function awardRandomLetter(where='lettersBar'){
  const tagged = [];
  uniqueAwardPool.forEach((ch,i)=>{ if(!awarded.has(`${ch}_${i}`)) tagged.push({tag:`${ch}_${i}`,ch}); });
  if(!tagged.length) return null;
  const pick = randomFrom(tagged);
  awarded.add(pick.tag);
  revealLetter(pick.ch,where);
  return pick.ch;
}

function celebrate(){
  const msg = randomFrom(congrats);
  $('#afterMsg').innerHTML = `<div class="bubble">${msg}</div>`;
  awardRandomLetter('lettersBar');
  shootConfetti(14);
}

function shootConfetti(count=12){
  const cvs = document.createElement('canvas');
  cvs.className='confetti';
  document.body.appendChild(cvs);
  const ctx=cvs.getContext('2d');
  const W=cvs.width=innerWidth,H=cvs.height=innerHeight;
  const parts=Array.from({length:count}).map(()=>({x:Math.random()*W,y:-20-Math.random()*H*.2,vy:2+Math.random()*3,vx:(Math.random()-.5)*2,r:4+Math.random()*6,rot:Math.random()*6,col:`hsl(${Math.floor(Math.random()*360)},90%,60%)`}));
  let t=0; const id=requestAnimationFrame(function loop(){ t++; ctx.clearRect(0,0,W,H); parts.forEach(p=>{ p.y+=p.vy; p.x+=p.vx; p.rot+=.1; ctx.save(); ctx.translate(p.x,p.y); ctx.rotate(p.rot); ctx.fillStyle=p.col; ctx.fillRect(-p.r/2,-p.r/2,p.r,p.r*1.4); ctx.restore();}); if(t<180) requestAnimationFrame(loop); else cvs.remove();});
}

$('#btn-ready').onclick = ()=>{ show('screen-quiz'); setupQuestion(); };
$('#btn-preview').onclick = ()=>{ shootConfetti(8); };

$('#btn-submit').onclick = ()=>{
  const spec = questions[idx];
  const ui = $('#inputWrap').querySelector('input,select');
  const value = (ui?.value || '').trim();
  const ok = approxEq(value,spec.a);
  const fb = $('#feedback');

  if(!ok){
    fb.textContent = 'Wrong answer sweety, try again 💔';
    fb.className = 'feedback bad';
    return;
  }

  fb.text
