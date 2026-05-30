<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>WR Importados</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, sans-serif;
}

body{
background:#f5f5f5;
}

header{
background:#005eff;
padding:15px;
display:flex;
align-items:center;
justify-content:space-between;
color:white;
flex-wrap:wrap;
}

.logo{
font-size:28px;
font-weight:bold;
}

.search{
width:40%;
padding:10px;
border:none;
border-radius:8px;
}

.menu a{
color:white;
text-decoration:none;
margin:10px;
font-weight:bold;
}

.banner{
height:300px;
background:linear-gradient(90deg,#005eff,#00a2ff);
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
color:white;
text-align:center;
}

.banner h1{
font-size:45px;
}

.banner p{
font-size:20px;
margin-top:10px;
}

.produtos{
padding:30px;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:white;
border-radius:15px;
padding:15px;
text-align:center;
box-shadow:0 3px 10px rgba(0,0,0,.15);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
border-radius:10px;
}

.preco{
color:#00aa00;
font-size:24px;
font-weight:bold;
margin:10px 0;
}

.btn{
background:#00aa00;
color:white;
border:none;
padding:12px;
width:100%;
border-radius:8px;
cursor:pointer;
font-size:16px;
}

.pix{
background:white;
margin:30px;
padding:20px;
border-radius:15px;
text-align:center;
}

.pix img{
width:250px;
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25d366;
color:white;
padding:15px 20px;
border-radius:50px;
text-decoration:none;
font-weight:bold;
}

footer{
background:#111;
color:white;
text-align:center;
padding:20px;
margin-top:30px;
}
</style>
</head>

<body>

<header>
<div class="logo">WR IMPORTADOS</div>

<input class="search" placeholder="Busque celulares, notebooks e acessórios">

<div class="menu">
<a href="#">Início</a>
<a href="#">Celulares</a>
<a href="#">Notebooks</a>
<a href="#">Minha Conta</a>
<a href="#">🛒 Carrinho</a>
</div>
</header>

<section class="banner">
<h1>MEGA OFERTAS</h1>
<p>Celulares, notebooks e acessórios com desconto no Pix</p>
</section>

<section class="produtos">

<div class="card">
<img src="https://images.unsplash.com/photo-1592750475338-74b7b21085ab">
<h3>iPhone 15</h3>
<div class="preco">R$ 4.799</div>
<button class="btn">Comprar</button>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1610945265064-0e34e5519bbf">
<h3>Samsung S24</h3>
<div class="preco">R$ 3.299</div>
<button class="btn">Comprar</button>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1588872657578-7efd1f1555ed">
<h3>Motorola Edge</h3>
<div class="preco">R$ 2.199</div>
<button class="btn">Comprar</button>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1496181133206-80ce9b88a853">
<h3>Notebook Dell i5</h3>
<div class="preco">R$ 2.899</div>
<button class="btn">Comprar</button>
</div>

</section>

<section class="pix">
<h2>Pague com Pix</h2>
<p>Coloque aqui o arquivo do seu QR Code:</p>

<img <section class="pix">
    <h2>Pague com Pix</h2>

    <img src="pdfpage.png" alt="QR Code Pix" width="300">

    <p>Após o pagamento envie o comprovante pelo[infinite_pay_pix_qr_code (1).pdf](https://github.com/user-attachments/files/28422857/infinite_pay_pix_qr_code.1.pdf)
 WhatsApp.</p>
</section>>

<p>Após o pagamento envie o comprovante.</p>
</section>

<a class="whatsapp" href="https://wa.me/5511913028832">
WhatsApp
</a>

<footer>
© 2026 WR IMPORTADOS - Todos os direitos reservados
</footer>

</body>
</html>
