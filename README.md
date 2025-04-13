<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Food Delivery App</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <h1>Food Express</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Menu</a>
      <a href="#">Cart</a>
    </nav>
  </header>

  <main>
    <section id="menu">
      <h2>Our Menu</h2>
      <div class="food-list">
        <div class="food-item">
          <img src="https://via.placeholder.com/150" alt="Burger"/>
          <h3>Burger</h3>
          <p>$5.99</p>
          <button onclick="addToCart('Burger', 5.99)">Add to Cart</button>
        </div>
        <div class="food-item">
          <img src="https://via.placeholder.com/150" alt="Pizza"/>
          <h3>Pizza</h3>
          <p>$8.99</p>
          <button onclick="addToCart('Pizza', 8.99)">Add to Cart</button>
        </div>
        <!-- Add more items similarly -->
      </div>
    </section>

    <section id="cart">
      <h2>Your Cart</h2>
      <ul id="cart-items"></ul>
      <p>Total: $<span id="total">0.00</span></p>
    </section>
  </main>

  <script src="script.js"></script>
</body>
</html>
