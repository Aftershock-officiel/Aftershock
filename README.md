<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Aftershock - Clément Jovanovic | Combattant MMA</title>
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background: #0d0d0d;
      color: #f1f1f1;
      line-height: 1.6;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    header {
      background: linear-gradient(90deg, #b30000, #330000);
      padding: 30px 20px;
      text-align: center;
      border-bottom: 4px solid #ff1a1a;
      box-shadow: 0 4px 10px rgba(179, 0, 0, 0.7);
    }

    header h1 {
      font-size: 3rem;
      font-weight: 900;
      letter-spacing: 4px;
      text-transform: uppercase;
      color: #fff;
      text-shadow: 2px 2px 6px #ff1a1a;
    }

    header h2 {
      font-weight: 700;
      color: #ff4d4d;
      font-size: 1.5rem;
      margin-top: 8px;
      font-style: italic;
    }

    main {
      flex-grow: 1;
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    .profile {
      display: flex;
      align-items: center;
      gap: 30px;
      margin-bottom: 40px;
      flex-wrap: wrap;
    }

    .photo {
      flex-shrink: 0;
      width: 180px;
      height: 180px;
      border-radius: 12px;
      border: 4px solid #ff1a1a;
      background: url('photo.jpg') center/cover no-repeat;
      box-shadow: 0 0 20px #ff1a1a;
    }

    .info {
      flex: 1;
      min-width: 250px;
    }

    .info h3 {
      font-size: 2rem;
      color: #ff1a1a;
      margin-bottom: 6px;
      text-transform: uppercase;
      letter-spacing: 3px;
    }

    .info p {
      font-size: 1.1rem;
      margin-bottom: 12px;
      color: #ddd;
    }

    section {
      margin-bottom: 40px;
      background: #1a1a1a;
      padding: 25px 30px;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(255, 26, 26, 0.5);
    }

    section h2 {
      color: #ff1a1a;
      margin-bottom: 20px;
      font-size: 2rem;
      border-bottom: 3px solid #ff1a1a;
      padding-bottom: 6px;
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
    }

    th, td {
      padding: 12px 15px;
      text-align: left;
      border-bottom: 1px solid #330000;
      color: #f1f1f1;
    }

    th {
      background: #ff1a1a;
      color: #fff;
      font-weight: 700;
      text-transform: uppercase;
    }

    ul {
      list-style: none;
      color: #ccc;
    }

    ul li {
      padding-left: 1.2em;
      margin-bottom: 10px;
      position: relative;
    }

    ul li::before {
      content: "✔";
      color: #ff1a1a;
      position: absolute;
      left: 0;
      font-weight: bold;
    }

    .devise {
      font-style: italic;
      font-size: 1.3rem;
      text-align: center;
      margin-top: 30px;
      color: #ff4d4d;
      text-shadow: 1px 1px 5px #990000;
      max-width: 700px;
      margin-left: auto;
      margin-right: auto;
    }

    footer {
      background: #1a1a1a;
      text-align: center;
      padding: 15px 10px;
      color: #660000;
      font-size: 0.9rem;
      border-top: 2px solid #330000;
      margin-top: auto;
      font-style: italic;
    }

    /* Responsive */
    @media (max-width: 600px) {
      .profile {
        flex-direction: column;
        align-items: center;
      }

      .photo {
        width: 140px;
        height: 140px;
      }

      .info h3 {
        font-size: 1.5rem;
        text-align: center;
      }

      .devise {
        font-size: 1.1rem;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Aftershock</h1>
  <h2>Clément Jovanovic</h2>
</header>

<main>
  <div class="profile">
    <div class="photo" aria-label="Photo de Clément Jovanovic"></div>
    <div class="info">
      <h3>Combattant MMA - Remiseur Stratégique</h3>
      <p><strong>Taille :</strong> 1m55 &nbsp;&nbsp;&nbsp; <strong>Poids :</strong> 38 kg &nbsp;&nbsp;&nbsp; <strong>Catégorie :</strong> Poids plume</p>
      <p>Clément, alias <strong>Aftershock</strong>, est un combattant patient et calculateur. Sa force réside dans ses contre-attaques précises et dévastatrices. Il n’attaque jamais sans analyser d’abord les mouvements adverses, ce qui fait de lui un expert du timing et de la stratégie sur le ring.</p>
    </div>
  </div>

  <section>
    <h2>Caractéristiques Clés</h2>
    <table>
      <thead>
        <tr><th>Compétence</th><th>Niveau</th></tr>
      </thead>
      <tbody>
        <tr><td>Précision des coups</td><td>85 %</td></tr>
        <tr><td>Vitesse de réaction</td><td>Très élevée</td></tr>
        <tr><td>Endurance</td><td>Solide</td></tr>
        <tr><td>Force</td><td>Moyenne mais explosive</td></tr>
        <tr><td>Technique de contre-attaque</td><td>Exemplaire</td></tr>
      </tbody>
    </table>
  </section>

  <section>
    <h2>Points Forts</h2>
    <ul>
      <li>Analyse en temps réel exceptionnelle</li>
      <li>Riposte rapide et dévastatrice</li>
      <li>Mental d’acier et sang-froid impressionnant</li>
      <li>Endurance et résistance physique remarquables</li>
    </ul>
  </section>

  <section>
    <h2>Techniques favorites</h2>
    <ul>
      <li>Contre-attaque directe</li>
      <li>Esquive et déplacement rapide</li>
      <li>Combinaisons précises après feintes adverses</li>
      <li>Utilisation d’angles et de timing optimal</li>
    </ul>
  </section>

  <section>
    <h2>Objectifs</h2>
    <ul>
      <li>Devenir un combattant professionnel reconnu</li>
      <li>Affiner encore la technique de remise</li>
      <li>Développer puissance et vitesse</li>
      <li>Intégrer une équipe d’élite et concourir à l’international</li>
    </ul>
  </section>

  <div class="devise">
    <p>« Tu crois m’avoir touché. C’est après que tout s’écroule. »</p>
    <p><em>"You think you've hit me. That's when everything falls apart."</em></p>
  </div>
</main>

<footer>
  © 2025 Clément "Aftershock" Jovanovic — Tous droits réservés
</footer>

</body>
</html>
