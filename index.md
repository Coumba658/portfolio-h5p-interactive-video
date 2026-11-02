
<style>
  body {
    background: #f5f7f2;
  }

  .portfolio {
    max-width: 1050px;
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
    margin-bottom: 38px;
  }

  .eyebrow {
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
    max-width: 720px;
    margin: 0 auto;
    line-height: 1.8;
    color: #edf6ef;
  }

  .section {
    margin: 42px 0;
  }

  .section-title {
    color: #173f35;
    font-size: 27px;
    margin-bottom: 10px;
  }

  .section-intro {
    color: #617168;
    line-height: 1.8;
    margin-bottom: 24px;
  }

  .course-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 18px;
  }

  .course-card {
    background: white;
    border: 1px solid #e0e8df;
    border-radius: 16px;
    padding: 23px 20px;
    box-shadow: 0 5px 18px rgba(30, 60, 40, 0.06);
    display: flex;
    flex-direction: column;
  }

  .course-tag {
    color: #26745b;
    font-size: 11px;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 1px;
  }

  .course-card h3 {
    color: #173f35;
    font-size: 19px;
    line-height: 1.4;
    margin: 13px 0 10px;
  }

  .course-card p {
    color: #617168;
    font-size: 14px;
    line-height: 1.75;
    flex-grow: 1;
  }

  .course-link {
    display: block;
    text-align: center;
    margin-top: 15px;
    padding: 12px 10px;
    background: #26745b;
    color: white !important;
    text-decoration: none !important;
    font-size: 14px;
    font-weight: bold;
    border-radius: 9px;
  }

  .course-link:hover {
    background: #173f35;
  }

  .secondary-link {
    background: #e9f1e5;
    color: #173f35 !important;
  }

  .secondary-link:hover {
    background: #d8e7d2;
  }

  .notice {
    padding: 12px 14px;
    background: #f3f5ee;
    border-radius: 9px;
    color: #617168;
    font-size: 12px;
    line-height: 1.6;
    margin-top: 12px;
  }

  .method {
    background: #e9f1e5;
    border-radius: 16px;
    padding: 24px;
    margin: 42px 0;
    line-height: 1.8;
  }

  .method h2 {
    color: #173f35;
    margin-top: 0;
  }

  .footer {
    border-top: 1px solid #dce5da;
    padding: 24px 10px;
    margin-top: 40px;
    text-align: center;
    color: #617168;
    font-size: 13px;
    line-height: 1.8;
  }

  @media (max-width: 800px) {
    .course-grid {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }

  @media (max-width: 560px) {
    .course-grid {
      grid-template-columns: 1fr;
    }

    .hero {
      padding: 35px 20px;
    }

    .hero h1 {
      font-size: 28px;
    }

    .section-title {
      font-size: 23px;
    }
  }
</style>

<div class="portfolio">

  <header class="hero">
    <div class="eyebrow">Portfolio · Ingénierie pédagogique</div>
    <h1>Conception de formations e-learning</h1>
    <p>
      Découvrez une sélection de ressources et de cours numériques conçus
      pour transformer des contenus techniques en expériences
      d'apprentissage structurées, interactives et adaptées aux besoins
      des apprenants.
    </p>
  </header>

  <section class="section">
    <h2 class="section-title">01 · Vidéos interactives — Filière mangue</h2>
    <p class="section-intro">
      Une série de ressources audiovisuelles interactives consacrées aux
      bonnes pratiques de la filière mangue, de l'agréage au
      pré-refroidissement et à l'empotage.
    </p>

    <div class="course-grid">

      <article class="course-card">
        <div class="course-tag">Vidéo interactive · 01</div>
        <h3>Agréage des mangues</h3>
        <p>
          Contrôle à la réception, examen de la qualité et identification
          des défauts pouvant affecter la conformité des fruits.
        </p>
        <a class="course-link"
           href="https://agreage-recole.netlify.app/"
           target="_blank" rel="noopener noreferrer">
          Voir la vidéo ↗
        </a>
      </article>

      <article class="course-card">
        <div class="course-tag">Vidéo interactive · 02</div>
        <h3>Pesée et calibrage</h3>
        <p>
          Comprendre le classement des mangues selon leur poids et leur
          calibre afin de constituer des lots homogènes.
        </p>
        <a class="course-link"
           href="https://pesee-et-calibrage.netlify.app/"
           target="_blank" rel="noopener noreferrer">
          Voir la vidéo ↗
        </a>
      </article>

      <article class="course-card">
        <div class="course-tag">Vidéo interactive · 03</div>
        <h3>Pré-refroidissement et empotage</h3>
        <p>
          Découvrir les principes de refroidissement et les bonnes
          pratiques de préparation des palettes avant le transport.
        </p>
        <a class="course-link"
           href="https://precooling-et-empotage.netlify.app/"
           target="_blank" rel="noopener noreferrer">
          Voir la vidéo ↗
        </a>
      </article>

    </div>
  </section>

  <section class="section">
    <h2 class="section-title">02 · Santé et sécurité au travail</h2>
    <p class="section-intro">
      Modules développés dans le cadre d'une formation de renforcement
      des capacités destinée aux inspecteurs et contrôleurs du travail
      du Sénégal. Les contenus portent sur l'utilisation des instruments
      de mesure des facteurs d'ambiance et la planification stratégique
      des missions de contrôle. Ils intègrent des scénarios, des quiz
      et des vidéos pour favoriser les apprentissages pratiques.
    </p>

    <div class="course-grid">

      <article class="course-card">
        <div class="course-tag">Instrument de mesure</div>
        <h3>Luxmètre</h3>
        <p>
          Ressource consacrée à l'utilisation du luxmètre pour mesurer
          l'éclairement dans les environnements de travail.
        </p>
        <a class="course-link"
           href="https://luxmetre.netlify.app/"
           target="_blank" rel="noopener noreferrer">
          Consulter le module ↗
        </a>
      </article>

      <article class="course-card">
        <div class="course-tag">Instrument de mesure</div>
        <h3>Sonomètre</h3>
        <p>
          Ressource sur la mesure du bruit au travail et l'utilisation
          du sonomètre dans le cadre des contrôles.
        </p>
        <a class="course-link"
           href="https://sonometre.netlify.app/"
           target="_blank" rel="noopener noreferrer">
          Consulter le module ↗
        </a>
      </article>

      <article class="course-card">
        <div class="course-tag">Instrument de mesure</div>
        <h3>Indice WBGT</h3>
        <p>
          Présentation de l'indice WBGT et de son utilisation pour
          évaluer les contraintes thermiques liées à la chaleur.
        </p>
        <a class="course-link"
           href="https://wbgt.netlify.app/"
           target="_blank" rel="noopener noreferrer">
          Consulter le module ↗
        </a>
      </article>

      <article class="course-card">
        <div class="course-tag">Détection des risques</div>
        <h3>Détecteur de gaz</h3>
        <p>
          Ressource pédagogique dédiée à la découverte du détecteur
          de gaz et à son utilisation dans les situations de contrôle.
        </p>
        <a class="course-link"
           href="https://detecteur-de-gaz.netlify.app/"
           target="_blank" rel="noopener noreferrer">
          Consulter le module ↗
        </a>
      </article>

    </div>

    <div class="notice">
      Formation conçue pour un public professionnel spécifique.
      L'accès aux ressources et leur diffusion restent soumis aux
      conditions du dispositif de formation concerné.
    </div>
  </section>

  <section class="section">
    <h2 class="section-title">03 · Production et conditionnement de la mangue</h2>
    <p class="section-intro">
      Deux cours consacrés aux bonnes pratiques de production, de récolte
      et de conditionnement de la mangue, accessibles sur la plateforme
      de formation ATINGI.
    </p>

    <div class="course-grid">

      <article class="course-card">
        <div class="course-tag">Cours e-learning · ATINGI</div>
        <h3>Bonnes pratiques de production et de récolte</h3>
        <p>
          Parcours de formation sur les pratiques à adopter pour la
          production et la récolte des mangues.
        </p>
        <a class="course-link"
           href="https://online.atingi.org/course/view.php?id=6316"
           target="_blank" rel="noopener noreferrer">
          Accéder au cours ↗
        </a>
      </article>

      <article class="course-card">
        <div class="course-tag">Cours e-learning · ATINGI</div>
        <h3>Bonnes pratiques de conditionnement</h3>
        <p>
          Parcours dédié aux opérations de conditionnement et aux pratiques
          contribuant à préserver la qualité des mangues.
        </p>
        <a class="course-link"
           href="https://online.atingi.org/course/view.php?id=6395"
           target="_blank" rel="noopener noreferrer">
          Accéder au cours ↗
        </a>
      </article>

    </div>
  </section>

  <section class="section">
    <h2 class="section-title">04 · Formation de formateurs — Biotrade</h2>
    <p class="section-intro">
      Un parcours destiné aux acteurs du biotrade dans quatre pays
      partenaires : le Cameroun, Madagascar, la Namibie et l'Afrique du
      Sud. Il vise à outiller les formateurs locaux pour transmettre
      les bonnes pratiques de la filière sur le terrain.
    </p>

    <div class="course-grid">

      <article class="course-card">
        <div class="course-tag">Formation de formateurs · FR</div>
        <h3>Former les acteurs du biotrade — Français</h3>
        <p>
          Version française du parcours pour accompagner les formateurs
          locaux dans la transmission des bonnes pratiques.
        </p>
        <a class="course-link"
           href="https://online.atingi.org/local/partner/page.php?id=44"
           target="_blank" rel="noopener noreferrer">
          Accéder à la version française ↗
        </a>
      </article>

      <article class="course-card">
        <div class="course-tag">Training of trainers · EN</div>
        <h3>Biotrade Training of Trainers — English</h3>
        <p>
          English version of the training pathway for local trainers
          supporting the transfer of good practices in partner countries.
        </p>
        <a class="course-link"
           href="https://online.atingi.org/local/partner/page.php?id=45"
           target="_blank" rel="noopener noreferrer">
          Access the English version ↗
        </a>
      </article>

    </div>
  </section>

  <section class="method">
    <h2>Une approche centrée sur l'apprentissage</h2>
    <p>
      Ces réalisations mobilisent différents formats pédagogiques :
      vidéos, scénarios, quiz, activités interactives et parcours
      structurés sur des plateformes de formation. L'objectif est
      de rendre les contenus techniques plus accessibles et de favoriser
      leur appropriation par les publics ciblés.
    </p>
  </section>

  <footer class="footer">
    <p><strong>Portfolio de conception pédagogique e-learning</strong></p>
    <p>
      Ingénierie pédagogique · Ressources interactives ·
      Digital learning
    </p>
  </footer>

</div>
