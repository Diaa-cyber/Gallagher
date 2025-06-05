<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Gallagher – Order Online</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background-color: #2b2b2b;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    .container {
      max-width: 800px;
      margin: auto;
      padding: 20px;
      background: #fff;
    }
    h2 {
      border-bottom: 2px solid #ccc;
      padding-bottom: 10px;
    }
    .product {
      display: flex;
      justify-content: space-between;
      padding: 10px 0;
      border-bottom: 1px solid #eee;
    }
    .order-options {
      margin: 20px 0;
    }
    .order-options a {
      display: inline-block;
      margin: 10px;
      padding: 12px 20px;
      background-color: #25d366;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
    }
    .order-options a.sms {
      background-color: #4285f4;
    }
    form {
      background: #fafafa;
      padding: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form input, form textarea {
      width: 100%;
      margin-bottom: 10px;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 4px;
    }
    form button {
      background-color: #333;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 14px;
      background: #2b2b2b;
      color: #ccc;
    }
  </style>
</head>
<body>

  <header>
    <h1>Gallagher</h1>
    <p>Fresh drinks and groceries – Order Online</p>
  </header>

  <div class="container">
    <h2>Products</h2>
    <div class="product"><span>Water 20oz</span><span>$2.99</span></div>
    <div class="product"><span>Pepsi 20oz</span><span>$2.99</span></div>
    <div class="product"><span>Milk half gallon</span><span>$4.99</span></div>
    <div class="product"><span>Tomato 1lb</span><span>$1.99</span></div>
    <div class="product"><span>Potato 1lb</span><span>$2.99</span></div>

    <div class="order-options">
      <h2>Order Now</h2>
      <a class="sms" href="sms:+1234567890?body=Hi Gallagher, I’d like to order...">Order via SMS</a>
      <a href="https://wa.me/1234567890?text=Hi%20Gallagher,%20I’d%20like%20to%20order...">Order via WhatsApp</a>
    </div>

    <form name="orderForm" method="POST" data-netlify="true">
      <h2>Order via Form</h2>
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="tel" name="phone" placeholder="Phone Number" required />
      <textarea name="order" rows="4" placeholder="What would you like to order?" required></textarea>
      <button type="submit">Submit Order</button>
    </form>
  </div>

  <footer>
    &copy; 2025 Gallagher. All rights reserved.
  </footer>

</body>
</html>
