<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Grill Bar Dacha | Luxury Restaurant</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">

<style>
body{
margin:0;
font-family:Inter;
background:#0b0b0b;
color:white;
overflow-x:hidden;
}

/* HERO */
.hero{
height:90vh;
background:url('https://images.unsplash.com/photo-1555396273-367ea4eb4db5') center/cover;
display:flex;
align-items:center;
justify-content:center;
position:relative;
}

.hero::after{
content:'';
position:absolute;
inset:0;
background:rgba(0,0,0,0.6);
}

.hero-content{
position:relative;
text-align:center;
z-index:2;
}

.hero h1{
font-family:'Playfair Display';
font-size:64px;
margin:0;
}

.hero p{
opacity:0.8;
font-size:18px;
}

/* NAV */
nav{
position:fixed;
top:0;
width:100%;
display:flex;
justify-content:space-between;
padding:20px 40px;
backdrop-filter:blur(10px);
background:rgba(0,0,0,0.4);
z-index:10;
}

.logo{
font-weight:700;
letter-spacing:1px;
}

.nav-links a{
color:white;
text-decoration:none;
margin-left:20px;
opacity:0.8;
}

/* SECTION */
.section{
padding:80px 40px;
max-width:1200px;
margin:auto;
}

.section h2{
font-family:'Playfair Display';
font-size:36px;
margin-bottom:20px;
}

/* MENU GRID */
.menu{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:20px;
}

.card{
background:rgba(255,255,255,0.05);
border:1px solid rgba(255,255,255,0.1);
border-radius:20px;
overflow:hidden;
transition:0.3s;
}

.card:hover{
transform:translateY(-5px);
}

.card img{
width:100%;
height:180px;
object-fit:cover;
}

.card-content{
padding:15px;
}

.price{
color:#d4af37;
font-weight:600;
}

/* ABOUT */
.about{
display:flex;
gap:40px;
align-items:center;
flex-wrap:wrap;
}

.about img{
width:100%;
max-width:500px;
border-radius:20px;
}

/* FOOTER */
footer{
text-align:center;
padding:40px;
opacity:0.5;
border-top:1px solid #222;
}

@media(max-width:768px){
.hero h1{font-size:38px;}
nav{padding:15px;}
}
</style>
</head>

<body>

<nav>
<div class="logo">Grill Bar Dacha</div>
<div class="nav-links">
<a href="#menu">Меню</a>
<a href="#about">Про нас</a>
<a href="#contact">Контакти</a>
</div>
</nav>

<div class="hero">
<div class="hero-content">
<h1>Luxury Grill Experience</h1>
<p>Смак, який виглядає як мистецтво</p>
</div>
</div>

<!-- MENU -->
<div class="section" id="menu">
<h2>Меню</h2>

<div class="menu">

<div class="card">
<img src="https://images.unsplash.com/photo-1601924582970-9238bcb495d9">
<div class="card-content">
<h3>Піца Маргарита</h3>
<p class="price">120 грн</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1606755962773-d324e0a13086">
<div class="card-content">
<h3>Піца М’ясна</h3>
<p class="price">160 грн</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1529692236671-f1f6cf9683ba">
<div class="card-content">
<h3>Шашлик на вогні</h3>
<p class="price">180 грн</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1550547660-d9450f859349">
<div class="card-content">
<h3>Преміум бургер</h3>
<p class="price">150 грн</p>
</div>
</div>

</div>
</div>

<!-- ABOUT -->
<div class="section" id="about">
<h2>Про нас</h2>

<div class="about">
<img src="https://images.unsplash.com/photo-1414235077428-338989a2e8c0">
<div>
<p>
Grill Bar Dacha — це ресторан преміум рівня з атмосферою тепла, вогню та справжнього смаку.
Ми створюємо не просто їжу — ми створюємо досвід.
</p>
</div>
</div>
</div>

<!-- CONTACT -->
<div class="section" id="contact">
<h2>Контакти</h2>
<p>📍 Славута, вул. Лісна 30В</p>
<p>📞 068 410 13 17</p>
<p>📸 Instagram: @grill_bar_dacha_</p>
</div>

<footer>
© 2026 Grill Bar Dacha — Luxury Restaurant Experience
</footer>

</body>
</html>
