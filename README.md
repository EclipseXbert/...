
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
    /* Background con immagine e overlay */
    body {
      background: url('https://i.pinimg.com/736x/e5/41/d3/e541d318a855faae36f7cee2e57b128f.jpg') no-repeat center center fixed;
      background-size: cover;
      position: relative;
    }
    /* Overlay scuro per migliorare la leggibilità */
    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.6);
      z-index: 1;
    }
    /* Sezione hero a schermo intero */
    .hero {
      position: relative;
      height: calc(84vh - 84px); /* Ridotta altezza per lasciare spazio al titolo */
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      z-index: 2;
      flex-direction: column; /* Imposta il layout verticale */
    }
    /* Contenitore centrale */
    .container {
      padding: 20px;
    }
    /* Titolo principale centrato più in alto */
    .top-title {
      position: absolute;
      top: -24px; /* Più vicino alla parte superiore della pagina */
      left: 50%;
      transform: translateX(-50%);
      font-size: 4em;
      color: #6A5ACD; /* Viola scuro chiaro */
      margin: 0; /* Rimuove eventuale spazio extra */
      text-align: center;
    }
    /* Sottotitolo */
    .welcome {
      position: absolute;
      top: 50px; /* Aggiungi spazio tra il titolo e il paragrafo */
      left: 50%;
      transform: translateX(-50%);
      color: #6A5ACD;
      margin: 0;
      font-size: 1.5em;
      text-align: center;
    }
    /* Bottone per i link */
    .button {
      display: inline-block;
      padding: 15px 30px;
      background: #6A5ACD;
      color: black;
      font-size: 1.2em;
      text-decoration: none;
      border-radius: 5px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
      margin: 10px 0; /* Spazio tra i bottoni */
      transition: transform 0.3s ease;
    }
    .button:hover {
      transform: scale(1.05);
      }
    /* Footer fissato in basso */
    footer {
      background: rgba(0, 0, 0, 0.5);
      text-align: center;
      padding: 10px;
      color: #AAAAAA;
      font-size: 14px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <!-- Overlay per rendere più leggibile il testo -->
  <div class="overlay"></div>
  
  <!-- Titolo Principale in alto centrato -->
  <h1 class="top-title">EclipseXbert</h1>
  <p class="welcome">Benvenuto Sul Sito Di EclipseXbert</p>
  
  <!-- Sezione Hero -->
  <div class="hero">
    <div class="container">
      <a class="button" href="https://youtu.be/VejTk-Lor8I?si=5lUsO5C_RrkizX3j" target="_blank">
        ZakShen - Memories (Euphoric Hardstyle)
      </a>
      <a class="button" href="https://www.youtube.com/@EclipseXbert" target="_blank">
        Visita il canale YouTube
      </a>
      <a class="button" href="https://youtu.be/uLHqpjW3aDs?si=frFD2qkqOQTEqLQU" target="_blank">
        Roddy Ricch - The Box [Official Audio]
      </a>
    </div>
  </div> 
  <!-- Footer -->
  <footer>
    <p>&copy; 2025 EclipseXbert. All rights reserved.</p>
  </footer>
  </body>
</html>
