<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mon Site Coloré</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #ff6f61, #6a5acd);
      color: white;
      text-align: center;
    }
    header {
      padding: 20px;
      background: rgba(0,0,0,0.3);
    }
    nav a {
      margin: 0 15px;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 50px;
    }
    button {
      background: #ffd700;
      border: none;
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
      border-radius: 5px;
    }
    button:hover {
      background: #ffa500;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bienvenue sur mon site coloré</h1>
    <nav>
      <a href="#about">À propos</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <section id="about">
    <h2>À propos</h2>
    <p>Voici un site simple et coloré pour présenter ton activité ou ton portfolio.</p>
  </section>
  <section id="services">
    <h2>Services</h2>
    <p>Ajoute ici ce que tu proposes !</p>
  </section>
  <section id="contact">
    <h2>Contact</h2>
    <button>Me contacter</button>
  </section>
</body>
</html>
