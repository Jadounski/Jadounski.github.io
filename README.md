<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Café Aroma</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Header -->
  <header>
    <div class="container">
      <h1>Café Aroma</h1>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Menu</a></li>
          <li><a href="#">About Us</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Main Content -->
  <main>
    <!-- Welcome Section -->
    <section class="welcome">
      <h2>Welcome to Café Aroma</h2>
      <p>Your cozy neighborhood coffee spot. Come for the aroma, stay for the comfort.</p>
    </section>

    <!-- Menu Section -->
    <section class="menu">
      <h2>Our Menu</h2>
      <div class="menu-items">
        <div class="item">
          <img src="images/coffee1.jpg" alt="Espresso">
          <h3>Espresso</h3>
          <p>Rich, bold, and smooth – the perfect shot to start your day.</p>
        </div>
        <div class="item">
          <img src="images/coffee2.jpg" alt="Cappuccino">
          <h3>Cappuccino</h3>
          <p>Frothy milk and robust coffee, a classic favorite.</p>
        </div>
        <div class="item">
          <img src="images/coffee3.jpg" alt="Iced Latte">
          <h3>Iced Latte</h3>
          <p>Chill out with our refreshing and creamy iced latte.</p>
        </div>
      </div>
    </section>

    <!-- About Us Section -->
    <section class="about">
      <h2>About Us</h2>
      <p>Founded in 2020, Café Aroma brings people together over great coffee. Our mission is to serve high-quality, ethically sourced coffee while creating a warm, welcoming space for our community.</p>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Café Aroma. All rights reserved.</p>
    <div class="socials">
      <a href="#">Facebook</a> |
      <a href="#">Instagram</a> |
      <a href="#">Twitter</a>
    </div>
  </footer>

</body>
</html>





/* Reset and Base Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  color: #333;
  background-color: #fffdf7;
}

/* Header */
header {
  background-color: #6f4e37;
  color: #fff;
  padding: 20px 0;
}

header .container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header h1 {
  font-size: 2rem;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

/* Sections */
section {
  padding: 40px 20px;
  max-width: 1000px;
  margin: auto;
}

.welcome {
  text-align: center;
}

.menu-items {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: space-around;
}

.item {
  background: #f9f4ef;
  padding: 20px;
  border-radius: 10px;
  width: 280px;
  text-align: center;
}

.item img {
  max-width: 100%;
  border-radius: 10px;
}

/* Footer */
footer {
  background-color: #6f4e37;
  color: #fff;
  text-align: center;
  padding: 20px;
  font-size: 0.9rem;
}

footer .socials a {
  color: #fff;
  text-decoration: none;
  margin: 0 5px;
}

/* Responsive Design */
@media (max-width: 768px) {
  header .container {
    flex-direction: column;
    align-items: flex-start;
  }

  nav ul {
    flex-direction: column;
    gap: 10px;
  }

  .menu-items {
    flex-direction: column;
    align-items: center;
  }
}
