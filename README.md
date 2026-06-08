<!DOCTYPE html>
<html lang="fr">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Poules Pondeuses</title>

<meta name="description"
content="Site d'information sur les poules pondeuses : races, alimentation et conseils d'élevage.">

<link rel="icon" href="favicon.png">

<link rel="stylesheet" href="style.css">

</head>

<body>

<header>

<div class="logo-area">

<img src="favicon.png" class="logo">

<div>

<h1>POULES PONDEUSES</h1>

<p>Tout savoir sur les poules pondeuses</p>

</div>

</div>

<nav>

<a href="#">Accueil</a>
<a href="#apropos">À propos</a>
<a href="#races">Races</a>
<a href="#elevage">Élevage</a>
<a href="#alimentation">Alimentation</a>
<a href="#contact">Contact</a>

</nav>

</header>

<section class="hero">

<div class="hero-box">

<h2>POULES PONDEUSES</h2>

<p>

Le guide complet pour découvrir les races,
leur alimentation et les bonnes pratiques
d'élevage.

</p>

<div>

<a href="#conseils" class="button1">

Découvrir nos conseils

</a>

<a href="#races" class="button2">

Voir les races

</a>

</div>

</div>

</section>

<section class="services">

<div class="service">

<div class="emoji">🐔</div>

<h3>Les races</h3>

<p>

Découvrez plusieurs races populaires.

</p>

</div>

<div class="service">

<div class="emoji">🏡</div>

<h3>Élevage facile</h3>

<p>

Des conseils simples pour bien débuter.

</p>

</div>

<div class="service">

<div class="emoji">🌾</div>

<h3>Alimentation</h3>

<p>

Une nourriture adaptée pour des poules en bonne santé.

</p>

</div>

<div class="service">

<div class="emoji">❤</div>

<h3>Bien-être animal</h3>

<p>

Le respect et le confort des animaux avant tout.

</p>

</div>

</section>

<section id="races">

<h2>NOS RACES POPULAIRES</h2>

<div class="cards">

<div class="card">

<img src="hero.jpg">

<h3>La Rousse</h3>

<p>

Une excellente pondeuse.

</p>

</div>

<div class="card">

<img src="hero.jpg">

<h3>La Sussex</h3>

<p>

Calme et sociable.

</p>

</div>

<div class="card">

<img src="hero.jpg">

<h3>La Marans</h3>

<p>

Connue pour ses œufs foncés.

</p>

</div>

<div class="card">

<img src="hero.jpg">

<h3>La Coucou</h3>

<p>

Rustique et active.

</p>

</div>

</div>

</section>

<section id="conseils">

<h2>QUELQUES CONSEILS</h2>

<ul>

<li>✔ Nettoyer régulièrement le poulailler.</li>

<li>✔ Laisser toujours de l'eau fraîche.</li>

<li>✔ Fournir une alimentation équilibrée.</li>

<li>✔ Prévoir un espace extérieur sécurisé.</li>

<li>✔ Observer régulièrement leur état de santé.</li>

</ul>

</section>

<footer id="contact">

<h3>Poules Pondeuses</h3>

<p>

Site d'information consacré aux poules pondeuses.

</p>

<p>

© 2026

</p>

</footer>

</body>
</html>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f8f6f2;
color:#333;
}

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 50px;
background:white;
box-shadow:0 2px 10px rgba(0,0,0,0.1);
flex-wrap:wrap;
}

.logo-area{
display:flex;
align-items:center;
gap:15px;
}

.logo{
width:80px;
height:80px;
border-radius:50%;
object-fit:cover;
}

.logo-area h1{
color:#6d3200;
font-size:38px;
}

.logo-area p{
font-size:18px;
}

nav a{
text-decoration:none;
margin:15px;
font-weight:bold;
color:#6d3200;
}

.hero{
height:550px;
background:url(hero.jpg);
background-size:cover;
background-position:center;
display:flex;
align-items:center;
justify-content:flex-end;
}

.hero-box{
margin-right:80px;
padding:40px;
background:rgba(0,0,0,0.25);
border-radius:15px;
color:white;
max-width:700px;
}

.hero-box h2{
font-size:80px;
margin-bottom:20px;
}

.hero-box p{
font-size:28px;
margin-bottom:30px;
}

.button1{
background:#d96f07;
padding:15px 25px;
text-decoration:none;
color:white;
border-radius:8px;
margin-right:15px;
}

.button2{
padding:15px 25px;
text-decoration:none;
color:white;
border:2px solid white;
border-radius:8px;
}

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:30px;
padding:60px;
background:#f0ebe3;
}

.service{
text-align:center;
}

.emoji{
font-size:55px;
margin-bottom:15px;
}

.service h3{
font-size:30px;
margin-bottom:10px;
color:#6d3200;
}

#races{
padding:70px;
text-align:center;
}

#races h2{
font-size:50px;
color:#6d3200;
margin-bottom:40px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
border-radius:15px;
overflow:hidden;
box-shadow:0 3px 10px rgba(0,0,0,0.15);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card h3{
margin:15px;
color:#6d3200;
}

.card p{
padding-bottom:20px;
}

#conseils{
padding:70px;
max-width:900px;
margin:auto;
}

#conseils h2{
text-align:center;
font-size:45px;
margin-bottom:30px;
color:#6d3200;
}

#conseils li{
font-size:24px;
margin:15px 0;
}

footer{
background:#2d2d2d;
color:white;
text-align:center;
padding:35px;
margin-top:50px;
}

@media(max-width:900px){

header{
justify-content:center;
}

nav{
margin-top:20px;
}

.hero{
justify-content:center;
}

.hero-box{
margin:20px;
}

.hero-box h2{
font-size:45px;
}

.hero-box p{
font-size:20px;
}

.logo-area h1{
font-size:28px;
}

}
favicon.png<img width="1536" height="1536" alt="image" src="https://github.com/user-attachments/assets/7e6b3690-328c-4f5d-9e69-75b36ed256b9" />

hero.jpg<img width="1536" height="1536" alt="image" src="https://github.com/user-attachments/assets/fce83176-95f2-46f3-8ce8-ed13969c880e" />


