<!DOCTYPE html>
<html lang="de">
<Lukas&Lena>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Online-Shop</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">Mein Shop</div>
    <nav>
      <ul>
        <li><a href="#home">Startseite</a></li>
        <li><a href="#shop">Shop</a></li>
        <li><a href="#contact">Kontakt</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1>Willkommen in unserem Online-Shop</h1>
    <p>Entdecke stilvolle Produkte für deinen Alltag.</p>
  </section>

  <section id="shop" class="shop">
    <h2>Unsere Produkte</h2>
    <div class="product-grid">
      <div class="product">
        <img src="produkt1.jpg" alt="Produkt 1">
        <h3>Produkt 1</h3>
        <p>Beschreibung des Produkts.</p>
        <button>Zum Warenkorb hinzufügen</button>
      </div>
      <div class="product">
        <img src="produkt2.jpg" alt="Produkt 2">
        <h3>Produkt 2</h3>
        <p>Beschreibung des Produkts.</p>
        <button>Zum Warenkorb hinzufügen</button>
      </div>
      <!-- Weitere Produkte hier -->
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Kontakt</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      
      <label for="email">E-Mail:</label>
      <input type="email" id="email" name="email" required>
      
      <label for="message">Nachricht:</label>
      <textarea id="message" name="message" required></textarea>
      
      <button type="submit">Senden</button>
    </form>
  </section>

  <footer>
    <p>© 2024 Mein Shop. Alle Rechte vorbehalten.</p>
  </footer>
</body>
</html>
