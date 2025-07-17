<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Uncle Mac Shawarma</title>
  <style>
    body { background: #fff; color: #8B0000; font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header, footer { background: #8B0000; color: white; text-align: center; padding: 1rem 0; }
    nav { background: #f8f8f8; display: flex; justify-content: center; padding: 0.5rem; }
    nav a { color: #8B0000; margin: 0 1rem; font-weight: bold; text-decoration: none; }
    nav a:hover { text-decoration: underline; }
    .hero { text-align: center; padding: 2rem; }
    .hero h1 { font-size: 2.5rem; margin-bottom: 0.5rem; }
    .hero p { color: #333; }
    .menu { display: flex; flex-wrap: wrap; gap: 1rem; justify-content: center; padding: 2rem; }
    .menu-item { flex: 1 1 300px; border: 1px solid #8B0000; border-radius: 8px; padding: 1rem; text-align: center; }
    .menu-item img { width: 100%; height: auto; border-radius: 4px; }
    .menu-item h3 { margin-top: 0.5rem; }
    .order-btn { display: inline-block; margin-top: 0.5rem; padding: 0.5rem 1rem; background: #8B0000; color: white; border: none; border-radius: 4px; cursor: pointer; }
    .order-btn:hover { background: #a10000; }
  </style>
</head>
<body>

  <header>
    <h1>Uncle Mac Shawarma</h1>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero" id="home">
    <h1>Welcome to Uncle Mac Shawarma</h1>
    <p>Only the best beef shawarma in town — pita wraps, burgers, and rice bowls!</p>
  </section>

  <section class="menu" id="menu">
    <div class="menu-item">
      <img src="https://via.placeholder.com/400x250?text=Beef+Pita+Wrap" alt="Beef Shawarma Pita Wrap">
      <h3>Beef Shawarma Pita Wrap</h3>
      <p>Thinly sliced beef, fresh veggies, signature sauce in a soft pita.</p>
      <button class="order-btn">Order Now</button>
    </div>
    <div class="menu-item">
      <img src="https://via.placeholder.com/400x250?text=Shawarma+Burger" alt="Shawarma Burger">
      <h3>Shawarma Burger – Beef</h3>
      <p>Juicy beef patty topped with shawarma spices and tangy sauce.</p>
      <button class="order-btn">Order Now</button>
    </div>
    <div class="menu-item">
      <img src="https://via.placeholder.com/400x250?text=Shawarma+Rice" alt="Shawarma Rice">
      <h3>Beef Shawarma Rice Bowl</h3>
      <p>Fragrant rice, seasoned beef strips, veggies, and creamy drizzle.</p>
      <button class="order-btn">Order Now</button>
    </div>
  </section>

  <section class="hero" id="contact">
    <h1>Contact Us</h1>
    <p>Email: info@unclemacshawarma.com | Phone: (123) 456‑7890</p>
  </section>

  <footer>
    <p>&copy; 2025 Uncle Mac Shawarma. All rights reserved.</p>
  </footer>

</body>
</html>
