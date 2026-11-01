
<style>
  body {
    background: #f5f7f2;
  }

  .portfolio {
    max-width: 1000px;
    margin: 0 auto;
    color: #24352d;
    font-family: Arial, sans-serif;
  }

  .hero {
    padding: 48px 28px;
    border-radius: 22px;
    background: linear-gradient(135deg, #173f35, #26745b);
    color: white;
    text-align: center;
    margin-bottom: 35px;
  }

  .hero .eyebrow {
    color: #d7edbd;
    text-transform: uppercase;
    letter-spacing: 2px;
    font-size: 12px;
    font-weight: bold;
  }

  .hero h1 {
    color: white;
    font-size: 34px;
    line-height: 1.25;
    margin: 18px 0;
  }

  .hero p {
    max-width: 650px;
    margin: 0 auto;
    line-height: 1.8;
    color: #edf6ef;
  }

  .section-title {
    text-align: center;
    margin: 38px 0 8px;
    color: #173f35;
  }

  .intro {
    text-align: center;
    color: #617168;
    margin-bottom: 26px;
  }

  .video-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 18px;
    margin: 28px 0;
  }

  .video-card {
    background: white;
    border: 1px solid #e0e8df;
    border-radius: 16px;
    padding: 24px 20px;
    box-shadow: 0 5px 18px rgba(30, 60, 40, 0.06);
    display: flex;
    flex-direction: column;
  }

  .video-number {
    color: #26745b;
    font-size: 13px;
    font-weight: bold;
    letter-spacing: 1px;
  }

  .video-card h3 {
    color: #173f35;
    font-size: 20px;
    margin: 14px 0 10px;
  }

  .video-card p {
    color: #617168;
    line-height: 1.7;
    font-size: 14px;
    flex-grow: 1;
  }

  .video-link {
    display: block;
    text-align: center;
    margin-top: 16px;
    padding: 12px 10px;
    background: #26745b;
    color: white !important;
    text-decoration: none !important;
    font-weight: bold;
    border-radius: 9px;
  }

  .video-link:hover {
    background: #173f35;
  }

  .method {
    background: #e9f1e5;
    border-radius: 16px;
    padding: 22px;
    margin: 35px 0;
    line-height: 1.8;
  }

  .footer {
    border-top: 1px solid #dce5da;
    padding: 22px 10px;
    margin-top: 35px;
    text-align: center;
    color: #617168;
    font-size: 13px;
  }

  @media (max-width: 700px) {
    .video-grid {
      grid-template-columns: 1fr;
    }

    .hero {
      padding: 35px 20px;
    }

    .hero h1 {
      font-size: 28px;
    }
  }
</style>

<div class="portfolio">

  <header class="hero">
    <div class="eyebrow">Portfolio e-learning · Ressources interactives</div>
    <h1>Les bonnes pratiques de la mangue</h1>
    <p>
      Découvrez une série de vidéos interactives consacrées aux étapes clés
      de la préparation des mangues, de l'agréage jusqu'au conditionnement
      avant l'expédition.
    </p>
  </header>

  <h2 class="section-title">Explorez les vidéos</h2>
  <p class="intro">
    Trois ressources pour comprendre les opérations et retenir les bonnes pratiques.
  </p>

  <div class="video-grid">

    <article class="video-card">
      <div class="video-number">VIDÉO 01</div>
      <h3>Agréage des mangues</h3>
      <p>
        Découvrez comment contrôler les mangues à la réception, examiner
        leur qualité et identifier les défauts avant la suite du processus.
      </p>
      <a class="video-link"
         href="https://agreage-recole.netlify.app/"
         target="_blank" rel="noopener noreferrer">
        ▶ Voir la vidéo
      </a>
    </article>

    <article class="video-card">
      <div class="video-number">VIDÉO 02</div>
      <h3>Pesée et calibrage</h3>
      <p>
        Comprenez le rôle de la pesée et du calibrage dans la constitution
        de lots homogènes et le respect des exigences de conditionnement.
      </p>
      <a class="video-link"
         href="https://pesee-et-calibrage.netlify.app/"
         target="_blank" rel="noopener noreferrer">
        ▶ Voir la vidéo
      </a>
    </article>

    <article class="video-card">
      <div class="video-number">VIDÉO 03</div>
      <h3>Pré-refroidissement et empotage</h3>
      <p>
        Retrouvez les principes essentiels du refroidissement des mangues
        et de la préparation des palettes pour le transport en conteneur.
      </p>
      <a class="video-link"
         href="https://precooling-et-empotage.netlify.app/"
         target="_blank" rel="noopener noreferrer">
        ▶ Voir la vidéo
      </a>
    </article>

  </div>

  <section class="method">
    <h2>Apprendre en interagissant</h2>
    <p>
      Chaque ressource associe des explications audiovisuelles à des
      questions interactives pour favoriser l'attention, vérifier la
      compréhension et renforcer la mémorisation des notions essentielles.
    </p>
  </section>

  <footer class="footer">
    <p><strong>Ressources de formation e-learning</strong></p>
    <p>Transformation de contenus techniques en expériences d'apprentissage interactives.</p>
  </footer>

</div>
