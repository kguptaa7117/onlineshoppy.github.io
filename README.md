# onlineshoppy
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>onlineshoppy.com</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #ffffff;
      color: #333;
    }
    header {
      background-color: #007BFF;
      color: #fff;
      padding: 15px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    .logo {
      font-weight: bold;
      font-size: 20px;
    }
    .container {
      padding: 20px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .product {
      border: 1px solid #ddd;
      border-radius: 6px;
      padding: 15px;
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 4px;
    }
    .product h3 {
      margin: 10px 0;
    }
    .paypal-button {
      margin-top: 10px;
      background-color: #ffc439;
      border: none;
      padding: 10px 20px;
      font-weight: bold;
      cursor: pointer;
      border-radius: 4px;
    }
    footer {
      text-align: center;
      padding: 15px;
      background-color: #f1f1f1;
      margin-top: 30px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">onlineshoppy.com</div>
    <div>Shop Everything!</div>
  </header>

  <div class="container">
    <h2>Featured Products</h2>
    <div class="products">
      <!-- Product 1 -->
      <div class="product">
        <img src="https://via.placeholder.com/300x200?text=Smart+Watch" alt="Smart Watch">
        <h3>Smart Watch</h3>
        <p>Fitness tracker with heart rate monitor</p>
        <button class="paypal-button">Buy with PayPal</button>
      </div>
      <!-- Product 2 -->
      <div class="product">
        <img src="https://via.placeholder.com/300x200?text=Wireless+Earbuds" alt="Earbuds">
        <h3>Wireless Earbuds</h3>
        <p>High-quality audio with noise canceling</p>
        <button class="paypal-button">Buy with PayPal</button>
      </div>
      <!-- Product 3 -->
      <div class="product">
        <img src="https://via.placeholder.com/300x200?text=Mini+Blender" alt="Mini Blender">
        <h3>Mini Blender</h3>
        <p>Portable USB blender for smoothies</p>
        <button class="paypal-button">Buy with PayPal</button>
      </div>
      <!-- Product 4 -->
      <div class="product">
        <img src="https://via.placeholder.com/300x200?text=LED+Lamp" alt="LED Lamp">
        <h3>LED Desk Lamp</h3>
        <p>Touch control with adjustable brightness</p>
        <button class="paypal-button">Buy with PayPal</button>
      </div>
    </div>
  </div>

  <footer>
    &copy; 2025 onlineshoppy.com | All rights reserved
  </footer>
</body>
</html>
