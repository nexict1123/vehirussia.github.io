<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="color-scheme" content="light">
<title>История и культура — интерактивный проект</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300;0,9..144,500;1,9..144,300&family=Instrument+Sans:wght@400;500&display=swap">
<style>
:root{color-scheme:light;--bg:#eae3d6;--paper:#f4efe5;--ink:#315f78;--mute:#7b817d;--red:#398bb4;--serif:"Fraunces",Georgia,serif;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#eae3d6;--paper:#f4efe5;--ink:#315f78;--mute:#7b817d;--red:#398bb4}}}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
html,body{margin:0;height:100%}
body{background:var(--bg);color:var(--ink);font-family:"Instrument Sans",system-ui,sans-serif;overflow:hidden;background-image:radial-gradient(ellipse at 12% 10%,color-mix(in srgb,var(--red) 9%,transparent),transparent 42%),radial-gradient(ellipse at 90% 85%,color-mix(in srgb,#1e90c5 12%,transparent),transparent 38%)}
a{color:inherit}
:focus-visible{outline:2px solid var(--red);outline-offset:4px}

.page{position:absolute;inset:0;overflow-y:auto;overflow-x:hidden;padding:clamp(16px,3vw,36px);
opacity:0;visibility:hidden;transform:translateY(24px);transition:opacity .7s ease,transform .8s cubic-bezier(.2,.7,.2,1),visibility 0s .8s}
.page.on{opacity:1;visibility:visible;transform:none;transition-delay:.15s,.15s,0s}

/* титульный лист */
.sheet{position:relative;overflow:hidden;min-height:100%;border:1px solid color-mix(in srgb,var(--ink) 35%,transparent);border-radius:5px;background:var(--paper);padding:clamp(24px,5vw,64px);display:flex;flex-direction:column;justify-content:space-between;gap:40px;box-shadow:0 18px 60px color-mix(in srgb,var(--ink) 7%,transparent)}
.sheet:before{content:"";position:absolute;width:clamp(180px,35vw,460px);height:clamp(180px,35vw,460px);right:-9%;top:12%;border:1px solid color-mix(in srgb,var(--red) 45%,transparent);border-radius:50%;box-shadow:0 0 0 22px color-mix(in srgb,var(--red) 5%,transparent),0 0 0 48px color-mix(in srgb,var(--red) 4%,transparent);pointer-events:none}
.sheet>*{position:relative;z-index:1}
.org{margin:0;text-align:center;font-size:12px;line-height:1.7;letter-spacing:.16em;text-transform:uppercase;color:var(--mute)}
.title{margin:0;max-width:10ch;font-family:var(--serif);font-weight:300;font-style:italic;font-size:clamp(54px,10vw,132px);line-height:.98;letter-spacing:-.045em;color:var(--ink)}
.sub{margin:24px 0 0;max-width:43ch;font-size:clamp(16px,1.6vw,20px);line-height:1.7;color:var(--mute)}
.go{display:inline-flex;align-items:center;gap:14px;margin-top:36px;padding:14px 22px 14px 16px;border:1px solid var(--ink);border-radius:999px;background:var(--ink);color:var(--paper);font:500 15px "Instrument Sans",sans-serif;cursor:pointer;transition:transform .3s,background .3s,color .3s}
.go:hover{transform:translateY(-2px);background:var(--red);color:#fff}
.go i{width:24px;height:24px;border:1px solid currentColor;border-radius:50%;position:relative;transition:transform .5s cubic-bezier(.65,0,.25,1),box-shadow .4s}
.go i:after{content:"↗";position:absolute;inset:0;display:grid;place-items:center;font-style:normal;font-size:13px}
.go:hover i{transform:translateX(8px);box-shadow:0 0 0 8px color-mix(in srgb,var(--red) 14%,transparent)}
.who{display:flex;justify-content:space-between;gap:24px;flex-wrap:wrap;font-size:14px;line-height:1.8;padding-top:24px;border-top:1px solid color-mix(in srgb,var(--red) 40%,transparent)}
.who span{display:block;color:var(--mute)}
.who div:last-child{text-align:right}
.city{margin:0;text-align:center;font-size:12px;letter-spacing:.2em;text-transform:uppercase;color:var(--mute)}

/* верхняя панель */
.bar{display:flex;justify-content:space-between;align-items:baseline;gap:16px;margin-bottom:24px;padding:10px 0 18px;border-bottom:1px solid color-mix(in srgb,var(--red) 40%,transparent)}
.bar a{font-size:14px;color:var(--mute);text-decoration:none;transition:color .2s}
.bar a:hover{color:var(--red)}
.bar h1{margin:0;font-family:var(--serif);font-style:italic;font-weight:300;font-size:clamp(22px,3vw,34px)}

/* выбор шкалы */
.choices{display:grid;grid-template-columns:1fr 1fr;gap:clamp(14px,2.4vw,28px);min-height:calc(100% - 52px)}
.choice{position:relative;overflow:hidden;display:flex;flex-direction:column;justify-content:space-between;gap:32px;min-height:340px;padding:clamp(24px,3.5vw,44px);border:1px solid color-mix(in srgb,var(--red) 55%,transparent);border-radius:4px;background:color-mix(in srgb,var(--paper) 94%,#e3d7c3);text-decoration:none;transition:transform .4s,background .5s,border-color .5s,box-shadow .4s}
.choice:hover{transform:translateY(-5px);background:color-mix(in srgb,#d9cdb8 22%,var(--paper));border-color:var(--red);box-shadow:0 18px 38px color-mix(in srgb,var(--ink) 8%,transparent)}
.num{font-family:var(--serif);font-weight:300;font-style:italic;font-size:clamp(72px,10vw,132px);line-height:1;color:var(--red);opacity:.9}
.choice h2{margin:0 0 14px;font-family:var(--serif);font-weight:500;font-size:clamp(30px,3.8vw,48px);line-height:1.08;letter-spacing:-.025em}
.choice p{margin:0;max-width:36ch;font-size:16px;line-height:1.75;color:var(--mute)}
.open{display:flex;align-items:center;gap:14px;font-weight:500;font-size:14px;letter-spacing:.02em}
.open i{width:30px;height:30px;border:1px solid var(--red);border-radius:50%;position:relative;transition:transform .5s cubic-bezier(.65,0,.25,1),background .4s}
.open i:after{content:"↗";position:absolute;inset:0;display:grid;place-items:center;color:var(--red);font-size:14px}
.choice:hover .open i{transform:translate(4px,-2px);background:var(--red)}
.choice:hover .open i:after{color:#fff}
@media (max-width:760px){.choices{grid-template-columns:1fr}.choice{min-height:240px}.sheet:before{right:-28%;top:24%;opacity:.7}}

/* шкала */
.lane{padding:clamp(8px,4vh,48px) 0;background:var(--paper);border:1px solid color-mix(in srgb,var(--red) 35%,transparent);border-radius:4px;padding-inline:clamp(16px,3vw,36px);}
.track{position:relative;height:128px;touch-action:none;user-select:none;margin:0 2%}
.line{position:absolute;left:0;right:0;top:50%;height:2px;margin-top:-1px;background:color-mix(in srgb,var(--red) 70%,transparent);border-radius:2px}
.line::before{content:"";position:absolute;left:0;right:0;top:14px;height:8px;background:repeating-linear-gradient(90deg,var(--mute) 0 1px,transparent 1px 14px);opacity:.45}
.tick{position:absolute;top:50%;width:2px;margin-left:-1px;background:var(--mute);border:0;padding:0;border-radius:2px;cursor:pointer;transform:translateY(-50%);transition:background .5s}
.tick span{position:absolute;top:calc(100% + 10px);left:50%;transform:translateX(-50%);font-size:15px;color:var(--mute);white-space:nowrap;transition:color .5s}
.tick.on span{color:var(--ink)}
.tick:hover{background:var(--red)}
.ring{position:absolute;top:50%;width:58px;height:58px;margin:-29px 0 0 -29px;border:2px solid var(--red);border-radius:50%;cursor:grab;
background:color-mix(in srgb,var(--paper) 88%,transparent);box-shadow:inset 0 0 0 5px var(--paper),0 0 0 1px color-mix(in srgb,var(--red) 15%,transparent);transition:left .75s cubic-bezier(.65,0,.25,1),box-shadow .4s;z-index:2}
.ring.drag{cursor:grabbing;transition:box-shadow .4s;box-shadow:0 0 0 12px color-mix(in srgb,var(--red) 14%,transparent)}
.stage{position:relative;min-height:240px;margin-top:clamp(24px,6vh,64px)}
.ev{position:absolute;inset:0;display:grid;grid-template-columns:auto 1fr;gap:6px 36px;align-content:start;opacity:0;transform:translateY(16px);pointer-events:none;
transition:opacity .6s ease,transform .7s cubic-bezier(.2,.7,.2,1)}
.ev.on{opacity:1;transform:none;pointer-events:auto;transition-delay:.12s}
.ev.out{transform:translateY(-16px)}
.year{grid-row:span 2;margin:0;font-family:var(--serif);font-weight:300;font-size:clamp(56px,10vw,128px);line-height:1;letter-spacing:-.02em;font-variant-numeric:tabular-nums}
.ev h2{margin:6px 0 0;font-family:var(--serif);font-weight:500;font-size:clamp(22px,3vw,36px);line-height:1.2}
.ev .txt{margin:0;font-size:18px;line-height:1.55;color:var(--mute);max-width:60ch}
.other{margin:8px 0 0;font-size:15px}
.other a{color:var(--mute);text-decoration:none}.other a:hover{color:var(--red)}
@media (max-width:600px){.page{padding:12px}.sheet{padding:24px 20px;gap:30px}.ev{grid-template-columns:1fr;gap:10px}.year{grid-row:auto}.stage{min-height:290px}.who div:last-child{text-align:left}.ring{width:48px;height:48px;margin:-24px 0 0 -24px}.bar{align-items:flex-start;flex-direction:column;gap:8px}.bar h1{order:-1}}
@media (prefers-reduced-motion:reduce){*{transition-duration:.01s!important;transition-delay:0s!important}}
</style>
</head>
<body>

<section class="page on" id="cover" aria-label="Титульный лист">
<div class="sheet">
<p class="org">Название учебного заведения<br>Факультет, кафедра</p>
<div>
<h1 class="title">Название проекта</h1>
<p class="sub">Интерактивные временные шкалы: культура и история России. Здесь будет подзаголовок или тема работы.</p>
<button class="go" id="go"><i></i>Открыть временные шкалы</button>
</div>
<div class="who"><div><span>Выполнил(а)</span>Имя Фамилия, группа</div><div><span>Руководитель</span>Имя Фамилия, должность</div></div>
<p class="city">Город, 2026</p>
</div>
</section>

<section class="page" id="choose" aria-label="Выбор шкалы">
<div class="bar"><a href="#">← Титульный лист</a><h1>Выберите шкалу</h1></div>
<div class="choices">
<a class="choice" href="#culture"><span class="num">1</span><div><h2>Шкала культуры</h2><p>Здесь будет краткое описание шкалы: что в неё входит и какой период охватывает.</p></div><span class="open"><i></i>Открыть</span></a>
<a class="choice" href="#russia"><span class="num">2</span><div><h2>Общая история России</h2><p>Здесь будет краткое описание шкалы: что в неё входит и какой период охватывает.</p></div><span class="open"><i></i>Открыть</span></a>
</div>
</section>

<section class="page" id="culture" aria-label="Шкала культуры">
<div class="bar"><a href="#choose">← Выбор шкалы</a><h1>Шкала культуры</h1></div>
<div class="lane" id="lane1"></div>
<p class="other"><a href="#russia">Перейти к шкале «Общая история России»</a></p>
</section>

<section class="page" id="russia" aria-label="Общая история России">
<div class="bar"><a href="#choose">← Выбор шкалы</a><h1>Общая история России</h1></div>
<div class="lane" id="lane2"></div>
<p class="other"><a href="#culture">Перейти к шкале культуры</a></p>
</section>

<script>
const PH="Здесь будет описание события. Текст-заглушка до получения настоящих данных.";
const LANES=[
{title:"Шкала культуры",heights:[50,38,58,34,46,62],events:[
{y:1037,t:"Закладка Софийского собора в Киеве",d:PH},
{y:1411,t:"«Троица» Андрея Рублёва",d:PH},
{y:1564,t:"Первая датированная печатная книга «Апостол»",d:PH},
{y:1755,t:"Основание Московского университета",d:PH},
{y:1799,t:"Рождение Александра Пушкина",d:PH},
{y:1869,t:"Издание романа «Война и мир»",d:PH}]},
{title:"Общая история России",heights:[44,60,36,54,42,64,38,56],events:[
{y:862,t:"Начало правления Рюрика",d:PH},
{y:988,t:"Крещение Руси",d:PH},
{y:1380,t:"Куликовская битва",d:PH},
{y:1547,t:"Венчание Ивана IV на царство",d:PH},
{y:1613,t:"Начало правления династии Романовых",d:PH},
{y:1703,t:"Основание Санкт-Петербурга",d:PH},
{y:1861,t:"Отмена крепостного права",d:PH},
{y:1917,t:"Революция",d:PH}]}
];
const A=4,B=96;

function lane(root,cfg){
const evs=cfg.events,n=evs.length,pos=i=>A+i*(B-A)/(n-1);
root.innerHTML='<div class="track"><div class="line"></div></div><div class="stage" aria-live="polite"></div>';
const track=root.querySelector('.track'),stage=root.querySelector('.stage');
const ring=document.createElement('div');ring.className='ring';ring.tabIndex=0;ring.setAttribute('role','slider');
ring.setAttribute('aria-label',cfg.title);ring.setAttribute('aria-valuemin',1);ring.setAttribute('aria-valuemax',n);
track.appendChild(ring);
const ticks=[],cards=[];let cur=-1,dragging=false;
evs.forEach((e,i)=>{
const b=document.createElement('button');b.className='tick';b.style.left=pos(i)+'%';b.style.height=cfg.heights[i%cfg.heights.length]+'px';
b.setAttribute('aria-label',e.y+': '+e.t);b.innerHTML='<span>'+e.y+'</span>';b.onclick=()=>go(i);track.insertBefore(b,ring);ticks.push(b);
const c=document.createElement('article');c.className='ev';
c.innerHTML='<p class="year">'+e.y+'</p><h2>'+e.t+'</h2><p class="txt">'+e.d+'</p>';stage.appendChild(c);cards.push(c);
});
function show(i){
if(i===cur)return;
if(cur>=0){const o=cards[cur];o.classList.remove('on');o.classList.add('out');setTimeout(()=>o.classList.remove('out'),700)}
cards[i].classList.remove('out');cards[i].classList.add('on');
ticks.forEach((t,k)=>t.classList.toggle('on',k===i));
ring.setAttribute('aria-valuenow',i+1);ring.setAttribute('aria-valuetext',evs[i].y+': '+evs[i].t);cur=i;
}
function go(i){i=Math.max(0,Math.min(n-1,i));ring.style.left=pos(i)+'%';show(i)}
function nearest(p){let k=0,m=1e9;for(let i=0;i<n;i++){const d=Math.abs(pos(i)-p);if(d<m){m=d;k=i}}return k}
function pct(ev){const r=track.getBoundingClientRect();return Math.max(A,Math.min(B,(ev.clientX-r.left)/r.width*100))}
ring.addEventListener('pointerdown',e=>{dragging=true;ring.classList.add('drag');ring.setPointerCapture(e.pointerId);ring.style.transition='box-shadow .4s';e.preventDefault()});
ring.addEventListener('pointermove',e=>{if(!dragging)return;const p=pct(e);ring.style.left=p+'%';show(nearest(p))});
const end=()=>{if(!dragging)return;dragging=false;ring.classList.remove('drag');ring.style.transition='';go(cur)};
ring.addEventListener('pointerup',end);ring.addEventListener('pointercancel',end);
ring.addEventListener('keydown',e=>{
if(e.key==='ArrowRight'||e.key==='ArrowDown'){go(cur+1);e.preventDefault()}
if(e.key==='ArrowLeft'||e.key==='ArrowUp'){go(cur-1);e.preventDefault()}
if(e.key==='Home'){go(0);e.preventDefault()}if(e.key==='End'){go(n-1);e.preventDefault()}
});
track.addEventListener('wheel',e=>{if(!e.deltaX&&Math.abs(e.deltaY)<4)return;e.preventDefault();clearTimeout(track._w);track._w=setTimeout(()=>go(cur+((e.deltaX||e.deltaY)>0?1:-1)),40)},{passive:false});
ring.style.transition='none';go(0);requestAnimationFrame(()=>ring.style.transition='');
return{reset:()=>{ring.style.transition='none';go(0);requestAnimationFrame(()=>ring.style.transition='')}};
}
const lanes={culture:lane(document.getElementById('lane1'),LANES[0]),russia:lane(document.getElementById('lane2'),LANES[1])};

const pages={'':'cover',choose:'choose',culture:'culture',russia:'russia'};
function route(){
const h=location.hash.slice(1),id=pages[h]||'cover';
Object.values(pages).forEach(p=>{const el=document.getElementById(p);el.classList.toggle('on',p===id);if(p===id)el.scrollTop=0});
}
document.getElementById('go').onclick=()=>{location.hash='choose'};
addEventListener('hashchange',route);route();
</script>
</body>
</html>
