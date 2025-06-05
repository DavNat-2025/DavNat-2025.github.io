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
      <img src="https://www.google.com/imgres?q=platos%20culinarios&imgurl=https%3A%2F%2Fwww.elcaminoconcorreos.com%2Fadmin%2Ffiles%2Fcontents%2Fimages%2Farroz-a-la-zamorana-platos-tipicos-camino-de-santiago.jpg&imgrefurl=https%3A%2F%2Fwww.elcaminoconcorreos.com%2Fes%2Fblog%2Flos-platos-tpicos-que-debes-probar-en-el-camino-de-santiago&docid=l5DXjvD-n54ufM&tbnid=l2mQkFRNQbATBM&vet=12ahUKEwjv7uKzwNqNAxV7IUQIHSIOAIwQM3oECHAQAA..i&w=610&h=338&hcb=2&ved=2ahUKEwjv7uKzwNqNAxV7IUQIHSIOAIwQM3oECHAQAA">
      <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=800&q=80" alt="Ingredientes frescos">
      <img src="data:image/jpeg;base64,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">
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

