<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sideway Sensation</title>
  <link rel="stylesheet" href="style.css" />
  <script defer src="script.js"></script>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: url('Untitled design (1).png') no-repeat center center fixed;
      background-size: cover;
      animation: fadeIn 2s ease-in;
    }

    @keyframes fadeIn {
      from { opacity: 0; filter: blur(5px); }
      to { opacity: 1; filter: blur(0); }
    }

    .page-wrapper {
      background-color: rgba(0, 0, 0, 0.7);
      min-height: 100vh;
      color: white;
      padding: 20px;
    }

    .top-banner img {
      width: 100%;
      height: auto;
    }

    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-top: 20px;
    }

    .cart {
      font-size: 1.2em;
    }

    .products {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 30px;
    }

    .product {
      background-color: #222;
      padding: 15px;
      border-radius: 10px;
      width: 200px;
      text-align: center;
    }

    .product img {
      width: 100%;
      height: auto;
      border-radius: 8px;
    }

    button {
      background-color: #00bcd4;
      color: white;
      border: none;
      padding: 10px 15px;
      margin-top: 10px;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #0097a7;
    }
  </style>
</head>
<body>
  <div class="page-wrapper">
    <!-- Top Banner -->
    <header class="top-banner">
      <img src="TOP banner.png" alt="Sideway Sensation Banner">
    </header>

    <!-- Header Section -->
    <section class="header">
      <h1>Sideway Sensation Drift Build Fan Funds</h1>
      <div class="cart">
        🛒 <span id="cart-count">0</span>
      </div>
    </section>

    <!-- Product Section -->
    <section class="products">
      <div class="product">
        <img src="pink-flat-1.jpg" alt="Pink Flat Cap">
        <h2>Pink Flat Cap</h2>
        <p>R150</p>
        <button onclick="addToCart('Pink Flat Cap')">Add to Basket</button>
      </div>

      <div class="product">
        <img src="gray-flat-1.jpg" alt="Gray Flat Cap">
        <h2>Gray Flat Cap</h2>
        <p>R150</p>
        <button onclick="addToCart('Gray Flat Cap')">Add to Basket</button>
      </div>

      <div class="product">
        <img src="gray-black-1.jpg" alt="Gray & Black Cap">
        <h2>Gray & Black Cap</h2>
        <p>R150</p>
        <button onclick="addToCart('Gray & Black Cap')">Add to Basket</button>
      </div>
    </section>
  </div>

  <script>
    let cartCount = 0;

    function addToCart(itemName) {
      cartCount++;
      document.getElementById('cart-count').innerText = cartCount;
      console.log(`${itemName} added to basket.`);
    }
  </script>
</body>
</html>
