<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>CTRL + ALT + DUDA</title>

<script src="https://cdn.tailwindcss.com"></script>

<style>

html{
scroll-behavior:smooth;
}

body{
background:#0f172a;
color:white;
font-family:Arial, sans-serif;
}

.hero{
background:linear-gradient(135deg,#1e293b,#0f172a);
}

.card{
transition:0.3s;
}

.card:hover{
transform:translateY(-8px);
}

.section-title{
font-size:40px;
font-weight:bold;
margin-bottom:20px;
text-align:center;
}

.phase-title{
font-size:32px;
font-weight:bold;
margin-bottom:15px;
}

.btn{
background:#2563eb;
padding:12px 25px;
border-radius:15px;
display:inline-block;
margin-top:20px;
transition:0.3s;
}

.btn:hover{
background:#1d4ed8;
}

</style>

</head>

<body>

<!-- NAVBAR -->

<nav class="bg-black p-5 sticky top-0 z-50 shadow-xl">

<div class="max-w-7xl mx-auto flex justify-between items-center">

<h1 class="text-2xl font-bold">
CTRL + ALT + DUDA
</h1>

<div class="space-x-5 hidden md:block">

<a href="#inicio" class="hover:text-blue-400">Inicio</a>

<a href="#fase1" class="hover:text-blue-400">Fase 1</a>

<a href="#fase2" class="hover:text-blue-400">Fase 2</a>

<a href="#fase3" class="hover:text-blue-400">Fase 3</a>

</div>

</div>

</nav>

<!-- HERO -->

<section id="inicio" class="hero py-24 px-6 text-center">

<h1 class="text-6xl font-bold mb-6">
CTRL + ALT + DUDA
</h1>

<h2 class="text-3xl mb-6 text-blue-300">
Laboratorio de Verificación Digital
</h2>

<p class="max-w-4xl mx-auto text-xl text-slate-300 leading-relaxed">

Bienvenidos al Laboratorio de Verificación Digital. 
En este proyecto aprenderán a identificar noticias falsas, 
analizar información de internet, verificar fuentes y comprender 
cómo funciona la inteligencia artificial en los entornos digitales.

A través de retos, herramientas tecnológicas y trabajo colaborativo, 
ustedes se convertirán en investigadores digitales capaces de crear 
contenido crítico, ético y responsable.

</p>

<a href="#fase1" class="btn">
Comenzar misión
</a>

</section>

<!-- FASE 1 -->

<section id="fase1" class="py-20 px-6 bg-slate-900">

<h2 class="section-title">
🔍 FASE 1 — EXPLORACIÓN Y DIAGNÓSTICO
</h2>

<div class="max-w-6xl mx-auto">

<div class="bg-slate-800 p-10 rounded-3xl shadow-2xl">

<h3 class="phase-title">
¿Qué vamos a hacer?
</h3>

<p class="text-lg text-slate-300 leading-relaxed">

En esta primera fase exploraremos cómo consumimos información en internet 
y cómo influyen las redes sociales, las noticias virales y la inteligencia artificial 
en nuestra manera de pensar.

También conoceremos las dinámicas del proyecto y conformaremos los equipos de trabajo.

</p>

<h3 class="text-2xl font-bold mt-10 mb-5">
🎯 Actividades
</h3>

<div class="grid md:grid-cols-2 gap-6">

<div class="card bg-slate-700 p-6 rounded-2xl">

<h4 class="text-xl font-bold mb-3">
🧠 Diagnóstico digital
</h4>

<p>
Responderemos un formulario interactivo sobre hábitos digitales,
fake news y uso de inteligencia artificial.
</p>

</div>

<div class="card bg-slate-700 p-6 rounded-2xl">

<h4 class="text-xl font-bold mb-3">
📱 Analizando redes sociales
</h4>

<p>
Observaremos publicaciones virales, noticias y cadenas de WhatsApp
para identificar posibles señales de desinformación.
</p>

</div>

<div class="card bg-slate-700 p-6 rounded-2xl">

<h4 class="text-xl font-bold mb-3">
🎮 Interland
</h4>

<p>
Jugaremos y exploraremos herramientas gamificadas sobre ciudadanía digital.
</p>

<a href="https://beinternetawesome.withgoogle.com/interland"
target="_blank"
class="btn">
Ir a Interland
</a>

</div>

<div class="card bg-slate-700 p-6 rounded-2xl">

<h4 class="text-xl font-bold mb-3">
👥 Formación de equipos
</h4>

<p>
Cada grupo asumirá roles específicos:
verificadores, analistas IA, diseñadores y comunicadores.
</p>

</div>

</div>

<h3 class="text-2xl font-bold mt-12 mb-5">
🛠 Herramientas
</h3>

<div class="flex flex-wrap gap-4">

<span class="bg-blue-700 px-5 py-3 rounded-xl">
Google Forms
</span>

<span class="bg-blue-700 px-5 py-3 rounded-xl">
Interland
</span>

<span class="bg-blue-700 px-5 py-3 rounded-xl">
Padlet
</span>

<span class="bg-blue-700 px-5 py-3 rounded-xl">
Teams
</span>

</div>

</div>

</div>

</section>

<!-- FASE 2 -->

<section id="fase2" class="py-20 px-6">

<h2 class="section-title">
🧠 FASE 2 — LABORATORIO DE VERIFICACIÓN
</h2>

<div class="max-w-6xl mx-auto">

<div class="bg-slate-800 p-10 rounded-3xl shadow-2xl">

<h3 class="phase-title">
¿Qué vamos a hacer?
</h3>

<p class="text-lg text-slate-300 leading-relaxed">

En esta fase nos convertiremos en investigadores digitales.
Analizaremos información, verificaremos fuentes y compararemos contenidos
generados por inteligencia artificial para descubrir qué tan confiables son.

</p>

<h3 class="text-2xl font-bold mt-10 mb-5">
🎯 Actividades
</h3>

<div class="grid md:grid-cols-2 gap-6">

<div class="card bg-slate-700 p-6 rounded-2xl">

<h4 class="text-xl font-bold mb-3">
🔎 Verificación de fuentes
</h4>

<p>
Buscaremos información académica y contrastaremos noticias utilizando
herramientas de fact-checking.
</p>

<div class="mt-4 flex flex-wrap gap-3">

<a href="https://dialnet.unirioja.es/"
target="_blank"
class="btn">
Dialnet
</a>

<a href="https://maldita.es/"
target="_blank"
class="btn">
Maldita
</a>

</div>

</div>

<div class="card bg-slate-700 p-6 rounded-2xl">

<h4 class="text-xl font-bold mb-3">
🤖 Análisis de IA
</h4>

<p>
Compararemos respuestas generadas por herramientas de inteligencia artificial
para identificar errores, sesgos y alucinaciones.
</p>

</div>

<div class="card bg-slate-700 p-6 rounded-2xl">

<h4 class="text-xl font-bold mb-3">
📚 Contraste académico
</h4>

<p>
Analizaremos si la información encontrada coincide con artículos académicos
y fuentes confiables.
</p>

</div>

<div class="card bg-slate-700 p-6 rounded-2xl">

<h4 class="text-xl font-bold mb-3">
📝 Registro de evidencias
</h4>

<p>
Cada equipo construirá un repositorio de evidencias y conclusiones
sobre la información analizada.
</p>

</div>

</div>

<h3 class="text-2xl font-bold mt-12 mb-5">
🛠 Herramientas
</h3>

<div class="flex flex-wrap gap-4">

<span class="bg-purple-700 px-5 py-3 rounded-xl">
Dialnet
</span>

<span class="bg-purple-700 px-5 py-3 rounded-xl">
Scopus
</span>

<span class="bg-purple-700 px-5 py-3 rounded-xl">
AFP Factual
</span>

<span class="bg-purple-700 px-5 py-3 rounded-xl">
ChatGPT
</span>

<span class="bg-purple-700 px-5 py-3 rounded-xl">
Gemini
</span>

<span class="bg-purple-700 px-5 py-3 rounded-xl">
Perplexity
</span>

</div>

</div>

</div>

</section>

<!-- FASE 3 -->

<section id="fase3" class="py-20 px-6 bg-slate-900">

<h2 class="section-title">
🎥 FASE 3 — PRODUCCIÓN Y SOCIALIZACIÓN
</h2>

<div class="max-w-6xl mx-auto">

<div class="bg-slate-800 p-10 rounded-3xl shadow-2xl">

<h3 class="phase-title">
¿Qué vamos a hacer?
</h3>

<p class="text-lg text-slate-300 leading-relaxed">

En esta fase construiremos productos digitales donde compartiremos
los hallazgos del proyecto y promoveremos el pensamiento crítico
y la ciudadanía digital responsable.

</p>

<h3 class="text-2xl font-bold mt-10 mb-5">
🎯 Actividades
</h3>

<div class="grid md:grid-cols-2 gap-6">

<div class="card bg-slate-700 p-6 rounded-2xl">

<h4 class="text-xl font-bold mb-3">
🎨 Diseño de campañas
</h4>

<p>
Crearemos campañas digitales, infografías y piezas gráficas
sobre desinformación y ciudadanía digital.
</p>

</div>

<div class="card bg-slate-700 p-6 rounded-2xl">

<h4 class="text-xl font-bold mb-3">
🎙 Producción multimedia
</h4>

<p>
Diseñaremos podcasts, videos y publicaciones digitales.
</p>

</div>

<div class="card bg-slate-700 p-6 rounded-2xl">

<h4 class="text-xl font-bold mb-3">
🗣 Socialización
</h4>

<p>
Cada equipo presentará sus resultados y argumentará
las decisiones tomadas durante el proceso.
</p>

</div>

<div class="card bg-slate-700 p-6 rounded-2xl">

<h4 class="text-xl font-bold mb-3">
📊 Evaluación y reflexión
</h4>

<p>
Realizaremos procesos de autoevaluación, coevaluación y reflexión crítica.
</p>

</div>

</div>

<h3 class="text-2xl font-bold mt-12 mb-5">
🛠 Herramientas
</h3>

<div class="flex flex-wrap gap-4">

<span class="bg-red-700 px-5 py-3 rounded-xl">
Canva Educación
</span>

<span class="bg-red-700 px-5 py-3 rounded-xl">
Teams
</span>

<span class="bg-red-700 px-5 py-3 rounded-xl">
Google Classroom
</span>

<span class="bg-red-700 px-5 py-3 rounded-xl">
OneNote
</span>

</div>

</div>

</div>

</section>

<!-- GALERÍA -->

<section class="py-20 px-6">

<h2 class="section-title">
🏆 GALERÍA DE PROYECTOS
</h2>

<div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">

<div class="card bg-slate-800 p-8 rounded-3xl">

<h3 class="text-2xl font-bold mb-4">
📱 Infografía
</h3>

<p>
Campaña sobre fake news en redes sociales.
</p>

</div>

<div class="card bg-slate-800 p-8 rounded-3xl">

<h3 class="text-2xl font-bold mb-4">
🎙 Podcast
</h3>

<p>
Reflexión crítica sobre inteligencia artificial.
</p>

</div>

<div class="card bg-slate-800 p-8 rounded-3xl">

<h3 class="text-2xl font-bold mb-4">
🎥 Video educativo
</h3>

<p>
Ciudadanía digital y verificación de información.
</p>

</div>

</div>

</section>

<!-- FOOTER -->

<footer class="bg-black text-center py-10 text-slate-400">

<h3 class="text-2xl font-bold mb-4">
CTRL + ALT + DUDA
</h3>

<p>
Proyecto de Innovación Educativa Mediada por TIC
</p>

<p class="mt-2">
Laboratorio de Verificación Digital © 2026
</p>

</footer>

</body>
</html>
