<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Brújula Interior Gamificada</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:'Poppins',sans-serif;
background:linear-gradient(135deg,#fff5f7,#f8f1ec);
min-height:100vh;
color:#4b3b40;
overflow-x:hidden;
}

.game-wrapper{
max-width:1400px;
margin:auto;
padding:30px 20px 60px;
}

.hero{
position:relative;
padding:45px 30px;
border-radius:36px;
background:linear-gradient(135deg,#fff,#fff7fb);
box-shadow:0 20px 60px rgba(0,0,0,.08);
overflow:hidden;
margin-bottom:35px;
}

.hero::before{
content:'';
position:absolute;
width:450px;
height:450px;
background:radial-gradient(circle,#efb6c4 0%, transparent 70%);
right:-150px;
top:-180px;
opacity:.35;
}

.badge{
display:inline-block;
padding:10px 18px;
background:#f3e4e0;
border-radius:999px;
font-size:12px;
font-weight:600;
letter-spacing:1px;
margin-bottom:20px;
position:relative;
z-index:2;
}

.hero h1{
font-size:56px;
line-height:1.1;
margin-bottom:20px;
background:linear-gradient(90deg,#d58ab1,#ef8f6d,#f0b55c);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
position:relative;
z-index:2;
}

.hero p{
max-width:900px;
font-size:18px;
line-height:1.8;
position:relative;
z-index:2;
}

.top-panel{
display:grid;
grid-template-columns:1fr 280px;
gap:25px;
margin-bottom:30px;
}

.question-box{
background:rgba(255,255,255,.82);
backdrop-filter:blur(12px);
padding:35px;
border-radius:30px;
box-shadow:0 10px 30px rgba(0,0,0,.08);
position:relative;
overflow:hidden;
}

.question-box::after{
content:'';
position:absolute;
width:220px;
height:220px;
background:radial-gradient(circle,#f0c4d1 0%, transparent 70%);
right:-90px;
bottom:-90px;
opacity:.45;
}

.question-number{
font-size:13px;
letter-spacing:1px;
font-weight:700;
color:#b3728a;
margin-bottom:15px;
}

.question-text{
font-size:34px;
font-weight:700;
line-height:1.35;
position:relative;
z-index:2;
}

.timer-card{
background:linear-gradient(135deg,#d58ab1,#f0a36d);
color:white;
padding:30px;
border-radius:30px;
text-align:center;
box-shadow:0 12px 35px rgba(0,0,0,.12);
}

.timer-title{
font-size:13px;
letter-spacing:1px;
margin-bottom:10px;
opacity:.9;
}

.timer-number{
font-size:72px;
font-weight:700;
line-height:1;
}

.timer-sub{
margin-top:10px;
font-size:14px;
opacity:.9;
}

.cards-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:24px;
}

.choice-card{
background:white;
border-radius:28px;
overflow:hidden;
box-shadow:0 12px 35px rgba(0,0,0,.08);
transition:.35s ease;
cursor:pointer;
position:relative;
}

.choice-card:hover{
transform:translateY(-10px) scale(1.02);
box-shadow:0 20px 50px rgba(0,0,0,.14);
}

.choice-image{
height:190px;
background-size:cover;
background-position:center;
position:relative;
}

.choice-image::after{
content:'';
position:absolute;
inset:0;
background:linear-gradient(to top,rgba(0,0,0,.6),transparent);
}

.choice-level{
position:absolute;
top:16px;
left:16px;
padding:8px 14px;
background:rgba(255,255,255,.88);
backdrop-filter:blur(10px);
border-radius:999px;
font-size:11px;
font-weight:700;
letter-spacing:1px;
z-index:2;
}

.choice-content{
padding:24px;
}

.choice-title{
font-size:24px;
font-weight:700;
margin-bottom:12px;
}

.choice-text{
font-size:15px;
line-height:1.8;
color:#67575c;
}

.choice-points{
margin-top:18px;
font-size:13px;
font-weight:600;
color:#b06b83;
}

.result-box{
margin-top:30px;
padding:35px;
border-radius:30px;
background:linear-gradient(135deg,#fff,#fff8fb);
box-shadow:0 12px 35px rgba(0,0,0,.08);
display:none;
}

.result-box.active{
display:block;
animation:fadeIn .5s ease;
}

.result-box h2{
font-size:36px;
margin-bottom:15px;
background:linear-gradient(90deg,#d58ab1,#ef8f6d);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

.result-box p{
font-size:18px;
line-height:1.9;
}

.next-btn{
margin-top:24px;
padding:15px 26px;
border:none;
border-radius:999px;
background:linear-gradient(135deg,#d58ab1,#ef8f6d);
color:white;
font-size:16px;
font-weight:600;
cursor:pointer;
transition:.3s ease;
}

.next-btn:hover{
transform:scale(1.05);
}

.progress-bar{
height:12px;
background:#f0e4e8;
border-radius:999px;
overflow:hidden;
margin-top:25px;
}

.progress-fill{
height:100%;
width:0%;
background:linear-gradient(90deg,#d58ab1,#ef8f6d,#f0b55c);
transition:.5s ease;
}

@keyframes fadeIn{
from{opacity:0;transform:translateY(20px);} 
to{opacity:1;transform:translateY(0);} 
}

@media(max-width:900px){
.top-panel{
grid-template-columns:1fr;
}

.hero h1{
font-size:40px;
}

.question-text{
font-size:28px;
}
}

@media(max-width:650px){
.hero h1{
font-size:32px;
}

.question-text{
font-size:24px;
}

.cards-grid{
grid-template-columns:1fr;
}
}

</style>
</head>
<body>

<div class="game-wrapper">

<div class="hero">
<div class="badge">INNER DEVELOPMENT GOALS · EXPERIENCIA GAMIFICADA</div>
<h1>Brújula Interior</h1>
<p>
Explora preguntas sobre propósito, consciencia y proyección de vida. Todas las respuestas son válidas, pero cada elección refleja distintos niveles de crecimiento interior.
</p>
</div>

<div class="top-panel">

<div class="question-box">
<div class="question-number" id="questionNumber">PREGUNTA 1 DE 5</div>
<div class="question-text" id="questionText"></div>

<div class="progress-bar">
<div class="progress-fill" id="progressFill"></div>
</div>
</div>

<div class="timer-card">
<div class="timer-title">TIEMPO INTERIOR</div>
<div class="timer-number" id="timer">20</div>
<div class="timer-sub">segundos para reflexionar</div>
</div>

</div>

<div class="cards-grid" id="cardsGrid"></div>

<div class="result-box" id="resultBox">
<h2 id="resultTitle"></h2>
<p id="resultText"></p>
<button class="next-btn" onclick="nextQuestion()">Continuar exploración</button>
<button class="next-btn" onclick="showProjection()" style="margin-left:12px;background:linear-gradient(135deg,#ef8f6d,#d58ab1);">Mirar tu proyección</button>
</div>

</div>

<script>

const questions = [
{
question:'¿Qué guía más tus decisiones cuando enfrentas un nuevo desafío?',
options:[
{
title:'Claridad Interior',
level:'CONSCIENCIA EXPANSIVA',
text:'Escuchas tu intuición y conectas tus decisiones con propósito profundo.',
points:5,
image:'https://images.unsplash.com/photo-1506744038136-46273834b3fb?q=80&w=1200&auto=format&fit=crop'
},
{
title:'Aprendizaje',
level:'CRECIMIENTO',
text:'Ves cada desafío como una oportunidad para evolucionar.',
points:4,
image:'https://images.unsplash.com/photo-1496307042754-b4aa456c4a2d?q=80&w=1200&auto=format&fit=crop'
},
{
title:'Seguridad',
level:'ESTABILIDAD',
text:'Prefieres caminos conocidos y emocionalmente seguros.',
points:3,
image:'https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=1200&auto=format&fit=crop'
}
]
},
{
question:'¿Cómo imaginas tu impacto en el mundo dentro de 10 años?',
options:[
{
title:'Transformar Comunidades',
level:'LIDERAZGO HUMANO',
text:'Sueñas con inspirar cambios positivos y bienestar colectivo.',
points:5,
image:'https://images.unsplash.com/photo-1529156069898-49953e39b3ac?q=80&w=1200&auto=format&fit=crop'
},
{
title:'Crear Innovación',
level:'VISIÓN',
text:'Deseas impulsar ideas y soluciones sostenibles.',
points:4,
image:'https://images.unsplash.com/photo-1516321318423-f06f85e504b3?q=80&w=1200&auto=format&fit=crop'
},
{
title:'Construir Estabilidad',
level:'PROGRESO PERSONAL',
text:'Quieres consolidar una vida equilibrada y significativa.',
points:3,
image:'https://images.unsplash.com/photo-1504384308090-c894fdcc538d?q=80&w=1200&auto=format&fit=crop'
}
]
}
];

let currentQuestion = 0;
let score = 0;
let timer = 60;
let interval;

const questionText = document.getElementById('questionText');
const cardsGrid = document.getElementById('cardsGrid');
const resultBox = document.getElementById('resultBox');
const resultTitle = document.getElementById('resultTitle');
const resultText = document.getElementById('resultText');
const timerElement = document.getElementById('timer');
const progressFill = document.getElementById('progressFill');
const questionNumber = document.getElementById('questionNumber');

function loadQuestion(){
clearInterval(interval);

timer = 60;
timerElement.innerText = timer;

interval = setInterval(()=>{
timer--;
timerElement.innerText = timer;

if(timer <= 0){
clearInterval(interval);
nextQuestion();
}
},1000);

const q = questions[currentQuestion];
questionText.innerText = q.question;
questionNumber.innerText = `PREGUNTA ${currentQuestion+1} DE ${questions.length}`;

progressFill.style.width = `${(currentQuestion/questions.length)*100}%`;

cardsGrid.innerHTML = '';
resultBox.classList.remove('active');

q.options.forEach(option=>{
const card = document.createElement('div');
card.className = 'choice-card';

card.innerHTML = `
<div class="choice-image" style="background-image:url('${option.image}')">
<div class="choice-level">${option.level}</div>
</div>

<div class="choice-content">
<div class="choice-title">${option.title}</div>
<div class="choice-text">${option.text}</div>
<div class="choice-points">Explora esta dirección de tu brújula interior</div>
</div>
`;

card.onclick = ()=>selectOption(option);
cardsGrid.appendChild(card);
});
}

function selectOption(option){
clearInterval(interval);
score += option.points;

resultBox.classList.add('active');
resultTitle.innerText = option.title;
resultText.innerText = `Tu elección refleja una orientación hacia ${option.level.toLowerCase()} y una forma particular de proyectar tu brújula interior.`;

progressFill.style.width = `${((currentQuestion+1)/questions.length)*100}%`;
}

function nextQuestion(){
currentQuestion++;

if(currentQuestion >= questions.length){
showFinal();
return;
}

loadQuestion();
}

function showProjection(){

resultBox.classList.add('active');

let projection = '';

if(score >= 23){
projection = 'Tu brújula interior refleja una proyección expansiva, consciente y orientada al liderazgo humano positivo.';
}else if(score >= 18){
projection = 'Tu brújula interior muestra crecimiento constante, apertura y capacidad de evolución personal.';
}else{
projection = 'Tu brújula interior se orienta hacia estabilidad, equilibrio y fortalecimiento progresivo.';
}

resultTitle.innerText = 'Tu proyección interior';
resultText.innerText = projection;

}

function showFinal(){
cardsGrid.innerHTML = '';
resultBox.classList.add('active');
questionText.innerText = 'Exploración completada';
questionNumber.innerText = 'RESULTADO FINAL';

let profile = '';

if(score >= 8){
profile = 'Tu brújula interior refleja visión expansiva, consciencia y liderazgo humano.';
}else{
profile = 'Tu brújula interior busca equilibrio, estabilidad y crecimiento gradual.';
}

resultTitle.innerText = 'Perfil de tu brújula interior';
resultText.innerText = profile;
progressFill.style.width = '100%';
}

loadQuestion();

</script>

</body>
</html>
