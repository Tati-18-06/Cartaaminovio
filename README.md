# Cartaaminovio
Te amo ❤️
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Para Mi Amor 💖</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom right, #ffe6e6, #ffccff);
      color: #333;
      margin: 0;
      padding: 0;
      text-align: center;
    }

    header {
      padding: 2rem;
      background-color: #ff99cc;
      color: white;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
    }

    .content {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }

    .quote {
      font-style: italic;
      font-size: 1.5rem;
      margin: 2rem 0;
    }

    .photo-gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
      margin-top: 2rem;
    }

    .photo-gallery img {
      border-radius: 15px;
      width: 250px;
      height: auto;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      transition: transform 0.3s ease;
    }

    .photo-gallery img:hover {
      transform: scale(1.05);
    }

    .surprise-btn {
      background-color: #ff66a3;
      color: white;
      padding: 1rem 2rem;
      border: none;
      font-size: 1.2rem;
      border-radius: 10px;
      margin-top: 2rem;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    .surprise-btn:hover {
      background-color: #ff3385;
    }

    .hidden-message {
      margin-top: 2rem;
      font-size: 1.3rem;
      font-weight: bold;
      display: none;
      color: #d1006d;
    }

    footer {
      background-color: #ff99cc;
      color: white;
      padding: 1rem;
      font-size: 0.9rem;
      margin-top: 3rem;
    }

    audio {
      display: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Para Ti, Amor de Mi Vida 💕</h1>
    <p>Un pequeño rincón para recordarte cuánto te amo</p>
  </header>

  <div class="content">
    <div class="quote">"Eres mi sol en los días nublados, mi calma en la tormenta y mi alegría diaria."</div>

    <p>
      Cada momento contigo es un regalo que atesoro. Desde nuestras risas hasta nuestras charlas
      profundas, todo a tu lado tiene un significado especial. Gracias por ser tú, por apoyarme,
      por amarme y por hacerme sentir tan especial.
    </p>

    <!-- Galería -->
    <div class="photo-gallery">
      <img src="https://via.placeholder.com/250x180?text=Foto+1" alt="Foto 1">
      <img src="https://via.placeholder.com/250x180?text=Foto+2" alt="Foto 2">
      <img src="https://via.placeholder.com/250x180?text=Foto+3" alt="Foto 3">
    </div>

    <!-- Botón sorpresa -->
    <button class="surprise-btn" onclick="showSurprise()">Haz clic para una sorpresa 🎁</button>
    <div class="hidden-message" id="surpriseMessage">
      Te amo con todo mi corazón 💖. ¡Gracias por ser mi persona favorita en el mundo!
    </div>
  </div>

  <!-- Música -->
  <audio autoplay loop>
    <source src="https://www.bensound.com/bensound-music/bensound-love.mp3" type="audio/mpeg">
    Tu navegador no soporta música de fondo.
  </audio>

  <footer>
    Hecho con amor 💖 por [Tu Nombre]
  </footer>

  <script>
    function showSurprise() {
      const msg = document.getElementById("surpriseMessage");
      msg.style.display = "block";
    }
  </script>
</body>
</html>
