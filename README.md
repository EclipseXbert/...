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
    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.6);
      z-index: 1;
    }
    /* Sezione hero */
    .hero {
      position: relative;
      display: flex;
      flex-direction: column; /* Mette i link in verticale */
      align-items: flex-start; /* Allinea i contenuti a sinistra */
      padding: 50px; /* Spazio per separare dal bordo */
      z-index: 2;
    }
    /* Titolo principale */
    .top-title {
      text-align: center;
      font-size: 3em;
      color: #6A5ACD;
      margin-bottom: 10px;
    }
    .welcome {
      text-align: center;
      font-size: 1.2em;
      color: #6A5ACD;
      margin-bottom: 30px;
    }
    /* Stile dei link */
    .button {
      display: block; /* Ogni link occupa una nuova riga */
      background: #6A5ACD;
      color: black;
      padding: 10px 20px;
      margin: 10px 0;
      text-decoration: none;
      border-radius: 5px;
      text-align: left; /* Allinea il testo del link a sinistra */
      box-shadow
