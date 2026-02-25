<!DOCTYPE html>
<html>
<head>
  <title>Mins the Rover</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #001f3f, #0074D9);
      color: white;
      text-align: center;
    }

    nav {
      background: rgba(0,0,0,0.3);
      padding: 15px;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    .section {
      padding: 60px 20px;
    }

    .product {
      background: rgba(255,255,255,0.1);
      margin: 20px auto;
      padding: 20px;
      width: 300px;
      border-radius: 15px;
    }

    button {
      padding: 10px 20px;
      background: #00c3ff;
      border: none;
      border-radius: 20px;
      color: white;
      cursor: pointer;
      margin-top: 10px;
    }

    button:hover {
      background: #00e1ff;
    }
  </style>
</head>

<body>

<nav>
  <a href="index.html">Home</a>
  <a href="cart.html">Cart</a>
</nav>

<div class="section">
  <h1>Mins the Rover</h1>
  <h3>Innovation, one roll at a time.</h3>

  <p>
    At Mins Robotics, we believe the future of companionship is interactive,
    intelligent, and inspiring. Mins the Rover is an AI-powered rover pet
    designed to learn, grow, and explore with you.
  </p>

  <p>
    Built with smart sensors, emotional interaction,
    and learning features, Mins combines technology
    and creativity into one rolling companion.
  </p>
</div>

<div class="section">
  <h2>Our Products</h2>

  <div class="product">
    <h3>Mins the Rover</h3>
    <p>$149.99</p>
    <button onclick="addToCart('Mins the Rover', 149.99)">Add to Cart</button>
  </div>

  <div class="product">
    <h3>Extended Battery Pack</h3>
    <p>$29.99</p>
    <button onclick="addToCart('Extended Battery Pack', 29.99)">Add to Cart</button>
  </div>

</div>

<script>
function addToCart(name, price) {
  let cart = JSON.parse(localStorage.getItem("cart")) || [];
  cart.push({name: name, price: price});
  localStorage.setItem("cart", JSON.stringify(cart));
  alert(name + " added to cart!");
}
</script>

</body>
</html>


