<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>DavNat-2025 | Cocina Creativa</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Roboto&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #ff5e62;
      --secondary: #ff9966;
      --bg: #fff5f0;
      --text-dark: #333;
      --text-light: #fff;
    }
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Roboto', sans-serif;
      background-color: var(--bg);
      color: var(--text-dark);
      margin: 0;
      padding: 0;
    }
    header {
      background: linear-gradient(to right, var(--secondary), var(--primary));
      color: var(--text-light);
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3em;
      margin: 0;
    }
    header p {
      font-size: 1.2em;
      max-width: 600px;
      margin: 10px auto 0;
    }
    nav {
      background-color: var(--primary);
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 15px;
    }
    nav a {
      color: var(--text-light);
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: auto;
      text-align: center;
    }
    .section h2 {
      font-size: 2.5em;
      margin-bottom: 20px;
      color: var(--primary);
    }
    .gallery, .recipes, .tips {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 30px;
    }
    .gallery img, .recipe img {
      width: 280px;
      height: 190px;
      object-fit: cover;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      transition: transform 0.3s;
    }
    .gallery img:hover, .recipe img:hover {
      transform: scale(1.05);
    }
    .recipe {
      background: #fff;
      padding: 20px;
      border-radius: 15px;
      width: 300px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      text-align: left;
    }
    .recipe h3 {
      margin-top: 10px;
      font-size: 1.4em;
      color: var(--primary);
    }
    .recipe p {
      font-size: 1em;
      color: #555;
    }
    ul {
      text-align: left;
      max-width: 700px;
      margin: 0 auto;
    }
    ul li {
      margin: 10px 0;
    }
    iframe {
      border: none;
      border-radius: 15px;
      margin-top: 30px;
      max-width: 100%;
    }
    footer {
      background-color: var(--primary);
      color: var(--text-light);
      text-align: center;
      padding: 30px 20px;
      margin-top: 60px;
    }
  </style>
</head>
<body>
  <header>
    <h1>🍳 DavNat-2025</h1>
    <p>Tu rincón para aprender, disfrutar y compartir el arte de la cocina con creatividad e inspiración.</p>
  </header>

  <nav>
    <a href="#galeria">Galería</a>
    <a href="#recetas">Recetas</a>
    <a href="#consejos">Consejos</a>
    <a href="#video">Video</a>
    <a href="#enlaces">Enlaces</a>
  </nav>

  <section class="section" id="galeria">
    <h2>📸 Galería Culinaria</h2>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=800&q=80" alt="Pizza casera">
      <img src="https://images.unsplash.com/photo-1606756792152-6ae1dd7fbf5d?auto=format&fit=crop&w=800&q=80" alt="Postres variados">
      <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=800&q=80" alt="Ingredientes frescos">
      <img src="https://images.unsplash.com/photo-1523986371872-9d3ba2e2f642?auto=format&fit=crop&w=800&q=80" alt="Mesa servida">
    </div>
  </section>

  <section class="section" id="recetas">
    <h2>🍽 Recetas Destacadas</h2>
    <div class="recipes">
      <div class="recipe">
        <img src="https://images.unsplash.com/photo-1600628422012-72b1f0855f8c?auto=format&fit=crop&w=800&q=80" alt="Tostadas con aguacate">
        <h3>Tostadas con aguacate</h3>
        <p>Pan tostado con aguacate, sal, limón, y un toque de chile. Perfecto para un desayuno nutritivo.</p>
      </div>
      <div class="recipe">
        <img src="https://images.unsplash.com/photo-1613145992275-b74dfd2dc961?auto=format&fit=crop&w=800&q=80" alt="Galletas de avena">
        <h3>Galletas de avena</h3>
        <p>Saludables y fáciles, con avena, plátano y canela. Ideales como snack casero.</p>
      </div>
      <div class="recipe">
        <img src="https://images.unsplash.com/photo-1600693251568-65f62dbb0316?auto=format&fit=crop&w=800&q=80" alt="Pasta al pesto">
        <h3>Pasta al pesto</h3>
        <p>Spaghetti con pesto de albahaca y nuez, listo en menos de 20 minutos.</p>
      </div>
    </div>
  </section>

  <section class="section" id="consejos">
    <h2>🧠 Consejos Culinarios</h2>
    <ul>
      <li>Lee la receta completa antes de empezar.</li>
      <li>Usa ingredientes frescos siempre que sea posible.</li>
      <li>Prepara todos los ingredientes antes de cocinar.</li>
      <li>No temas experimentar con sabores.</li>
      <li>Mantén tu cocina ordenada durante el proceso.</li>
    </ul>
  </section>

  <section class="section" id="video">
    <h2>🎥 Video Destacado</h2>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/4aZr5hZXP_s" title="Cómo hacer pasta casera - Receta fácil" allowfullscreen></iframe>
  </section>

  <section class="section" id="enlaces">
    <h2>🔗 Enlaces Recomendados</h2>
    <ul>
      <li><a href="https://www.recetasgratis.net" target="_blank">RecetasGratis.net</a>: miles de recetas caseras y saludables.</li>
      <li><a href="https://www.directoalpaladar.com" target="_blank">Directo al Paladar</a>: blog gastronómico con recetas y técnicas.</li>
      <li><a href="https://www.tastemade.com" target="_blank">Tastemade</a>: videos creativos de recetas internacionales.</li>
    </ul>
  </section>

  <footer>
    &copy; 2025 DavNat-2025. Todos los derechos reservados. Sitio desarrollado con ❤️ por apasionados de la cocina.
  </footer>
</body>
</html>
