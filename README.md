# Keymomentrentals
Key moment rentals site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Key Moment Rentals</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background-color: #000;
      color: #fff;
    }
    header {
      background: #000;
      padding: 15px 30px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    header img {
      height: 60px;
    }
    nav a {
      color: #d4af37;
      text-decoration: none;
      margin-left: 20px;
      font-weight: bold;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1529634895247-8f985f0f0e2b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1600&q=80') no-repeat center center/cover;
      height: 90vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
      padding: 0 20px;
    }
    .hero h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }
    .hero button {
      background: #d4af37;
      color: #000;
      padding: 12px 25px;
      border: none;
      font-size: 1rem;
      font-weight: bold;
      cursor: pointer;
      border-radius: 5px;
    }
    section {
      padding: 60px 20px;
      text-align: center;
    }
    section h2 {
      font-family: 'Playfair Display', serif;
      color: #d4af37;
      font-size: 2rem;
      margin-bottom: 30px;
    }
    .rentals {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 30px;
    }
    .rental-item {
      background: #111;
      padding: 20px;
      border-radius: 10px;
      width: 250px;
    }
    .rental-item img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 15px;
    }
    .rental-item h3 {
      color: #fff;
      margin: 10px 0 5px;
    }
    .rental-item p {
      color: #d4af37;
      font-weight: bold;
    }
    footer {
      background: #000;
      text-align: center;
      padding: 20px;
      color: #888;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <img src="logo.png" alt="Key Moment Rentals Logo">
    <nav>
      <a href="#rentals">Our Rentals</a>
      <a href="#booking">Book Now</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Party Rentals for Every Occasion</h1>
    <p>Providing tables, chairs, and more to make your event unforgettable.</p>
    <button onclick="document.getElementById('booking').scrollIntoView({behavior:'smooth'})">Book Now</button>
  </section>

  <!-- Our Rentals -->
  <section id="rentals">
    <h2>Our Rentals</h2>
    <div class="rentals">
      <div class="rental-item">
        <img src="chair.jpg" alt="White Wood Wedding Chair">
        <h3>White Wood Wedding Chair</h3>
        <p>$3 per day</p>
      </div>
      <div class="rental-item">
        <img src="table.jpg" alt="6 ft Folding Table">
        <h3>6 ft Folding Table</h3>
        <p>$7 per day</p>
      </div>
      <div class="rental-item">
        <img src="moonbounce.jpg" alt="Moon Bounce">
        <h3>Moon Bounce</h3>
        <p>$125 per day</p>
      </div>
    </div>
  </section>

  <!-- Booking Form -->
  <section id="booking">
    <h2>Book Your Rentals</h2>
    <form action="https://formspree.io/f/YOUR-FORM-ID" method="POST" style="max-width:500px;margin:auto;text-align:left;">
      <label>Name:</label><br>
      <input type="text" name="name" required style="width:100%;padding:10px;margin-bottom:10px;"><br>
      <label>Email:</label><br>
      <input type="email" name="email" required style="width:100%;padding:10px;margin-bottom:10px;"><br>
      <label>Event Date:</label><br>
      <input type="date" name="date" required style="width:100%;padding:10px;margin-bottom:10px;"><br>
      <label>Items Needed:</label><br>
      <textarea name="items" required style="width:100%;padding:10px;margin-bottom:10px;"></textarea><br>
      <button type="submit" style="background:#d4af37;color:#000;padding:12px 20px;border:none;border-radius:5px;cursor:pointer;font-weight:bold;">Submit Booking</button>
    </form>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:keymomentrentals@gmail.com" style="color:#d4af37;">keymomentrentals@gmail.com</a></p>
    <p>Payments: Venmo @Kimberley-Ahumada | Zelle 512-584-3370</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Key Moment Rentals | Georgetown, TX</p>
  </footer>

</body>
</html>
