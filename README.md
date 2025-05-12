<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Fruit2U - Fresh Fruit Delivery Fairfield</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f7f7f7; color: #333; }
    header { background: #4CAF50; color: white; padding: 20px; text-align: center; }
    nav { background: #388E3C; padding: 10px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    .hero { background: url('https://images.unsplash.com/photo-1574226516831-e1dff420e13c') no-repeat center center/cover; height: 300px; display: flex; align-items: center; justify-content: center; color: white; text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.6); font-size: 2em; }
    .section { padding: 40px 20px; max-width: 800px; margin: auto; }
    .box { background: white; padding: 20px; margin-bottom: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    footer { background: #333; color: white; text-align: center; padding: 20px; }
    button { background: #4CAF50; color: white; padding: 10px 20px; border: none; cursor: pointer; }
    form input, form select, form textarea { width: 100%; padding: 10px; margin-bottom: 15px; border: 1px solid #ccc; border-radius: 4px; }
    form label { font-weight: bold; }
  </style>
</head>
<body>
  <header>
    <h1>Fruit2U</h1>
    <p>Fresh Fruit Delivery - Fairfield NSW</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#boxes">Boxes</a>
    <a href="#how">How It Works</a>
    <a href="#about">About</a>
    <a href="#order">Order</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero">
    <p>Fruit to Your Door. Fast. Local. Affordable.</p>
  </div>

  <div class="section" id="home">
    <div class="box">
      <h2>Welcome to Fruit2U</h2>
      <p>We’re a local fruit delivery service based in Fairfield, NSW. We deliver fresh, seasonal fruit straight to your home or workplace.</p>
    </div>
  </div>

  <div class="section" id="boxes">
    <div class="box">
      <h2>Our Boxes</h2>
      <ul>
        <li><strong>Mini Box</strong> – 15 pieces – $25</li>
        <li><strong>Standard Box</strong> – 30 pieces – $40</li>
        <li><strong>Family Box</strong> – 50 pieces – $60</li>
      </ul>
    </div>
  </div>

  <div class="section" id="how">
    <div class="box">
      <h2>How It Works</h2>
      <ol>
        <li>Choose your box size</li>
        <li>Fill out the order form</li>
        <li>We deliver it to your door in Fairfield and nearby suburbs</li>
      </ol>
    </div>
  </div>

  <div class="section" id="about">
    <div class="box">
      <h2>About Us</h2>
      <p>Fruit2U started as a small garage-based business in Fairfield. We believe everyone deserves easy access to fresh, local fruit. Our family-run business takes pride in offering fast, friendly service and great value.</p>
    </div>
  </div>

  <div class="section" id="order">
    <div class="box">
      <h2>Order Form</h2>
      <form action="mailto:fruit2u.orders@gmail.com" method="post" enctype="text/plain">
        <label for="name">Your Name</label>
        <input type="text" id="name" name="name" required />

        <label for="email">Email</label>
        <input type="email" id="email" name="email" required />

        <label for="phone">Phone</label>
        <input type="tel" id="phone" name="phone" />

        <label for="box">Choose a Box</label>
        <select id="box" name="box">
          <option value="Mini Box">Mini Box - $25</option>
          <option value="Standard Box">Standard Box - $40</option>
          <option value="Family Box">Family Box - $60</option>
        </select>

        <label for="address">Delivery Address</label>
        <textarea id="address" name="address" rows="3" required></textarea>

        <button type="submit">Place Order</button>
      </form>
    </div>
  </div>

  <div class="section" id="contact">
    <div class="box">
      <h2>Contact Us</h2>
      <p><strong>Phone:</strong> 0414 714 494</p>
      <p><strong>Email:</strong> fruit2u.orders@gmail.com</p>
      <p><strong>Delivery Area:</strong> Fairfield & surrounding suburbs</p>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 Fruit2U. All rights reserved.</p>
  </footer>
</body>
</html>
