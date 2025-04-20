<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Benvenuto Sul Sito Di EclipseXbert</title>
  <style>
    /* Reset globale */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    html, body {
      width: 100%;
      height: 100%;
      font-family: Arial, sans-serif;
      color: white;
    }
    /* Background con immagine ridimensionata */
    body {
      background-image: url('images/eclipse.jpg');
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
      background-attachment: fixed;
    }
    /* Sezione hero a schermo intero */
    .hero {
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    /* Titolo principale */
    .top-title {
      font-size: 4em;
      margin-bottom: 0.5em;
      color: #FFD700;
    }
    /* Sottotitolo */
    .welcome {
      font-size: 1.5em;
      margin-bottom: 1em;
    }
    /* Bottone per il canale YouTube */
    .button {
      display: inline-block;
      padding: 15px 30px;
      background-color: #FFD700;
      color: black;
      font-size: 1.2em;
      text-decoration: none;
      border-radius: 5px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
      transition: transform 0.3s ease;
    }
    .button:hover {
      transform: scale(1.05);
    }
    /* Footer fissato in basso */
    footer {
      text-align: center;
      padding: 10px;
      color: #AAAAAA;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <!-- Sezione Hero -->
  <div class="hero">
    <div>
      <h1 class="top-title">EclipseXbert</h1>
      <p class="welcome">Benvenuto Sul Sito Di EclipseXbert</p>
      <a class="button" href="https://www.youtube.com/@EclipseXbert" target="_blank">
        Visita il canale YouTube
      </a>
    </div>
  </div>
  
  <!-- Footer -->
  <footer>
    <p>&copy; 2025 EclipseXbert. All rights reserved.</p>
  </footer>
</body>
</html>
