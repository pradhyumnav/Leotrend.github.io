# Leotrend.github.io
<!DOCTYPE html>
<html>
<head>
  <title>LEO TREND</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #111;
      color: white;
    }

    header {
      background: black;
      text-align: center;
      padding: 20px;
    }

    header h1 {
      margin: 0;
      color: #f1c40f;
      font-size: 32px;
    }

    .banner img {
      width: 100%;
    }

    .shop-img img {
      width: 100%;
      height: auto;
    }

    .section {
      padding: 20px;
      text-align: center;
    }

    .section h2 {
      color: #f1c40f;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .card {
      background: #222;
      margin: 10px;
      padding: 15px;
      border-radius: 10px;
      width: 220px;
    }

    .card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
      border-radius: 10px;
    }

    .price {
      color: #f1c40f;
      margin-top: 10px;
    }

    .btn {
      background: #f1c40f;
      color: black;
      padding: 10px;
      margin-top: 10px;
      display: inline-block;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }

    footer {
      background: black;
      padding: 15px;
      text-align: center;
    }
  </style>
</head>

<body>

<header>
  <h1>LEO TREND</h1>
  <p>Men's Fashion • Style & Comfort</p>
</header>

<!-- 🏬 Shop Image -->
<div class="shop-img">
  <img src="shop.jpg" alt="LEO TREND Shop">
</div>

<!-- 🔥 Flyer -->
<div class="banner">
  <img src="Leo.jpg" alt="Flash Sale">
</div>

<!-- 👕 Shirts -->
<div class="section">
  <h2>🔥 4 Shirts @ ₹999</h2>
  <div class="products">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1602810318383-e386cc2a3ccf">
      <p>Casual Check Shirt</p>
      <div class="price">₹999 (4 pcs)</div>
      <a class="btn" href="https://wa.me/919945264617">Order</a>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1596755094514-f87e34085b2c">
      <p>Denim Shirt</p>
      <div class="price">₹999 (4 pcs)</div>
      <a class="btn" href="https://wa.me/919945264617">Order</a>
    </div>

  </div>
</div>

<!-- 👖 Jeans -->
<div class="section">
  <h2>🔥 4 Jeans @ ₹999</h2>
  <div class="products">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1582552938357-32b906df40cb">
      <p>Blue Slim Jeans</p>
      <div class="price">₹999 (4 pcs)</div>
      <a class="btn" href="https://wa.me/919945264617">Order</a>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1602293589930-45aad59ba3ab">
      <p>Black Denim</p>
      <div class="price">₹999 (4 pcs)</div>
      <a class="btn" href="https://wa.me/919945264617">Order</a>
    </div>

  </div>
</div>

<!-- 👕 T-Shirts -->
<div class="section">
  <h2>🔥 5 T-Shirts @ ₹999</h2>
  <div class="products">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab">
      <p>Basic White Tee</p>
      <div class="price">₹999 (5 pcs)</div>
      <a class="btn" href="https://wa.me/919945264617">Order</a>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1503342217505-b0a15ec3261c">
      <p>Stylish Red Tee</p>
      <div class="price">₹999 (5 pcs)</div>
      <a class="btn" href="https://wa.me/919945264617">Order</a>
    </div>

  </div>
</div>

<!-- 📍 Location -->
<div class="section">
  <h2>📍 Visit Our Store</h2>

  <iframe 
    src="https://maps.google.com/maps?q=12.9232498,77.5493787&z=15&output=embed"
    width="100%" 
    height="300" 
    style="border:0; border-radius:10px;">
  </iframe>

  <p>Bhuvaneshwari Nagar, Bengaluru</p>

  <a class="btn" href="https://maps.google.com/?q=12.9232498,77.5493787">
    Open in Google Maps
  </a>
</div>

<!-- 📞 Contact -->
<div class="section">
  <h2>📞 Contact</h2>
  <p>Call: 9945264617</p>
  <a class="btn" href="https://wa.me/919945264617">Chat on WhatsApp</a>
</div>

<footer>
  <p>© 2026 LEO TREND</p>
</footer>

</body>
</html>
