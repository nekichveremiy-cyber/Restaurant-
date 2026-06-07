<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Grill Bar Dacha | Luxury Menu</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">

<style>
body{
margin:0;
font-family:Inter;
background:#0a0a0a;
color:white;
}

/* HEADER */
header{
position:fixed;
top:0;
width:100%;
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 40px;
background:rgba(0,0,0,0.6);
backdrop-filter:blur(12px);
z-index:10;
}

.logo{
font-weight:700;
color:#d4af37;
letter-spacing:1px;
}

/* HERO */
.hero{
height:70vh;
background:url('https://images.unsplash.com/photo-1414235077428-338989a2e8c0') center/cover;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
position:relative;
}

.hero::after{
content:'';
position:absolute;
inset:0;
background:rgba(0,0,0,0.6);
}

.hero h1{
font-family:'Playfair Display';
font-size:60px;
position:relative;
}

/* SECTION */
.section{
padding:80px 40px;
max-width:1200px;
margin:auto;
}

h2{
font-family:'Playfair Display';
color:#d4af37;
font-size:32px;
margin-bottom:20px;
}

/* GRID */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:20px;
}

/* CARD */
.card{
background:rgba(255,255,255,0.05);
border:1px solid rgba(255,255,255,0.1);
border-radius:16px;
overflow:hidden;
transition:0.3s;
}

.card:hover{
transform:translateY(-6px);
}

.card img{
width:100%;
height:180px;
object-fit:cover;
}

.content{
padding:15px;
}

.price{
color:#d4af37;
font-weight:600;
margin-top:5px;
}

/* CATEGORY TITLE */
.cat{
margin-top:60px;
}

footer{
text-align:center;
padding:40px;
opacity:0.5;
border-top:1px solid #222;
}
</style>
</head>

<body>

<header>
<div class="logo">Grill Bar Dacha</div>
</header>

<div class="hero">
<h1>Luxury Restaurant Experience</h1>
</div>

<!-- START MENU -->

<div class="section">

<h2>🥗 Холодні закуски</h2>
<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1604908177522-0407c2f5a7d6">
<div class="content">
Рибний сет
<div class="price">620 грн</div>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1606755962773-d324e0a13086">
<div class="content">
Овочеве плато
<div class="price">130 грн</div>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1603079843962-8f6a8c7a1d12">
<div class="content">
Тарілка до вина
<div class="price">320 грн</div>
</div>
</div>

</div>

<!-- SALADS -->
<h2 class="cat">🥗 Салати</h2>
<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1540189549336-e6e99c3679fe">
<div class="content">
Цезар з куркою
<div class="price">210 грн</div>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1565958011703-44f9829ba187">
<div class="content">
Грецький салат
<div class="price">150 грн</div>
</div>
</div>

</div>

<!-- SOUPS -->
<h2 class="cat">🍲 Перші страви</h2>
<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1604908176997-125f25cc500f">
<div class="content">
Борщ червоний
<div class="price">140 грн</div>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1547592180-85f173990554">
<div class="content">
Сирний крем-суп
<div class="price">180 грн</div>
</div>
</div>

</div>

<!-- MAIN -->
<h2 class="cat">🔥 Основні страви</h2>
<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092">
<div class="content">
Котлета по-київськи
<div class="price">240 грн</div>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1">
<div class="content">
Лосось з броколі
<div class="price">490 грн</div>
</div>
</div>

</div>

<!-- PIZZA -->
<h2 class="cat">🍕 Піца</h2>
<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1548365328-9f547f6f9a6f">
<div class="content">
Піца М’ясна
<div class="price">250 грн</div>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1513104890138-7c749659a591">
<div class="content">
Піца Папероні
<div class="price">220 грн</div>
</div>
</div>

</div>

</div>

<footer>
© 2026 Grill Bar Dacha — Luxury Restaurant Experience
</footer>

</body>
</html>
