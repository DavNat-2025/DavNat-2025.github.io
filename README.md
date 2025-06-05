<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="description" content="Recetas, consejos y videos de cocina creativa. DavNat-2025 es tu sitio para aprender, experimentar y disfrutar la cocina.">
  <title>DavNat-2025 | Cocina Creativa</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Roboto&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #ff5e62;
      --secondary: #ff9966;
      --bg: #fffaf5;
      --text-dark: #2d2d2d;
      --text-light: #fff;
      --card-bg: #ffffff;
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
      line-height: 1.6;
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
      flex-wrap: wrap;
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
    .gallery, .recipes, .tips, .tools {
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
      background: var(--card-bg);
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
      max-width: 800px;
      margin: 0 auto;
      padding: 0 20px;
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
    .tools div {
      background: var(--card-bg);
      padding: 20px;
      border-radius: 10px;
      width: 250px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    footer {
      background-color: var(--primary);
      color: var(--text-light);
      text-align: center;
      padding: 30px 20px;
      margin-top: 60px;
    }
    form {
      margin-top: 30px;
    }
    input[type="email"] {
      padding: 10px;
      width: 250px;
      border-radius: 5px;
      border: 1px solid #ccc;
      margin-right: 10px;
    }
    button {
      background: var(--primary);
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background: var(--secondary);
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
    <a href="#utensilios">Utensilios</a>
    <a href="#planificacion">Planificación</a>
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
        <p>Pan tostado con aguacate, sal, limón y chile. Ideal para un desayuno saludable y rápido.</p>
      </div>
      <div class="recipe">
        <img src="https://images.unsplash.com/photo-1613145992275-b74dfd2dc961?auto=format&fit=crop&w=800&q=80" alt="Galletas de avena">
        <h3>Galletas de avena</h3>
        <p>Avena, plátano y canela: una combinación perfecta para un snack energético.</p>
      </div>
      <div class="recipe">
        <img src="https://images.unsplash.com/photo-1600693251568-65f62dbb0316?auto=format&fit=crop&w=800&q=80" alt="Pasta al pesto">
        <h3>Pasta al pesto</h3>
        <p>Una receta italiana clásica con albahaca fresca y nuez. Rápida y deliciosa.</p>
      </div>
    </div>
  </section>

  <section class="section" id="consejos">
    <h2>🧠 Consejos Culinarios</h2>
    <ul>
      <li>Lee la receta completa antes de comenzar a cocinar.</li>
      <li>Usa ingredientes de temporada para más sabor y economía.</li>
      <li>Mise en place: ten todo preparado antes de encender el fuego.</li>
      <li>Equilibra sabores: ácido, dulce, salado y umami.</li>
      <li>Limpia mientras cocinas para evitar desorden.</li>
    </ul>
  </section>

  <section class="section" id="utensilios">
    <h2>🍴 Utensilios Básicos de Cocina</h2>
    <div class="tools">
      <div><strong>Cuchillo de chef</strong><br>Indispensable para cortar cualquier alimento con precisión.</div>
      <div><strong>Tabla de cortar</strong><br>De madera o plástico, preferiblemente con base antideslizante.</div>
      <div><strong>Sartén antiadherente</strong><br>Ideal para freír, saltear o hacer huevos sin que se pegue nada.</div>
    </div>
  </section>

  <section class="section" id="planificacion">
    <h2>🗓 Planificación Semanal</h2>
    <p>Organiza tus comidas y compras con antelación para ahorrar tiempo y dinero.</p>
    <ul>
      <li>Haz una lista de recetas que deseas cocinar en la semana.</li>
      <li>Compra los ingredientes un solo día para ahorrar tiempo.</li>
      <li>Prepara comidas en lotes y congela porciones.</li>
    </ul>
  </section>

  <section class="section" id="video">
    <h2>🎥 Video Destacado</h2>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/4aZr5hZXP_s" title="Cómo hacer pasta casera - Receta fácil" allowfullscreen></iframe>
  </section>

  <section class="section" id="enlaces">
    <h2>🔗 Enlaces Recomendados</h2>
    <ul>
      <li><a href="https://www.recetasgratis.net" target="_blank">RecetasGratis.net</a> – Miles de recetas caseras con instrucciones claras.</li>
      <li><a href="https://www.directoalpaladar.com" target="_blank">Directo al Paladar</a> – Blog culinario con novedades y técnicas.</li>
      <li><a href="https://www.tastemade.com" target="_blank">Tastemade</a> – Videos e ideas creativas de comida de todo el mundo.</li>
      <li><a href="https://www.javirecetas.com" target="_blank">Javi Recetas</a> – Cocina española explicada paso a paso.</li>
      <li><a href="https://www.seriouseats.com/" target="_blank">Serious Eats</a> – Análisis científicos sobre técnicas de cocina.</li>
    </ul>

    <form>
      <label for="email"><strong>Suscríbete al boletín de recetas:</strong></label><br>
      <input type="email" id="email" name="email" placeholder="Tu correo electrónico" required>
      <button type="submit">Suscribirme</button>
    </form>
  </section>

  <footer>
    &copy; 2025 DavNat-2025. Todos los derechos reservados. Sitio desarrollado con ❤️ por apasionados de la cocina.
  </footer>
</body>
</html>

