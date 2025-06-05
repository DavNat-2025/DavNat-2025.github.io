<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>DavNat-2025 | Cocina Creativa</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to right, #ff9966, #ff5e62);
      color: #fff;
      text-align: center;
      padding: 50px 20px;
    }
    h1, h2 {
      font-size: 2.5em;
      margin-bottom: 20px;
    }
    p, li {
      font-size: 1.2em;
      max-width: 800px;
      margin: 0 auto 20px auto;
    }
    a.button {
      display: inline-block;
      padding: 15px 30px;
      background-color: #fff;
      color: #ff5e62;
      text-decoration: none;
      font-weight: bold;
      border-radius: 30px;
      transition: background 0.3s, color 0.3s;
      margin: 20px auto 40px auto;
    }
    a.button:hover {
      background-color: #ff5e62;
      color: #fff;
    }
    .gallery, .recipes, .tips {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 40px;
    }
    .gallery img, .recipe img {
      width: 250px;
      height: 180px;
      object-fit: cover;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
      transition: transform 0.3s ease;
    }
    .gallery img:hover, .recipe img:hover {
      transform: scale(1.05);
    }
    .recipe {
      background-color: rgba(255, 255, 255, 0.1);
      padding: 20px;
      border-radius: 20px;
      width: 280px;
      text-align: left;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
    }
    .recipe h3 {
      margin-top: 10px;
      font-size: 1.4em;
    }
    .recipe p {
      font-size: 1em;
    }
    footer {
      margin-top: 60px;
      font-size: 0.9em;
    }
    .section {
      margin: 60px 0;
    }
    ul {
      text-align: left;
      margin-left: auto;
      margin-right: auto;
      max-width: 600px;
    }
    iframe {
      border-radius: 20px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <h1>🍳 DavNat-2025 🍰</h1>
  <p>Bienvenid@ a <strong>DavNat-2025</strong>, tu rincón para aprender, disfrutar y compartir el arte de la cocina. Aquí encontrarás recetas deliciosas, técnicas fáciles, ingredientes frescos y mucha pasión culinaria.</p>
  <a href="https://github.com/DavNat-2025" target="_blank" class="button">Explora nuestro GitHub</a>

  <div class="section">
    <h2>🔍 ¿Quiénes somos?</h2>
    <p>Somos una comunidad de jóvenes apasionados por la cocina. Queremos ayudarte a descubrir el placer de cocinar en casa, experimentar con recetas saludables y sabrosas, y crear momentos inolvidables en torno a la comida.</p>
  </div>

  <div class="section">
    <h2>📸 Galería Culinaria</h2>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=800&q=80" alt="Pizza casera">
      <img src="https://images.unsplash.com/photo-1606756792152-6ae1dd7fbf5d?auto=format&fit=crop&w=800&q=80" alt="Postres variados">
      <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=800&q=80" alt="Ingredientes frescos">
      <img src="https://images.unsplash.com/photo-1523986371872-9d3ba2e2f642?auto=format&fit=crop&w=800&q=80" alt="Mesa servida">
    </div>
  </div>

  <div class="section">
    <h2>🍽 Recetas Destacadas</h2>
    <div class="recipes">
      <div class="recipe">
        <img src="https://images.unsplash.com/photo-1600628422012-72b1f0855f8c?auto=format&fit=crop&w=800&q=80" alt="Tostadas con aguacate">
        <h3>Tostadas con aguacate</h3>
        <p>Pan tostado con aguacate machacado, sal, limón, y un toque de chile. Perfecto para un desayuno rápido y nutritivo.</p>
      </div>
      <div class="recipe">
        <img src="https://images.unsplash.com/photo-1613145992275-b74dfd2dc961?auto=format&fit=crop&w=800&q=80" alt="Galletas de avena">
        <h3>Galletas de avena</h3>
        <p>Una receta fácil y saludable con avena, plátano y canela. Ideal como snack o postre casero.</p>
      </div>
      <div class="recipe">
        <img src="https://images.unsplash.com/photo-1600693251568-65f62dbb0316?auto=format&fit=crop&w=800&q=80" alt="Pasta al pesto">
        <h3>Pasta al pesto</h3>
        <p>Spaghetti con salsa de albahaca, nueces y aceite de oliva. ¡Listo en menos de 20 minutos!</p>
      </div>
    </div>
  </div>

  <div class="section">
    <h2>🧠 Consejos Culinarios</h2>
    <ul>
      <li>Lee la receta completa antes de comenzar.</li>
      <li>Usa ingredientes frescos para un mejor sabor.</li>
      <li>Mide bien las cantidades para evitar errores.</li>
      <li>No temas experimentar con especias.</li>
      <li>Limpia sobre la marcha para disfrutar más el resultado.</li>
    </ul>
  </div>

  <div class="section">
    <h2>🔗 Enlaces Recomendados</h2>
    <ul>
      <li><a href="https://www.recetasgratis.net" target="_blank">RecetasGratis.net</a> – Miles de recetas caseras y saludables.</li>
      <li><a href="https://www.directoalpaladar.com" target="_blank">Directo al Paladar</a> – Blog gastronómico con noticias y técnicas.</li>
      <li><a href="https://www.tastemade.com" target="_blank">Tastemade</a> – Videos creativos y recetas internacionales.</li>
    </ul>
  </div>

  <div class="section">
    <h2>🎥 Video Destacado</h2>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/4aZr5hZXP_s" title="Cómo hacer pasta casera - Receta fácil" frameborder="0" allowfullscreen></iframe>
  </div>

  <footer>
    &copy; 2025 DavNat-2025. Todos los derechos reservados. | Sitio desarrollado con ❤️ por apasionados de la cocina.
  </footer>
</body>
</html>
