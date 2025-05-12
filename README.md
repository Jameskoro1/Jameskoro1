<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>FreshCrate - Local Fruit Delivery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f7f7f7;
      color: #333;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1574226516831-e1dff420e13c') no-repeat center center/cover;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.6);
      font-size: 2em;
    }
    .section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
    }
    .box {
      background: white;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 20px;
    }
    button {
      background: #4CAF50;
      color: white;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>FreshCrate</h1>
    <p>Local Fruit Delivery from Our Garage to Your Door</p>
  </header>

  <div class="hero">
    <p>Fresh. Affordable. Local.</p>
  </div>

  <div class="section">
    <div class="box">
      <h2>About Us</h2>
      <p>We’re a small family-run fruit delivery business based in [Your Suburb], offering affordable and fresh fruit boxes straight from local markets. We deliver to homes and small offices, making healthy eating convenient and easy.</p>
    </div>

    <div class="box">
      <h2>Our Boxes</h2>
      <ul>
        <li><strong>Mini Box</strong> – 15 pieces – $25</li>
        <li><strong>Standard Box</strong> – 30 pieces – $40</li>
        <li><strong>Family Box</strong> – 50 pieces – $60</li>
      </ul>
    </div>

    <div class="box">
      <h2>Order Now</h2>
      <p>Text or call <strong>0400 000 000</strong> to place your order. We deliver every Monday and Thursday to [Your Suburbs].</p>
      <button onclick="window.location.href='mailto:orders@freshcrate.com'">Email Us</button>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 FreshCrate. All rights reserved.</p>
  </footer>
</body>
</html>
