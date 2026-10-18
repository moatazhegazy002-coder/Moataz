<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no">
<meta name="theme-color" content="#24144f"><title>كوكي: مغامرة إنقاذ عيد الميلاد 🎂</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@500;700;800;900&display=swap');
:root{--pink:#ff78b6;--yellow:#ffe17b;--mint:#7ef3d2;--purple:#815be9}
*{box-sizing:border-box}body{margin:0;background:#211444;color:white;font-family:Tajawal,Arial,sans-serif;min-height:100vh;overflow-x:hidden}button{font:inherit;cursor:pointer;touch-action:manipulation;border:0}button:focus-visible{outline:3px solid white;outline-offset:3px}
.app{width:min(1000px,96%);margin:auto;padding:12px 0 28px}.top{display:flex;justify-content:space-between;align-items:center;gap:8px;margin-bottom:9px;flex-wrap:wrap}.logo{font-weight:900;font-size:19px}.stats{display:flex;gap:7px;flex-wrap:wrap}.chip{background:#ffffff18;border:1px solid #ffffff30;border-radius:99px;padding:7px 12px;font-weight:800}.chip b{color:var(--yellow)}.sound{background:#ffffff20;color:white;border:1px solid #ffffff35;border-radius:50%;width:40px;height:40px;font-size:19px}
.gamebox{position:relative;background:#fff;border:3px solid #ffffffb8;border-radius:20px;overflow:hidden;box-shadow:0 20px 70px #09051c80}.gamehead{display:flex;justify-content:space-between;align-items:center;gap:10px;padding:9px 13px;background:#37236c;color:#fff;font-weight:800}.gamehead small{color:#dfd1ff}.canvas-wrap{position:relative;background:#8fdcf1}.canvas-wrap canvas{display:block;width:100%;height:auto;aspect-ratio:16/9;touch-action:pan-y}.overlay{position:absolute;inset:0;display:flex;align-items:center;justify-content:center;padding:16px;background:#20113ca8;backdrop-filter:blur(3px);z-index:3}.overlay.hidden{display:none}.card{max-width:580px;text-align:center;padding:clamp(17px,4vw,30px);background:linear-gradient(145deg,#fff8ff,#f1e5ff);color:#41265f;border:3px solid white;border-radius:25px;box-shadow:0 15px 50px #1c103a60;animation:pop .3s ease}.card h1{font-size:clamp(28px,5vw,45px);line-height:1.2;color:#7045c4;margin:8px 0}.card p{font-size:clamp(15px,2.5vw,18px);line-height:1.7;margin:10px 0 17px}.heroemoji{font-size:clamp(43px,8vw,70px);line-height:1.2}.btn{padding:12px 20px;border-radius:15px;font-size:17px;font-weight:900;box-shadow:0 4px 0 #42266b35;transition:transform .15s}.btn:active{transform:translateY(2px);box-shadow:none}.pink{background:linear-gradient(135deg,#ff75b5,#ffc27a);color:#451b5b}.light{background:#fff;color:#6940b1;border:2px solid #e6d7ff;box-shadow:none}.hintbar{display:flex;justify-content:space-between;gap:10px;align-items:center;flex-wrap:wrap;padding:10px 12px;background:#35215e;font-weight:800}.hintbar span{font-size:14px;color:#e5d8ff}.controls{direction:ltr;display:flex;justify-content:center;align-items:center;gap:10px;padding:12px;background:#29194d}.ctrl{width:60px;height:55px;border-radius:16px;background:#ffffff1b;border:2px solid #ffffff42;color:#fff;font-size:25px;font-weight:900;user-select:none}.ctrl.jump{width:100px;background:linear-gradient(135deg,#ff77b6,#ffc078);color:#4b1b62;border:0;font-size:17px}.ctrl:active{background:#ffffff40;transform:scale(.96)}.help{font-size:13px;color:#d7c9ff;text-align:center;margin:10px 0 0;line-height:1.6}.touch-tip{display:none}
@keyframes pop{from{opacity:0;transform:scale(.92)}to{opacity:1;transform:scale(1)}}@media(max-width:620px){.app{width:98%;padding-top:6px}.logo{font-size:16px}.chip{font-size:13px;padding:6px 9px}.gamebox{border-radius:14px}.gamehead{font-size:14px}.controls{gap:8px;padding:9px}.ctrl{width:64px;height:58px}.ctrl.jump{width:100px}.hintbar{font-size:14px}.touch-tip{display:inline}.card{border-radius:18px}.btn{font-size:16px;padding:11px 15px}}
</style>
</head>
<body>
<div class="app">
<header class="top"><div class="logo">🌈 كوكي: مغامرة الإنقاذ</div><div class="stats"><div class="chip">⭐ <b id="score">0</b></div><div class="chip">❤️ <b id="lives">3</b></div><button class="sound" id="sound" aria-label="الصوت">🔊</button></div></header>
<div class="gamebox">
<div class="gamehead"><span id="levelName">المرحلة ١: غابة البالونات 🎈</span><small id="objective">اجمعي ٨ نجوم</small></div>
<div class="canvas-wrap"><canvas id="game" width="960" height="540" aria-label="لعبة منصات ثنائية الأبعاد"></canvas>
<div class="overlay" id="overlay"><div class="card" id="card">
<div class="heroemoji">👧🏻 🎈 🦄</div><h1>أنقذي عيد ميلاد كوكي!</h1>
<p>الشرير شوشو خبّى كعكة عيد الميلاد! ساعدي كوكي تقفز فوق المنصات، تجمع النجوم، وتتفادى الوحوش عشان تنقذ الحفلة! 🎂</p>
<p><strong>التحكم:</strong> استخدمي ← → أو A / D للحركة، و Space للقفز. على الموبايل استخدمي الأزرار تحت اللعبة.</p>
<button class="btn pink" id="start">ابدئي المغامرة! 🚀</button>
</div></div></div>
<div class="hintbar"><strong id="message">جاهزة يا بطلة؟ 💖</strong><span>اجمعي النجوم ⭐ وابتعدي عن 👾</span></div>
<div class="controls"><button class="ctrl" id="left" aria-label="تحركي لليسار">◀</button><button class="ctrl" id="right" aria-label="تحركي لليمين">▶</button><button class="ctrl jump" id="jump">اقفزي! ⤴</button></div>
</div>
<p class="help">💡 تلميح: اقفزي فوق الفراغات والوحوش. لما تجمعي كل النجوم، افتحي البوابة السحرية! <span class="touch-tip">الأزرار مناسبة للمس.</span></p>
</div>
<script>
(()=>{
const canvas=document.getElementById('game'),ctx=canvas.getContext('2d');
const $=id=>document.getElementById(id);
const W=960,H=540,ground=445;
let state='intro',level=1,score=0,lives=3,keys={},touch={left:false,right:false},jumpQueued=false,last=0,cam=0,stars=[],enemies=[],platforms=[],particles=[],gates=[],player,goalX=0,levelStars=0,soundOn=true,audio=null,invuln=0;
const palettes=[{sky:'#8ddff4',far:'#b5a0ed',hill:'#87d9b1',ground:'#47aa87',top:'#b6f7c9'},{sky:'#ffbce0',far:'#c5a6ff',hill:'#8ce3db',ground:'#4e9ab1',top:'#b9fff0'},{sky:'#ffc5a4',far:'#c5a0ff',hill:'#a5dba2',ground:'#b77aaf',top:'#ffe3f0'}];
const rand=(a,b)=>a+Math.random()*(b-a);
function beep(type='coin'){if(!soundOn)return;try{audio=audio||new(window.AudioContext||window.webkitAudioContext)();if(audio.state==='suspended')audio.resume();let freqs=type==='win'?[523,659,784,1046]:type==='hurt'?[200,150]:[700,900];freqs.forEach((f,i)=>{let o=audio.createOscillator(),g=audio.createGain();o.type='sine';o.frequency.value=f;o.connect(g);g.connect(audio.destination);let t=audio.currentTime+i*.08;g.gain.setValueAtTime(.001,t);g.gain.exponentialRampToValueAtTime(.09,t+.02);g.gain.exponentialRampToValueAtTime(.001,t+.16);o.start(t);o.stop(t+.17)})}catch(e){}}
function resetPlayer(){player={x:55,y:ground-58,w:42,h:58,vx:0,vy:0,onGround:false,face:1,frame:0};cam=0;invuln=0}
function makeLevel(n){level=n;levelStars=0;stars=[];enemies=[];particles=[];platforms=[];gates=[];goalX=2600;
 if(n===4){goalX=880;platforms.push({x:0,y:ground,w:1800,h:95});resetPlayer();$('levelName').textContent='المرحلة ٤: حفلة كوكي 🎂';$('objective').textContent='روحي عند الكيكة 🎂';$('message').textContent='كل العيلة مستنياكي يا كوكي! 💖';return}
 const gap= n===1?2500:n===2?2750:2900;
 // A friendly side-scrolling platform world with gaps and raised ledges.
 platforms.push({x:0,y:ground,w:520,h:95},{x:590,y:ground,w:390,h:95},{x:1045,y:ground,w:390,h:95},{x:1490,y:ground,w:360,h:95},{x:1900,y:ground,w:400,h:95},{x:2350,y:ground,w:420,h:95});
 const ledges=n===1?[[260,350,135],[690,360,130],[900,315,130],[1180,350,140],[1580,340,145],[1770,300,120],[2050,350,150],[2240,310,120],[2460,340,130]]:n===2?[[200,350,145],[490,310,125],[760,360,150],[1000,300,140],[1290,350,135],[1530,300,140],[1780,350,145],[2080,300,130],[2350,340,150]]:[[230,340,140],[470,300,130],[730,350,150],[970,300,130],[1220,340,150],[1500,290,140],[1740,340,140],[1990,295,150],[2250,340,145],[2500,300,130]];
 ledges.forEach(p=>platforms.push({x:p[0],y:p[1],w:p[2],h:18}));
 let sx=150;for(let i=0;i<13;i++){let x= sx+i*195+rand(-25,25);let y=[ground-70,300,330,365,280,ground-105][i%6];stars.push({x,y,r:15,taken:false,phase:rand(0,6)})}
 let ex=[420,820,1120,1450,1710,2040,2390];ex.forEach((x,i)=>enemies.push({x:x+n*17,y:ground-42,w:42,h:42,alive:true,dir:i%2?1:-1,base:x,phase:rand(0,6)}));
 gates=[{x:goalX,y:ground-90,w:60,h:90}];resetPlayer();$('levelName').textContent=['','المرحلة ١: غابة البالونات 🎈','المرحلة ٢: وادي الحلوى 🍭','المرحلة ٣: قلعة عيد الميلاد 🏰'][n];$('objective').textContent='اجمعي ٨ نجوم';}
function rounded(x,y,w,h,r,fill){ctx.fillStyle=fill;ctx.beginPath();ctx.roundRect(x,y,w,h,r);ctx.fill()}
function drawCloud(x,y,s=1){ctx.fillStyle='#ffffffad';ctx.beginPath();ctx.arc(x,y,20*s,0,Math.PI*2);ctx.arc(x+22*s,y-12*s,27*s,0,Math.PI*2);ctx.arc(x+48*s,y,19*s,0,Math.PI*2);ctx.fill()}
function drawBackground(){let p=palettes[Math.min(level-1,2)];ctx.fillStyle=p.sky;ctx.fillRect(0,0,W,H);
 // sun and clouds
 ctx.fillStyle='#fff2a8';ctx.beginPath();ctx.arc(820,75,35,0,Math.PI*2);ctx.fill();
 for(let i=0;i<6;i++){let x=((i*205-cam*.22)%(W+160)+W+160)%(W+160)-50;drawCloud(x,80+(i%3)*45,.75+(i%2)*.18)}
 ctx.fillStyle=p.far;ctx.beginPath();ctx.moveTo(0,360);for(let x=0;x<=W+40;x+=40)ctx.lineTo(x,280+Math.sin((x+cam*.15)/100)*38);ctx.lineTo(W,H);ctx.lineTo(0,H);ctx.fill();
 ctx.fillStyle=p.hill;ctx.beginPath();ctx.moveTo(0,410);for(let x=0;x<=W+40;x+=40)ctx.lineTo(x,360+Math.sin((x+cam*.25)/90)*24);ctx.lineTo(W,H);ctx.lineTo(0,H);ctx.fill();
 // decorative flowers and candy trees
 for(let i=0;i<18;i++){let x=((i*73-cam*.45)%(W+60)+W+60)%(W+60)-20;let y=420+(i%3)*13;ctx.font='23px sans-serif';ctx.fillText(level===2?'🍭':level===3?'🌷':'🌼',x,y)}
}
function drawPlatform(p){let x=p.x-cam;if(x+p.w<0||x>W)return;rounded(x,p.y,p.w,p.h,7,p.h>20?palettes[Math.min(level-1,2)].ground:'#8b68c9');rounded(x,p.y,p.w,8,5,p.h>20?palettes[Math.min(level-1,2)].top:'#e7d5ff');if(p.h>20){ctx.fillStyle='#ffffff25';for(let i=12;i<p.w;i+=28)ctx.fillRect(x+i,p.y+18,4,4)}}
function drawStar(s){let x=s.x-cam,y=s.y+Math.sin(performance.now()/220+s.phase)*5;if(x<-30||x>W+30)return;ctx.save();ctx.translate(x,y);ctx.rotate(performance.now()/700);ctx.fillStyle='#ffe56e';ctx.strokeStyle='#fff9cb';ctx.lineWidth=2;ctx.beginPath();for(let i=0;i<10;i++){let a=-Math.PI/2+i*Math.PI/5,r=i%2?7:16;ctx.lineTo(Math.cos(a)*r,Math.sin(a)*r)}ctx.closePath();ctx.fill();ctx.stroke();ctx.restore()}
function drawPlayer(){let x=player.x-cam,y=player.y;if(invuln>0&&Math.floor(performance.now()/90)%2===0)return;
 // shadow
 ctx.fillStyle='#2b376b35';ctx.beginPath();ctx.ellipse(x+player.w/2,player.y+player.h+2,22,6,0,0,Math.PI*2);ctx.fill();
 // hair
 ctx.fillStyle='#5c2d4f';ctx.beginPath();ctx.arc(x+21,y+15,17,Math.PI,Math.PI*2);ctx.fill();rounded(x+5,y+14,32,15,9,'#5c2d4f');
 // face
 ctx.fillStyle='#ffcfaa';ctx.beginPath();ctx.arc(x+21,y+21,13,0,Math.PI*2);ctx.fill();
 // hair bow
 ctx.fillStyle='#ff6cae';ctx.beginPath();ctx.moveTo(x+7,y+9);ctx.lineTo(x-2,y+1);ctx.lineTo(x+10,y+2);ctx.fill();ctx.beginPath();ctx.moveTo(x+7,y+9);ctx.lineTo(x+18,y+1);ctx.lineTo(x+10,y+2);ctx.fill();
 // eyes and smile
 ctx.fillStyle='#3b2758';ctx.beginPath();ctx.arc(x+16,y+21,1.8,0,Math.PI*2);ctx.arc(x+26,y+21,1.8,0,Math.PI*2);ctx.fill();ctx.strokeStyle='#b95773';ctx.lineWidth=1.5;ctx.beginPath();ctx.arc(x+21,y+24,4,0,Math.PI);ctx.stroke();
 // dress
 ctx.fillStyle='#ff72b2';ctx.beginPath();ctx.moveTo(x+10,y+33);ctx.lineTo(x+32,y+33);ctx.lineTo(x+40,y+53);ctx.lineTo(x+2,y+53);ctx.closePath();ctx.fill();ctx.fillStyle='#ffe58a';ctx.fillRect(x+9,y+36,24,4);
 // legs
 ctx.strokeStyle='#ffcfaa';ctx.lineWidth=5;ctx.beginPath();ctx.moveTo(x+13,y+52);ctx.lineTo(x+12+(Math.sin(player.frame)*3),y+58);ctx.moveTo(x+29,y+52);ctx.lineTo(x+30-(Math.sin(player.frame)*3),y+58);ctx.stroke();
}
function drawEnemy(e){let x=e.x-cam;if(x<-60||x>W+60)return;ctx.font='38px sans-serif';ctx.fillText(level===2?'🍬':'👾',x,e.y+36+Math.sin(performance.now()/140+e.phase)*4)}
function drawGate(g){let x=g.x-cam;if(x<-100||x>W+100)return;ctx.save();ctx.shadowColor='#fff17b';ctx.shadowBlur=22;rounded(x,g.y,g.w,g.h,22,'#8d5ee8');ctx.shadowBlur=0;ctx.strokeStyle='#ffe67a';ctx.lineWidth=5;ctx.strokeRect(x+7,g.y+7,g.w-14,g.h-14);ctx.font='35px sans-serif';ctx.fillText('🚪',x+9,g.y+56);ctx.restore()}
function drawFamilyCharacter(x, label, kind, dress, hair, scale=1){
 ctx.save();ctx.translate(x,0);ctx.scale(scale,scale);
 // shadow
 ctx.fillStyle='#33234b30';ctx.beginPath();ctx.ellipse(0,ground+1,21,5,0,0,Math.PI*2);ctx.fill();
 // legs and shoes
 ctx.strokeStyle='#f1bd9c';ctx.lineWidth=5;ctx.lineCap='round';ctx.beginPath();ctx.moveTo(-8,ground-20);ctx.lineTo(-9,ground-3);ctx.moveTo(8,ground-20);ctx.lineTo(9,ground-3);ctx.stroke();
 rounded(-16,ground-5,13,6,3,'#51335c');rounded(4,ground-5,13,6,3,'#51335c');
 // arms
 ctx.strokeStyle='#f4c4a5';ctx.lineWidth=7;ctx.beginPath();ctx.moveTo(-13,ground-51);ctx.lineTo(-23,ground-34);ctx.moveTo(13,ground-51);ctx.lineTo(23,ground-34);ctx.stroke();
 // outfit
 if(kind==='dress'){
  ctx.fillStyle=dress;ctx.beginPath();ctx.moveTo(-13,ground-55);ctx.lineTo(13,ground-55);ctx.lineTo(22,ground-20);ctx.lineTo(-22,ground-20);ctx.closePath();ctx.fill();
  ctx.fillStyle='#fff4bf';ctx.fillRect(-9,ground-49,18,4);
 }else{
  rounded(-14,ground-56,28,29,7,dress);rounded(-15,ground-31,30,10,4,dress==='#4d80d9'?'#355bb0':'#42506e');
 }
 // neck and face
 ctx.fillStyle='#f4c4a5';ctx.fillRect(-5,ground-66,10,12);ctx.fillStyle='#ffd1b2';ctx.beginPath();ctx.ellipse(0,ground-76,16,18,0,0,Math.PI*2);ctx.fill();
 // Hair is drawn as a distinct 2D hairstyle for each family member.
 ctx.fillStyle=hair;
 if(label==='بابا'){
  // Dad: tidy rounded short haircut, visible side part and small sideburns
  ctx.beginPath();ctx.moveTo(-16,ground-76);ctx.lineTo(-17,ground-87);ctx.quadraticCurveTo(-20,ground-101,-7,ground-102);ctx.quadraticCurveTo(7,ground-106,15,ground-95);ctx.quadraticCurveTo(19,ground-88,16,ground-77);ctx.lineTo(11,ground-81);ctx.lineTo(10,ground-91);ctx.quadraticCurveTo(2,ground-86,-4,ground-91);ctx.quadraticCurveTo(-9,ground-84,-16,ground-76);ctx.closePath();ctx.fill();
  ctx.strokeStyle='#6b493b';ctx.lineWidth=2.5;ctx.beginPath();ctx.moveTo(-2,ground-97);ctx.quadraticCurveTo(5,ground-101,11,ground-94);ctx.stroke();
 }else if(label==='مودي'){
  // Short youthful hair with soft spikes
  ctx.beginPath();ctx.moveTo(-16,ground-77);ctx.lineTo(-18,ground-91);ctx.lineTo(-10,ground-88);ctx.lineTo(-7,ground-101);ctx.lineTo(0,ground-92);ctx.lineTo(7,ground-100);ctx.lineTo(10,ground-89);ctx.lineTo(17,ground-92);ctx.lineTo(16,ground-77);ctx.quadraticCurveTo(0,ground-87,-16,ground-77);ctx.closePath();ctx.fill();
 }else if(label==='ماما'){
  // Long wavy hair framing the face, with a soft fringe
  ctx.beginPath();ctx.moveTo(-15,ground-83);ctx.quadraticCurveTo(-24,ground-98,-10,ground-101);ctx.quadraticCurveTo(5,ground-108,15,ground-95);ctx.lineTo(17,ground-68);ctx.quadraticCurveTo(12,ground-62,8,ground-70);ctx.lineTo(9,ground-83);ctx.quadraticCurveTo(0,ground-88,-7,ground-83);ctx.lineTo(-9,ground-69);ctx.quadraticCurveTo(-16,ground-63,-18,ground-73);ctx.closePath();ctx.fill();
  ctx.beginPath();ctx.moveTo(-14,ground-86);ctx.quadraticCurveTo(-5,ground-91,0,ground-85);ctx.quadraticCurveTo(8,ground-91,14,ground-84);ctx.lineTo(10,ground-78);ctx.quadraticCurveTo(0,ground-83,-10,ground-77);ctx.closePath();ctx.fill();
 }else if(label==='نوده'){
  // Older sister: long, flowing hair with a clear side part
  ctx.beginPath();ctx.moveTo(-16,ground-82);ctx.quadraticCurveTo(-23,ground-101,-5,ground-103);ctx.quadraticCurveTo(14,ground-104,17,ground-88);ctx.lineTo(19,ground-61);ctx.quadraticCurveTo(12,ground-58,8,ground-69);ctx.lineTo(9,ground-84);ctx.quadraticCurveTo(0,ground-90,-8,ground-82);ctx.lineTo(-10,ground-65);ctx.quadraticCurveTo(-18,ground-61,-19,ground-72);ctx.closePath();ctx.fill();
  ctx.beginPath();ctx.moveTo(-14,ground-88);ctx.quadraticCurveTo(-4,ground-96,5,ground-88);ctx.lineTo(10,ground-81);ctx.quadraticCurveTo(-1,ground-84,-8,ground-79);ctx.closePath();ctx.fill();
 }else{
  // Kholouda: cute twin ponytails and a rounded fringe
  ctx.beginPath();ctx.ellipse(-17,ground-86,7,10,-.25,0,Math.PI*2);ctx.ellipse(17,ground-86,7,10,.25,0,Math.PI*2);ctx.fill();
  ctx.beginPath();ctx.moveTo(-16,ground-80);ctx.quadraticCurveTo(-23,ground-99,-8,ground-102);ctx.quadraticCurveTo(7,ground-106,16,ground-91);ctx.lineTo(14,ground-79);ctx.quadraticCurveTo(4,ground-87,-3,ground-83);ctx.quadraticCurveTo(-9,ground-81,-16,ground-80);ctx.closePath();ctx.fill();
  ctx.fillStyle='#ffdfef';ctx.beginPath();ctx.arc(-17,ground-78,3,0,Math.PI*2);ctx.arc(17,ground-78,3,0,Math.PI*2);ctx.fill();
 }
 // face details
 ctx.fillStyle='#392548';ctx.beginPath();ctx.arc(-6,ground-76,1.7,0,Math.PI*2);ctx.arc(6,ground-76,1.7,0,Math.PI*2);ctx.fill();ctx.strokeStyle='#b85e75';ctx.lineWidth=1.4;ctx.beginPath();ctx.arc(0,ground-71,4,0,Math.PI);ctx.stroke();
 if(label==='بابا'){
  // Dad has a clean-shaven face; keep only subtle eyebrows.
  ctx.fillStyle='#392548';ctx.fillRect(-9,ground-81,6,1.8);ctx.fillRect(3,ground-81,6,1.8);
 }else if(kind==='dress' && label!=='خلوده'){
  // little hair clip
  ctx.fillStyle='#ff78b6';ctx.beginPath();ctx.ellipse(11,ground-94,5,3,.45,0,Math.PI*2);ctx.fill();ctx.fillStyle='#ffe58a';ctx.beginPath();ctx.arc(11,ground-94,1.5,0,Math.PI*2);ctx.fill();
 }
 // name tag
 ctx.font='bold 16px Tajawal,Arial';ctx.textAlign='center';ctx.lineWidth=4;ctx.strokeStyle='#fff8ff';ctx.strokeText(label,0,ground+24);ctx.fillStyle='#48215f';ctx.fillText(label,0,ground+24);ctx.restore();
}
function drawParty(){
 // colorful bunting and balloons
 ctx.strokeStyle='#ff75b5';ctx.lineWidth=4;ctx.beginPath();ctx.moveTo(500-cam,105);ctx.quadraticCurveTo(710-cam,170,950-cam,105);ctx.stroke();
 ['🎈','🎉','⭐','🎈','💖','🎊'].forEach((e,i)=>{ctx.font='30px sans-serif';ctx.fillText(e,510+i*78-cam,132+(i%2)*18)});
 // family characters, drawn in the same cute 2D style as Cookie
 drawFamilyCharacter(555-cam,'بابا','person','#4d80d9','#392747',1.05);
 drawFamilyCharacter(625-cam,'ماما','dress','#ff8dbd','#5c2d4f',1.0);
 drawFamilyCharacter(695-cam,'مودي','person','#56b8a2','#3b2b35',1.0);
 drawFamilyCharacter(865-cam,'نوده','dress','#a77aef','#4d2b4f',1.0);
 drawFamilyCharacter(930-cam,'خلوده','dress','#ffbd70','#5c2d4f',.95);
 // birthday table with legs and cloth
 rounded(750-cam,ground-48,112,9,4,'#8b4bb3');
 ctx.fillStyle='#ff86bd';ctx.beginPath();ctx.moveTo(750-cam,ground-40);ctx.lineTo(862-cam,ground-40);ctx.lineTo(851-cam,ground-5);ctx.lineTo(761-cam,ground-5);ctx.closePath();ctx.fill();
 ctx.fillStyle='#fff0a8';ctx.fillRect(762-cam,ground-5,8,6);ctx.fillRect(842-cam,ground-5,8,6);
 // cake sitting on top of the table
 ctx.save();ctx.textAlign='center';ctx.font='49px sans-serif';ctx.fillText('🎂',806-cam,ground-51);ctx.font='bold 21px Tajawal,Arial';ctx.fillStyle='#7134a0';ctx.lineWidth=5;ctx.strokeStyle='#fff7ff';ctx.strokeText('عيد ميلاد كوكي!',800-cam,ground-112);ctx.fillText('عيد ميلاد كوكي!',800-cam,ground-112);ctx.restore();
}
function draw(){drawBackground();platforms.forEach(drawPlatform);stars.forEach(s=>{if(!s.taken)drawStar(s)});gates.forEach(drawGate);enemies.forEach(drawEnemy);if(level===4)drawParty();drawPlayer();if(state==='play'){ctx.save();rounded(15,12,218,48,13,'#241044eF');ctx.strokeStyle='#ffe17b';ctx.lineWidth=2;ctx.strokeRect(17,14,214,44);ctx.fillStyle='#ffe17b';ctx.font='bold 23px Tajawal,Arial';ctx.textAlign='left';ctx.textBaseline='middle';ctx.direction='ltr';ctx.fillText('⭐ STARS: '+levelStars+' / 8',27,36);ctx.restore()}}
function overlaps(a,b){return a.x<b.x+b.w&&a.x+a.w>b.x&&a.y<b.y+b.h&&a.y+a.h>b.y}
function puff(x,y,emoji='✨'){particles.push({x,y,life:30,emoji,vy:-1.3})}
function update(dt){if(state!=='play')return;let speed=260;let left=keys.ArrowLeft||keys.a||keys.A||touch.left,right=keys.ArrowRight||keys.d||keys.D||touch.right;
 player.vx=(right?1:0)-(left?1:0);if(player.vx)player.face=Math.sign(player.vx);player.x+=player.vx*speed*dt;player.x=Math.max(0,Math.min(goalX+90,player.x));if(player.vx)player.frame+=dt*13;
 if((jumpQueued||keys[' ']||keys.ArrowUp||keys.w||keys.W)&&player.onGround){player.vy=-590;player.onGround=false;beep('jump')}jumpQueued=false;
 player.vy+=1450*dt;player.y+=player.vy*dt;player.onGround=false;
 const oldBottom=player.y+player.h-player.vy*dt;
 for(let p of platforms){if(player.x+player.w>p.x&&player.x<p.x+p.w&&oldBottom<=p.y+5&&player.y+player.h>=p.y&&player.vy>=0){player.y=p.y-player.h;player.vy=0;player.onGround=true}}
 if(player.y>H+40){hurt(true)}
 for(let s of stars){if(!s.taken&&overlaps({x:player.x,y:player.y,w:player.w,h:player.h},{x:s.x-14,y:s.y-14,w:28,h:28})){s.taken=true;levelStars++;score+=10;$('score').textContent=score;$('objective').textContent='اجمعي '+Math.max(0,8-levelStars)+' نجوم';puff(s.x,s.y,'⭐');beep('coin');$('message').textContent='نجمة جديدة! شاطرة يا كوكي ⭐';if(levelStars>=8){$('message').textContent='رائع! النجوم كلها معاكي، دوري على البوابة! 🚪'}}}
 for(let e of enemies){if(!e.alive)continue;e.x=e.base+Math.sin(performance.now()/550+e.phase)*45;if(invuln<=0&&overlaps(player,{x:e.x+2,y:e.y+3,w:38,h:39})){if(player.vy>80&&player.y+player.h<e.y+27){e.alive=false;player.vy=-370;score+=15;$('score').textContent=score;puff(e.x,e.y,'💥');beep('coin')}else hurt(false)}}
 if(invuln>0)invuln-=dt;
 if(level===4&&player.x+player.w>840){nextLevel();return}
 for(let g of gates){if(overlaps(player,{x:g.x,y:g.y,w:g.w,h:g.h})){if(levelStars>=8){nextLevel()}else{$('message').textContent='البوابة سحرية ومقفولة! اجمعي ٨ نجوم الأول ⭐';puff(g.x,g.y,'🔒')}}}
 cam=Math.max(0,Math.min(goalX-W+130,player.x-W*.32));particles.forEach(p=>{p.x+=rand(-1,1);p.y+=p.vy;p.life--});particles=particles.filter(p=>p.life>0);
}
function hurt(fall){if(invuln>0)return;lives--;$('lives').textContent=lives;invuln=1.4;beep('hurt');$('message').textContent=fall?'أوه! وقعتِ. هترجعي لبداية المرحلة! 💗':'الوحش لمسِك! خلي بالك منه يا كوكي! 💗';puff(player.x,player.y,'💫');if(lives<=0){state='over';showOverlay('نجرّب تاني يا كوكي؟ 💖','ولا يهمك! هتبدئي من أول المرحلة دي، مش من أول اللعبة. ❤️','إعادة المرحلة 🔄','retry')}else{player.x=55;player.y=ground-player.h;player.vx=0;player.vy=0;player.onGround=true;cam=0}}
function nextLevel(){if(level<4){state='between';beep('win');showOverlay(level===3?'وصلنا للحفلة! 🎂':'عاش يا كوكي! 🌟',level===3?'خلصتي المغامرة! امشي عند عيلتك والكيكة عشان تبدأ حفلة عيد ميلادك! 💖':'خلصتي المرحلة! جاهزة لمغامرة أصعب ومفاجآت جديدة؟','يلا نكمل! 🚀','next')}else{state='won';beep('win');showOverlay('عيد ميلاد سعيد يا كوكي! 🎂💖','كل سنة و انتي طيبة يا كوكي هابي بيرث داي يا اجمل بنوتة في الدنيا و تبقي مبسوطة دايما و اشطر واحدة في العالم🥰🥰💌.','احتفلي من جديد! 🎉','again');confetti()}}
function showOverlay(title,desc,button,action){$('card').innerHTML='<div class="heroemoji">🎉 ⭐ 🎂</div><h1>'+title+'</h1><p>'+desc+'</p><button class="btn pink" id="overlayAction">'+button+'</button>';$('overlay').classList.remove('hidden');$('overlayAction').onclick=()=>{if(action==='next'){makeLevel(level+1);state='play';$('overlay').classList.add('hidden');$('message').textContent='المرحلة الجديدة بدأت! يلا يا كوكي!'}else if(action==='retry'){lives=3;$('lives').textContent=lives;makeLevel(level);state='play';$('overlay').classList.add('hidden');$('message').textContent='بداية المرحلة من جديد! تقدري تعمليها يا كوكي! 💖'}else if(action==='again'){score=0;lives=3;$('score').textContent=score;$('lives').textContent=lives;makeLevel(1);state='intro';$('card').innerHTML='<div class="heroemoji">👧🏻 🎈 🦄</div><h1>أنقذي عيد ميلاد كوكي!</h1><p>الشرير شوشو خبّى كعكة عيد الميلاد! ساعدي كوكي تقفز فوق المنصات، تجمع النجوم، وتتفادى الوحوش عشان تنقذ الحفلة! 🎂</p><p><strong>التحكم:</strong> ← → أو A / D للحركة، و Space للقفز. على الموبايل استخدمي الأزرار تحت اللعبة.</p><button class="btn pink" id="start">ابدئي المغامرة! 🚀</button>';$('overlay').classList.remove('hidden');$('start').onclick=startGame}}}
function startGame(){score=0;lives=3;$('score').textContent=score;$('lives').textContent=lives;makeLevel(1);state='play';$('overlay').classList.add('hidden');$('message').textContent='اجمعي النجوم وابتعدي عن الوحوش! ⭐'}
function confetti(){for(let i=0;i<60;i++){let e=document.createElement('span');e.className='confetti';e.textContent=['🎉','⭐','💖','🎊','✨'][Math.floor(Math.random()*5)];e.style.left=Math.random()*100+'vw';e.style.animationDelay=Math.random()+'s';document.body.appendChild(e);setTimeout(()=>e.remove(),4000)}}
function loop(t){let dt=Math.min((t-last)/1000||0,.035);last=t;update(dt);draw();requestAnimationFrame(loop)}
window.addEventListener('keydown',e=>{if(['ArrowLeft','ArrowRight','ArrowUp',' ','a','A','d','D','w','W'].includes(e.key)){keys[e.key]=true;if(e.key===' '||e.key==='ArrowUp'||e.key==='w'||e.key==='W')jumpQueued=true;e.preventDefault()}});
window.addEventListener('keyup',e=>{keys[e.key]=false});
function hold(id,prop){let b=$(id);const on=e=>{e.preventDefault();touch[prop]=true};const off=e=>{e.preventDefault();touch[prop]=false};b.addEventListener('pointerdown',on);['pointerup','pointercancel','pointerleave'].forEach(ev=>b.addEventListener(ev,off))}
hold('left','left');hold('right','right');$('jump').addEventListener('pointerdown',e=>{e.preventDefault();jumpQueued=true});
$('start').onclick=startGame;$('sound').onclick=()=>{soundOn=!soundOn;$('sound').textContent=soundOn?'🔊':'🔇';if(soundOn)beep()};
makeLevel(1);state='intro';requestAnimationFrame(loop);
})();
</script>
</body></html>
