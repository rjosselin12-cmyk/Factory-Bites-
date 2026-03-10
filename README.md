<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Factory Bites</title>

<style>

body{
font-family: Arial;
margin:0;
background:black;
color:white;
text-align:center;
}

header{
background:red;
padding:25px;
}

h1{
margin:0;
font-size:40px;
}

.sub{
font-size:18px;
}

.menu{
padding:20px;
}

.card{
background:#111;
border:2px solid red;
border-radius:12px;
padding:20px;
margin:20px;
}

img{
width:280px;
border-radius:12px;
margin:10px;
}

.precio{
background:yellow;
color:black;
padding:6px 12px;
border-radius:8px;
font-weight:bold;
}

button{
background:red;
color:white;
border:none;
padding:15px 25px;
margin:10px;
font-size:16px;
border-radius:8px;
cursor:pointer;
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
padding:16px 22px;
border-radius:50px;
font-weight:bold;
text-decoration:none;
}

</style>
</head>

<body>

<header>

<h1>🔥 Factory Bites</h1>
<p class="sub">Boneless • Papas • Banderillas</p>
<p>El sabor que se te antoja 🍟</p>

</header>

<div>

<img src="boneless.jpg">
<img src="papas.jpg">
<img src="banderillas.jpg">

</div>

<div class="menu">

<div class="card">

<h2>🔥 Combo</h2>

<p>
Boneless 150 g + Papas chicas con acompañamiento +
1 dip a elegir + Soda
<span class="precio">$170</span>
</p>

</div>

<div class="card">

<h2>Boneless</h2>

<p>150 g (Personal)</p>

<p>
🔥 250 g (Orden normal - Más vendido)
<span class="precio">$150</span>
</p>

<p>
400 g (Para compartir)
<span class="precio">$350</span>
</p>

<p><b>Salsas</b></p>

<p>Mango habanero</p>
<p>BBQ</p>
<p>Buffalo</p>
<p>Naturales</p>

</div>

<div class="card">

<h2>Papas</h2>

<p>150 g Orden normal <span class="precio">$65</span></p>

<p>250 g Orden grande <span class="precio">$120</span></p>

<p>Sazonadas o Naturales</p>

</div>

<div class="card">

<h2>Banderillas</h2>

<p>Salchicha de pavo o Queso <span class="precio">$60</span></p>

<p>Mixta <span class="precio">$75</span></p>

</div>

<div class="card">

<h2>Bebidas</h2>

<p>Soda 250ml <span class="precio">$20</span></p>

<p>Coca-Cola • Sprite • Fanta</p>

<p>Agua de jamaica <span class="precio">$35</span></p>

</div>

<div class="card">

<h2>Aderezos extra</h2>

<p>Mágico <span class="precio">$15</span></p>
<p>Chipotle <span class="precio">$15</span></p>
<p>Ranch <span class="precio">$15</span></p>

</div>

<button onclick="window.location.href='https://www.ubereats.com'">
Ordenar en Uber Eats
</button>

</div>

<a class="whatsapp" href="https://wa.me/5216631965319?text=Hola%20quisiera%20ordenar">
Ordenar por WhatsApp
</a>

</body>
</html>
