<!DOCTYPE html>
<html>
<head>
<title>Mins the Rover</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body {
  margin:0;
  font-family: 'Segoe UI', Arial, sans-serif;
  background:#eef2ff;
  color:#1e3a8a;
}

nav {
  background:white;
  padding:15px;
  display:flex;
  justify-content:space-between;
  align-items:center;
  box-shadow:0 2px 8px rgba(0,0,0,0.1);
}

nav a {
  text-decoration:none;
  color:#1e3a8a;
  margin:0 15px;
  font-weight:600;
}

.hero {
  text-align:center;
  padding:80px 20px;
  background:linear-gradient(135deg,#3b82f6,#1e40af);
  color:white;
}

.hero h1 {
  font-size:48px;
  margin-bottom:10px;
}

button {
  background:#2563eb;
  border:none;
  padding:12px 25px;
  color:white;
  border-radius:8px;
  cursor:pointer;
  font-weight:600;
  transition:0.3s;
}

button:hover {
  background:#1e40af;
  transform:scale(1.05);
}

.products {
  padding:60px 20px;
  text-align:center;
}

.product-grid {
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
  gap:30px;
  margin-top:40px;
}

.card {
  background:white;
  padding:25px;
  border-radius:15px;
  width:260px;
  box-shadow:0 10px 25px rgba(0,0,0,0.1);
  transition:0.3s;
}

.card:hover {
  transform:translateY(-8px);
}

.price {
  font-size:20px;
  font-weight:bold;
  margin:10px 0;
}

footer {
  background:#1e3a8a;
  color:white;
  text-align:center;
  padding:30px;
  margin-top:60px;
}
</style>
</head>

<body>

<nav>
  <div><strong>Mins Robotics</strong></div>
  <div>
    <a href="features.html">Features</a>
    <a href="cart.html">Cart</a>
  </div>
</nav>

<div class="hero">
  <h1>Mins the Rover</h1>
  <p>Innovation, One Roll at a Time</p>
  <div class="price">$129.99</div>
  <button onclick="addToCart('Mins the Rover - $129.99')">Add to Cart</button>
</div>

<div class="products">
  <h2>Add-On Products</h2>

  <div class="product-grid">

    <div class="card">
      <h3>Obstacle Course Kit</h3>
      <p>Build ramps and tracks for racing challenges.</p>
      <div class="price">$29.99</div>
      <button onclick="addToCart('Obstacle Course Kit - $29.99')">Add to Cart</button>
    </div>

    <div class="card">
      <h3>Custom Skin Pack</h3>
      <p>Blue, Midnight Black, Mars Red finishes.</p>
      <div class="price">$19.99</div>
      <button onclick="addToCart('Custom Skin Pack - $19.99')">Add to Cart</button>
    </div>

    <div class="card">
      <h3>LED Expansion Pack</h3>
      <p>Unlock new light patterns and effects.</p>
      <div class="price">$14.99</div>
      <button onclick="addToCart('LED Expansion Pack - $14.99')">Add to Cart</button>
    </div>

    <div class="card">
      <h3>Charging Dock Pro</h3>
      <p>Fast charging premium dock.</p>
      <div class="price">$24.99</div>
      <button onclick="addToCart('Charging Dock Pro - $24.99')">Add to Cart</button>
    </div>

  </div>
</div>

<footer>
  © 2026 Mins Robotics | Designed for the Future
</footer>

<script>
function addToCart(item) {
  let cart = JSON.parse(localStorage.getItem("cart")) || [];
  cart.push(item);
  localStorage.setItem("cart", JSON.stringify(cart));
  alert("Added to cart!");
}
</script>

</body>
</html>
