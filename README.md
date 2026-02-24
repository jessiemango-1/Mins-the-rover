<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mins the Rover</title>

<style>
html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #0b1120;
  color: white;
}

nav {
  background-color: #111827;
  padding: 15px;
  position: sticky;
  top: 0;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  color: #ef4444;
}

header {
  background: linear-gradient(90deg, #7f1d1d, #ef4444);
  padding: 80px 20px;
  text-align: center;
}

section {
  padding: 60px 20px;
  text-align: center;
}

h1 { font-size: 48px; }
h2 { margin-bottom: 20px; }

button {
  background-color: #ef4444;
  border: none;
  padding: 15px 30px;
  font-size: 16px;
  color: white;
  border-radius: 8px;
  cursor: pointer;
  margin-top: 15px;
}

button:hover {
  background-color: #dc2626;
}

.card-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.card {
  background-color: #1f2937;
  padding: 20px;
  border-radius: 10px;
  width: 260px;
}

table {
  margin: auto;
  border-collapse: collapse;
  width: 80%;
}

th, td {
  border: 1px solid #374151;
  padding: 12px;
}

th {
  background-color: #1f2937;
}

footer {
  background-color: #111827;
  padding: 30px;
  text-align: center;
}

input, textarea {
  width: 60%;
  padding: 10px;
  margin: 10px 0;
  border-radius: 5px;
  border: none;
}

</style>
</head>

<body>

<nav>
  <a href="#home">Home</a>
  <a href="#features">Features</a>
  <a href="#pricing">Pricing</a>
  <a href="#comparison">Compare</a>
  <a href="#reviews">Reviews</a>
  <a href="#faq">FAQ</a>
  <a href="#contact">Contact</a>
</nav>

<header id="home">
  <h1>Mins the Rover</h1>
  <p>Innovation, One Roll at a Time.</p>
  <h2>$129.99</h2>
  <button onclick="alert('Checkout Coming Soon!')">Buy Now</button>
</header>

<section id="features">
  <h2>Features</h2>
  <div class="card-container">
    <div class="card">
      <h3>360° Rolling</h3>
      <p>Moves smoothly in every direction.</p>
    </div>
    <div class="card">
      <h3>Voice Commands</h3>
      <p>Responds when called by name.</p>
    </div>
    <div class="card">
      <h3>Emotional LEDs</h3>
      <p>Displays excitement and curiosity.</p>
    </div>
    <div class="card">
      <h3>Smart Sensors</h3>
      <p>Detects touch and movement.</p>
    </div>
    <div class="card">
      <h3>Rechargeable</h3>
      <p>Long-lasting battery life.</p>
    </div>
    <div class="card">
      <h3>Companion App</h3>
      <p>Customize tricks and behaviors.</p>
    </div>
  </div>
</section>

<section id="pricing">
  <h2>Pricing</h2>
  <div class="card-container">
    <div class="card">
      <h3>Mins the Rover</h3>
      <p>$129.99</p>
      <p>Includes Rover, Dock, App Access</p>
      <button onclick="alert('Order Feature Coming Soon!')">Purchase</button>
    </div>
    <div class="card">
      <h3>Accessories Pack</h3>
      <p>$29.99</p>
      <p>Obstacle Course + Custom Skins</p>
      <button onclick="alert('Accessory Checkout Coming Soon!')">Add to Cart</button>
    </div>
  </div>
</section>

<section id="comparison">
  <h2>How Mins Compares</h2>
  <table>
    <tr>
      <th>Feature</th>
      <th>Mins</th>
      <th>Typical Robot Pet</th>
    </tr>
    <tr>
      <td>360° Mobility</td>
      <td>Yes</td>
      <td>Limited</td>
    </tr>
    <tr>
      <td>Voice Commands</td>
      <td>Advanced</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>LED Emotions</td>
      <td>Expressive</td>
      <td>Minimal</td>
    </tr>
    <tr>
      <td>Price</td>
      <td>$129.99</td>
      <td>$100–$200</td>
    </tr>
  </table>
</section>

<section id="reviews">
  <h2>Customer Reviews</h2>
  <div class="card-container">
    <div class="card">
      <p>"My kids love it! So interactive!"</p>
      <strong>★★★★★</strong>
    </div>
    <div class="card">
      <p>"Feels like the future of robot pets."</p>
      <strong>★★★★★</strong>
    </div>
    <div class="card">
      <p>"The rolling movement is so cool!"</p>
      <strong>★★★★☆</strong>
    </div>
  </div>
</section>

<section id="faq">
  <h2>FAQ</h2>
  <p><strong>How long does the battery last?</strong><br>Up to 4 hours of active play.</p>
  <p><strong>Is it safe for kids?</strong><br>Yes, built with durable and safe materials.</p>
  <p><strong>Does it require WiFi?</strong><br>Only for app customization features.</p>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <form>
    <input type="text" placeholder="Your Name"><br>
    <input type="email" placeholder="Your Email"><br>
    <textarea placeholder="Your Message"></textarea><br>
    <button type="submit">Send Message</button>
  </form>
</section>

<footer>
  <p>© 2026 Mins Robotics | Innovation One Roll at a Time</p>
</footer>

</body>
</html>
