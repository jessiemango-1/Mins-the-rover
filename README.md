<!DOCTYPE html>
<html>
<head>
<title>Mins the Rover</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body {
  margin:0;
  font-family: Arial, sans-serif;
  background:#f1f5f9;
  color:#1e3a8a;
}

nav {
  background:#1e3a8a;
  padding:15px;
  text-align:center;
}

nav a {
  color:white;
  margin:0 15px;
  text-decoration:none;
  font-weight:bold;
}

header {
  text-align:center;
  padding:80px 20px;
  background:linear-gradient(90deg,#2563eb,#1e40af);
  color:white;
}

button {
  background:#2563eb;
  border:none;
  padding:12px 25px;
  color:white;
  border-radius:6px;
  cursor:pointer;
}

button:hover {
  background:#1e40af;
}

section {
  padding:60px 20px;
  text-align:center;
}
</style>
</head>

<body>

<nav>
  <a href="index.html">Home</a>
  <a href="features.html">Features</a>
  <a href="cart.html">Cart</a>
</nav>

<header>
  <h1>Mins the Rover</h1>
  <p>Innovation, One Roll at a Time</p>
  <h2>$129.99</h2>
  <button onclick="addToCart()">Add to Cart</button>
</header>

<section>
  <h2>The Future of Interactive Pets</h2>
  <p>Mins combines robotics, fun, and innovation into one rolling companion.</p>
</section>

<script>
function addToCart(){
  localStorage.setItem("cart","Mins the Rover - $129.99");
  alert("Added to cart!");
}
</script>

</body>
</html>
