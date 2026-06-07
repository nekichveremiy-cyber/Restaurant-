<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Grill Bar Dacha | Premium Delivery</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">

<style>
body{
margin:0;
font-family:Inter;
background: radial-gradient(circle at top, #1b1b1b, #0a0a0a);
color:white;
overflow-x:hidden;
}

/* TOP */
header{
padding:20px 40px;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo{
font-weight:800;
letter-spacing:1px;
color:#ff3b3b;
}

.btn-top{
background:rgba(255,255,255,0.08);
padding:10px 15px;
border-radius:12px;
backdrop-filter:blur(10px);
cursor:pointer;
}

/* HERO */
.hero{
text-align:center;
padding:80px 20px;
}

.hero h1{
font-size:50px;
margin:0;
}

.hero p{
opacity:0.7;
}

/* LAYOUT */
.container{
display:flex;
gap:20px;
padding:20px 40px;
}

/* MENU */
.menu{
flex:3;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.card{
background:rgba(255,255,255,0.06);
border:1px solid rgba(255,255,255,0.1);
backdrop-filter:blur(12px);
border-radius:18px;
padding:15px;
transition:0.3s;
transform:translateY(20px);
opacity:0;
animation:fadeUp 0.6s forwards;
}

.card:hover{
transform:scale(1.03);
}

@keyframes fadeUp{
to{opacity:1;transform:translateY(0);}
}

.price{
color:#ff3b3b;
font-weight:600;
margin:10px 0;
}

button{
width:100%;
padding:10px;
border:none;
border-radius:12px;
background:linear-gradient(135deg,#ff3b3b,#ff7a18);
color:white;
cursor:pointer;
}

/* CART */
.cart{
flex:1;
background:rgba(255,255,255,0.05);
backdrop-filter:blur(12px);
border-radius:18px;
padding:20px;
position:sticky;
top:20px;
height:fit-content;
}

.item{
display:flex;
justify-content:space-between;
margin:10px 0;
font-size:14px;
opacity:0.9;
}

.total{
margin-top:20px;
font-size:18px;
font-weight:600;
}

.checkout{
margin-top:15px;
width:100%;
padding:12px;
background:linear-gradient(135deg,#00c853,#00e676);
border:none;
border-radius:12px;
cursor:pointer;
}

/* FOOTER */
footer{
text-align:center;
padding:40px;
opacity:0.5;
}

/* MOBILE */
@media(max-width:900px){
.container{flex-direction:column;}
.hero h1{font-size:32px;}
}
</style>
</head>

<body>

<header>
<div class="logo">🔥 Grill Bar Dacha</div>
<div class="btn-top">Premium Delivery</div>
</header>

<div class="hero">
<h1>Ресторанна доставка нового рівня</h1>
<p>Смак. Атмосфера. Швидкість. Як у топових сервісах доставки.</p>
</div>

<div class="container">

<!-- MENU -->
<div class="menu">

<div class="card">
<h3>Піца Трюфель</h3>
<div class="price">189 грн</div>
<button onclick="add('Піца Трюфель',189)">Додати в кошик</button>
</div>

<div class="card">
<h3>Піца BBQ Meat</h3>
<div class="price">179 грн</div>
<button onclick="add('BBQ Meat',179)">Додати в кошик</button>
</div>

<div class="card">
<h3>Шашлик Преміум</h3>
<div class="price">220 грн</div>
<button onclick="add('Шашлик Преміум',220)">Додати в кошик</button>
</div>

<div class="card">
<h3>Бургер Dacha Gold</h3>
<div class="price">165 грн</div>
<button onclick="add('Бургер Gold',165)">Додати в кошик</button>
</div>

<div class="card">
<h3>Картопля з пармезаном</h3>
<div class="price">95 грн</div>
<button onclick="add('Фрі Пармезан',95)">Додати в кошик</button>
</div>

</div>

<!-- CART -->
<div class="cart">
<h3>🛒 Ваш кошик</h3>
<div id="cart"></div>

<div class="total">
Разом: <span id="total">0</span> грн
</div>

<button class="checkout" onclick="order()">
Оформити замовлення
</button>
</div>

</div>

<footer>
© 2026 Grill Bar Dacha — Premium Restaurant Delivery
</footer>

<script>
let cart = [];

function add(name, price){
cart.push({name, price});
render();
}

function render(){
let box = document.getElementById("cart");
let total = 0;
box.innerHTML = "";

cart.forEach(i=>{
total += i.price;
box.innerHTML += `<div class="item"><span>${i.name}</span><span>${i.price} грн</span></div>`;
});

document.getElementById("total").innerText = total;
}

function order(){
if(cart.length === 0){
alert("Кошик порожній");
return;
}

alert("🔥 Замовлення прийнято! Ми скоро зв’яжемось з вами.");
cart = [];
render();
}
</script>

</body>
</html>
