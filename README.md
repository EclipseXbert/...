
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Benvenuto Sul Sito Di EclipseXbert</title>
  <style>
    /* Impostazioni globali */
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      font-family: Arial, sans-serif;
      color: #E0E0E0;
    }
    /* Header */
    header {
      background-color: rgba(51, 51, 51, 0.8);
      padding: 20px;
      text-align: center;
      position: relative;
      z-index: 2;
    }
    header .top-title {
      margin: 0;
      font-size: 2em;
      color: #FFD700; /* EclipseXbert in giallo */
    }
    header .welcome {
      margin: 0;
      font-size: 1.5em;
      color: #FFFFFF; /* Testo bianco */
    }
    /* Sezione hero con background: immagine + sfumatura */
    section.hero {
      width: 100%;
      height: 100vh; /* Occupiamo tutta la viewport */
      background: 
        linear-gradient(180deg, #B8860B, #FF8C00, #FF0000, #000000),
        url('https://leganerd.com/wp-content/uploads/2022/05/storie_di_immaginaria_realta_sole_eclisse_artwork_fantasy.jpg');
      background-size: cover;
      background-position: center;
      background-blend-mode: multiply;
      position: relative;
      z-index: 1;
    }
    /* Sezione contenuto */
    section.content {
      text-align: center;
      background-color: rgba(30, 30, 30, 0.8);
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
      margin: 20px;
      position: relative;
      z-index: 2;
    }
    section.content h2,
    section.content p {
      margin: 10px 0;
    }
    section.content a {
      color: #FFD700;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.2em;
    }
    section.content a:hover {
      text-decoration: underline;
    }
    /* Footer */
    footer {
      background-color: rgba(51, 51, 51, 0.8);
      text-align: center;
      padding: 10px;
      color: #AAAAAA;
      font-size: 14px;
      margin-top: 20px;
      position: relative;
      z-index: 2;
    }
  </style>
</head>
<body>
  <header>
    <!-- Prima riga: EclipseXbert in giallo -->
    <h1 class="top-title">EclipseXbert</h1>
    <!-- Seconda riga: Benvenuto Sul Sito Di EclipseXbert in bianco -->
    <p class="welcome">Benvenuto Sul Sito Di EclipseXbert</p>
  </header>
  
  <!-- Sezione hero: sfondo composto da immagine e gradient -->
  <section class="hero"></section>
  
  <main>
    <!-- Sezione contenuto: testo e link centrati -->
    <section class="content">
      <h2>Clicca il link che troverai sotto e ovviamente seguimi!</h2>
      <p>Clicca qua sotto:</p>
      <a href="https://www.youtube.com/@EclipseXbert" target="_blank">EclipseXbert channels</a>
    </section>
  </main>
  
  <footer>
    <p>&copy; 2025 My Website. All rights reserved.</p>
  </footer>
</body>
</html>
