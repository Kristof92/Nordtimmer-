<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>NORDTIMMER – Trälösningar för kvalitet och hållbarhet</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="background-overlay">
    <header>
      <h1>NORDTIMMER</h1>
      <p><em>Trälösningar för kvalitet och hållbarhet</em></p>
    </header>

    <section class="services">
      <h2>✅ Våra tjänster</h2>
      <div class="service">
        <div class="icon">🪵</div>
        <h3>Altaner & träverandor</h3>
        <p>Skräddarsydda träterrasser för hem och sommarhus.</p>
      </div>
      <div class="service">
        <div class="icon">⚓</div>
        <h3>Bryggor & båtplatser</h3>
        <p>Vi bygger säkra, stilrena bryggor vid sjöar och vattendrag.</p>
      </div>
      <div class="service">
        <div class="icon">🏠</div>
        <h3>Takarbeten</h3>
        <p>Nya tak, renoveringar och pålitligt takarbete i hela Sverige.</p>
      </div>
      <div class="service">
        <div class="icon">🪟</div>
        <h3>Fasader i trä</h3>
        <p>Ny träpanel eller restaurering med naturlig känsla.</p>
      </div>
    </section>

    <footer>
      <p>Kontakt: <a href="mailto:nekriskans@gmail.com">nekriskans@gmail.com</a> | 📞 <a href="tel:0760988708">0760 988 708</a></p>
      <p>© 2025 NORDTIMMER</p>
    </footer>
  </div>
</body>
</html>
body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  color: #fff;
  background: url('https://images.unsplash.com/photo-1616627982074-d9021a68e8f0?ixlib=rb-4.0.3&auto=format&fit=crop&w=1470&q=80') no-repeat center center fixed;
  background-size: cover;
}

.background-overlay {
  background-color: rgba(0, 0, 0, 0.6);
  min-height: 100vh;
  padding: 0;
}

header {
  text-align: center;
  padding: 2em 1em;
}

h1 {
  font-size: 2.5em;
  margin-bottom: 0.2em;
  color: #fff;
}

.services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1.5em;
  padding: 2em;
}

.service {
  background: rgba(255, 255, 255, 0.1);
  border: 1px solid #ddd;
  padding: 1.5em;
  border-radius: 8px;
  text-align: center;
  color: #fff;
  backdrop-filter: blur(2px);
}

.service .icon {
  font-size: 2em;
  margin-bottom: 0.5em;
}

footer {
  text-align: center;
  padding: 1.5em;
  font-size: 0.9em;
  background-color: rgba(0, 0, 0, 0.5);
}

a {
  color: #ffd700;
  text-decoration: none;
}
