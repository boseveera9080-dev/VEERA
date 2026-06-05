<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>VV Enterprices - Fresh Agricultural Products</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#ffffff;
    color:#222;
}

header{
    background:linear-gradient(135deg,#1B5E20,#2E7D32);
    color:white;
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:32px;
    font-weight:bold;
    color:#D4AF37;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
}

.hero{
    background:linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),
    url('https://images.unsplash.com/photo-1500937386664-56d1dfef3854');
    background-size:cover;
    background-position:center;
    height:80vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
}

.hero h1{
    font-size:55px;
    margin-bottom:15px;
}

.hero p{
    font-size:22px;
    margin-bottom:25px;
}

.btn{
    background:#D4AF37;
    color:#000;
    padding:14px 30px;
    text-decoration:none;
    border-radius:30px;
    font-weight:bold;
}

section{
    padding:80px 10%;
}

.section-title{
    text-align:center;
    color:#1B5E20;
    margin-bottom:40px;
    font-size:38px;
}

.about{
    text-align:center;
    line-height:1.8;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:25px;
}

.card{
    background:white;
    border-radius:12px;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
    padding:25px;
    text-align:center;
}

.card h3{
    color:#1B5E20;
    margin-bottom:10px;
}

.stock-table{
    width:100%;
    border-collapse:collapse;
}

.stock-table th{
    background:#1B5E20;
    color:white;
    padding:15px;
}

.stock-table td{
    border:1px solid #ddd;
    padding:15px;
    text-align:center;
}

.contact{
    text-align:center;
}

footer{
    background:#1B5E20;
    color:white;
    text-align:center;
    padding:20px;
}

.whatsapp{
    position:fixed;
    right:20px;
    bottom:20px;
    background:#25D366;
    color:white;
    padding:15px 20px;
    border-radius:50px;
    text-decoration:none;
    font-weight:bold;
}
</style>
</head>

<body>

<header>
    <div class="logo">VV ENTERPRICES</div>

    <nav>
        <a href="#about">About</a>
        <a href="#products">Products</a>
        <a href="#stock">Stock</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <div>
        <h1>Fresh Agricultural Products</h1>
        <p>Direct From Farm To Customer</p>
        <a href="#products" class="btn">View Products</a>
    </div>
</section>

<section id="about">
    <h2 class="section-title">About Us</h2>

    <div class="about">
        <p>
            VV Enterprices supplies premium-quality agricultural products
            directly from trusted farmers. We provide fresh produce,
            competitive prices, and reliable delivery for customers and businesses.
        </p>
    </div>
</section>

<section id="products">
    <h2 class="section-title">Our Products</h2>

    <div class="products">

        <div class="card">
            <h3>🍌 Banana</h3>
            <p>Fresh farm bananas</p>
        </div>

        <div class="card">
            <h3>🥥 Coconut</h3>
            <p>Premium coconuts</p>
        </div>

        <div class="card">
            <h3>🍋 Lemon</h3>
            <p>Fresh lemons</p>
        </div>

        <div class="card">
            <h3>🍎 Fruits</h3>
            <p>Seasonal fresh fruits</p>
        </div>

        <div class="card">
            <h3>🍃 Banana Leaves</h3>
            <p>Natural fresh leaves</p>
        </div>

    </div>
</section>

<section id="stock">
    <h2 class="section-title">Stock Details</h2>

    <table class="stock-table">
        <tr>
            <th>Product</th>
            <th>Stock</th>
            <th>Price</th>
        </tr>

        <tr>
            <td>Banana</td>
            <td>500 Kg</td>
            <td>₹30/Kg</td>
        </tr>

        <tr>
            <td>Coconut</td>
            <td>1000 Nos</td>
            <td>₹25/Piece</td>
        </tr>

        <tr>
            <td>Lemon</td>
            <td>200 Kg</td>
            <td>₹60/Kg</td>
        </tr>

        <tr>
            <td>Banana Leaves</td>
            <td>500 Nos</td>
            <td>₹5/Piece</td>
        </tr>
    </table>
</section>

<section id="contact">
    <h2 class="section-title">Contact Us</h2>

    <div class="contact">
        <h3>VV Enterprices</h3>
        <p>📞 8883137259</p>
        <p>📧 boseveera9080@gmail.com</p>
    </div>
</section>

<footer>
    © 2026 VV Enterprices. All Rights Reserved.
</footer>

<a class="whatsapp"
href="https://wa.me/918883137259">
WhatsApp Order
</a>

</body>
</html>
