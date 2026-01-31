//index.html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Eatero</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!-- NAVBAR -->
    <nav class="navbar">
      <div class="logo">
        <img src="images/e1.png" alt="Eatero Logo" />
      </div>

      <ul class="nav-links">
        <li onclick="showSection('home')">Home</li>
        <li onclick="showSection('menu')">Menu</li>
        <li onclick="showSection('about')">About Us</li>
        <li onclick="showSection('contact')">Contact</li>
      </ul>

      <div class="nav-icons">
        <button onclick="showSection('menu')" title="Search Menu">🔍</button>
        <button onclick="showSection('cart')" title="Cart">🛒</button>
        <button onclick="showSection('profile')" title="Profile">👤</button>
      </div>
    </nav>

    <!-- HOME -->
    <section id="home" class="section home active"></section>

    <!-- MENU -->
    <section id="menu" class="section">
      <h2>Our Menu</h2>
      <div class="menu-items">
        <div class="card">
          <h3>Veg Burger</h3>
          <p>Delicious veggie burger with fresh lettuce, tomato, and cheese.</p>
          <p>₹120</p>
          <button>Add to Cart</button>
        </div>
        <div class="card">
          <h3>Pizza</h3>
          <p>Classic Margherita with golden crust and mozzarella cheese.</p>
          <p>₹250</p>
          <button>Add to Cart</button>
        </div>
        <div class="card">
          <h3>Pasta</h3>
          <p>Creamy Alfredo pasta with fresh herbs and parmesan.</p>
          <p>₹180</p>
          <button>Add to Cart</button>
        </div>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about" class="section">
      <div class="content-box">
        <p>
          Eatero is built on the philosophy of
          <strong>Platform Neutrality</strong>, ensuring fair pricing and
          transparency.
        </p>
        <br />
        <p>
          Our mission is to provide a
          <strong>trustworthy food delivery experience</strong> while empowering
          local restaurants and supporting niche dietary requirements.
          <br /><br />
          <strong>No hidden markups. No unnecessary layers.</strong>
          Just a cleaner connection between you and the food you love.
        </p>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="section">
      <div class="content-box">
        <h2>Contact Us</h2>
        <br />
        <p>Email: support@eatero.com</p>
        <p>Phone: +91 9512364789</p>
        <p>
          Address: Shop no.11, Siddhivinayak road, near Jay Footwear, Ravet,
          Pune
        </p>
        <p>
          Follow us on:
          <a href="#">Instagram</a> | <a href="#">Facebook</a> |
          <a href="#">Twitter</a>
        </p>
      </div>
    </section>

    <!-- CART -->
    <section id="cart" class="section">
      <div class="content-box">
        <h2>Your Cart</h2>
        <p>Your cart is empty.</p>
      </div>
    </section>

    <section id="profile" class="section">
      <div class="content-box">
        <h2>Profile</h2>
        <p>Name: John Doe</p>
        <p>Email: johndoe@example.com</p>
      </div>
    </section>

    <script src="script.js"></script>
  </body>
</html>
