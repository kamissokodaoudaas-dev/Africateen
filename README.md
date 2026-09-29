# Africateen
Pour apprendre des lećon à coder
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Réussite Jeune</title>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  background: #f5f7fb;
  color: #172033;
  line-height: 1.6;
}

header {
  background: #111827;
  color: white;
  padding: 18px;
  position: sticky;
  top: 0;
  z-index: 10;
}

nav {
  max-width: 1100px;
  margin: auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 15px;
}

.logo {
  font-size: 22px;
  font-weight: bold;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 5px;
  font-size: 14px;
}

.hero {
  padding: 70px 20px;
  text-align: center;
  background: linear-gradient(135deg, #2563eb, #7c3aed);
  color: white;
}

.hero h1 {
  font-size: 42px;
  margin-bottom: 15px;
}

.hero p {
  max-width: 650px;
  margin: auto;
  font-size: 18px;
}

.btn {
  display: inline-block;
  margin-top: 25px;
  padding: 13px 22px;
  background: white;
  color: #2563eb;
  text-decoration: none;
  border-radius: 10px;
  font-weight: bold;
}

section {
  max-width: 1100px;
  margin: auto;
  padding: 55px 20px;
}

section h2 {
  text-align: center;
  font-size: 30px;
  margin-bottom: 30px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  gap: 20px;
}

.card {
  background: white;
  padding: 24px;
  border-radius: 15px;
  box-shadow: 0 5px 20px rgba(0,0,0,.08);
}

.card h3 {
  margin-bottom: 10px;
}

.card a {
  color: #2563eb;
  font-weight: bold;
  text-decoration: none;
}

.premium {
  background: #111827;
  color: white;
  border-radius: 20px;
  padding: 40px 25px;
  text-align: center;
}

.price {
  font-size: 36px;
  font-weight: bold;
  margin: 15px 0;
}

.premium ul {
  list-style: none;
  max-width: 500px;
  margin: 20px auto;
  text-align: left;
}

.premium li {
  padding: 8px 0;
}

.premium .btn {
  background: #fbbf24;
  color: #111827;
}

.article {
  cursor: pointer;
}

footer {
  background: #111827;
  color: white;
  text-align: center;
  padding: 30px 15px;
}

footer a {
  color: white;
}

#message {
  display: none;
  margin-top: 20px;
  padding: 15px;
  background: #dcfce7;
  color: #166534;
  border-radius: 10px;
}

@media(max-width:700px) {
  nav {
    flex-direction: column;
  }

  nav a {
    font-size: 12px;
  }

  .hero h1 {
    font-size: 32px;
  }
}
</style>
</head>

<body>

<header>
<nav>
<div class="logo">🚀 Réussite Jeune</div>

<div>
<a href="#accueil">Accueil</a>
<a href="#revision">Révisions</a>
<a href="#ia">IA</a>
<a href="#jeux">Jeux</a>
<a href="#articles">Articles</a>
<a href="#premium">Premium</a>
</div>
</nav>
</header>

<!-- ACCUEIL -->

<div class="hero" id="accueil">
<h1>Réussite Jeune 🚀</h1>

<p>
Apprends, crée et progresse grâce à des ressources simples
sur les études, la technologie, l'IA et les projets numériques.
</p>

<a class="btn" href="#premium">
Découvrir Premium
</a>
</div>

<!-- REVISION -->

<section id="revision">

<h2>📚 Révisions</h2>

<div class="grid">

<div class="card">
<h3>🧠 Mieux mémoriser</h3>
<p>
Apprends une notion, ferme ton cours puis essaie
de l'expliquer avec tes propres mots.
</p>
</div>

<div class="card">
<h3>⏱️ Méthode 30 minutes</h3>
<p>
Travaille pendant 25 minutes sans distraction,
puis prends une courte pause.
</p>
</div>

<div class="card">
<h3>📝 Faire des fiches</h3>
<p>
Note uniquement les idées principales,
les définitions et quelques exemples.
</p>
</div>

<div class="card">
<h3>❓ Se tester</h3>
<p>
Transforme ton cours en questions et essaie
d'y répondre sans regarder tes notes.
</p>
</div>

</div>
</section>

<!-- IA -->

<section id="ia">

<h2>🤖 IA & outils</h2>

<div class="grid">

<div class="card">
<h3>ChatGPT</h3>
<p>Assistant IA pour apprendre, réfléchir et créer.</p>
<a href="https://chatgpt.com/" target="_blank">Visiter →</a>
</div>

<div class="card">
<h3>Gemini</h3>
<p>Assistant IA de Google.</p>
<a href="https://gemini.google.com/" target="_blank">Visiter →</a>
</div>

<div class="card">
<h3>Microsoft Copilot</h3>
<p>Assistant IA de Microsoft.</p>
<a href="https://copilot.microsoft.com/" target="_blank">Visiter →</a>
</div>

<div class="card">
<h3>Canva</h3>
<p>Création de visuels et présentations.</p>
<a href="https://www.canva.com/" target="_blank">Visiter →</a>
</div>

<div class="card">
<h3>Scratch</h3>
<p>Apprendre la programmation avec des blocs.</p>
<a href="https://scratch.mit.edu/" target="_blank">Visiter →</a>
</div>

<div class="card">
<h3>GitHub</h3>
<p>Découvrir et partager des projets de programmation.</p>
<a href="https://github.com/" target="_blank">Visiter →</a>
</div>

<div class="card">
<h3>Figma</h3>
<p>Créer des interfaces et prototypes.</p>
<a href="https://www.figma.com/" target="_blank">Visiter →</a>
</div>

<div class="card">
<h3>Khan Academy</h3>
<p>Ressources éducatives gratuites.</p>
<a href="https://www.khanacademy.org/" target="_blank">Visiter →</a>
</div>

<div class="card">
<h3>Google Drive</h3>
<p>Stocker et organiser ses fichiers.</p>
<a href="https://drive.google.com/" target="_blank">Visiter →</a>
</div>

<div class="card">
<h3>Google Docs</h3>
<p>Créer et modifier des documents en ligne.</p>
<a href="https://docs.google.com/" target="_blank">Visiter →</a>
</div>

</div>
</section>

<!-- JEUX -->

<section id="jeux">

<h2>🎮 Jeux à découvrir</h2>

<div class="grid">

<div class="card">
<h3>Subway Surfers</h3>
<p>Jeu de course et d'esquive.</p>
<a href="https://play.google.com/store/" target="_blank">Rechercher →</a>
</div>

<div class="card">
<h3>Hill Climb Racing</h3>
<p>Conduite et défis physiques.</p>
<a href="https://play.google.com/store/" target="_blank">Rechercher →</a>
</div>

<div class="card">
<h3>Brawlhalla</h3>
<p>Jeu de combat.</p>
<a href="https://play.google.com/store/" target="_blank">Rechercher →</a>
</div>

<div class="card">
<h3>Asphalt Legends</h3>
<p>Courses automobiles.</p>
<a href="https://play.google.com/store/" target="_blank">Rechercher →</a>
</div>

<div class="card">
<h3>Minecraft</h3>
<p>Construction et exploration.</p>
<a href="https://play.google.com/store/" target="_blank">Voir →</a>
</div>

<div class="card">
<h3>Roblox</h3>
<p>Plateforme regroupant de nombreuses expériences.</p>
<a href="https://play.google.com/store/" target="_blank">Voir →</a>
</div>

<div class="card">
<h3>Stumble Guys</h3>
<p>Parcours et défis.</p>
<a href="https://play.google.com/store/" target="_blank">Voir →</a>
</div>

<div class="card">
<h3>Shadow Fight</h3>
<p>Jeu de combat.</p>
<a href="https://play.google.com/store/" target="_blank">Voir →</a>
</div>

<div class="card">
<h3>Alto's Odyssey</h3>
<p>Course et exploration.</p>
<a href="https://play.google.com/store/" target="_blank">Voir →</a>
</div>

<div class="card">
<h3>Soul Knight</h3>
<p>Action et exploration.</p>
<a href="https://play.google.com/store/" target="_blank">Voir →</a>
</div>

</div>
</section>

<!-- ARTICLES -->

<section id="articles">

<h2>📰 Articles</h2>

<div class="grid">

<div class="card article">
<h3>1. Comment mieux apprendre</h3>
<p>
Travaille régulièrement, élimine les distractions
et teste tes connaissances.
</p>
</div>

<div class="card article">
<h3>2. Créer un site depuis son téléphone</h3>
<p>
Découvre les différentes étapes pour créer
et publier un premier site.
</p>
</div>

<div class="card article">
<h3>3. 10 façons d'utiliser l'IA</h3>
<p>
Utilise l'IA pour comprendre, réviser,
organiser et créer.
</p>
</div>

<div class="card article">
<h3>4. Commencer à programmer</h3>
<p>
Découvre les variables, conditions, boucles
et fonctions.
</p>
</div>

<div class="card article">
<h3>5. Créer son premier jeu</h3>
<p>
Commence avec un personnage, un objectif,
des obstacles et un score.
</p>
</div>

<div class="card article">
<h3>6. Protéger son compte</h3>
<p>
Utilise un mot de passe unique et
la vérification en deux étapes.
</p>
</div>

<div class="card article">
<h3>7. Économiser ses données mobiles</h3>
<p>
Identifie les applications qui consomment
le plus de données.
</p>
</div>

<div class="card article">
<h3>8. Organiser Android</h3>
<p>
Crée des dossiers pour tes photos,
documents et projets.
</p>
</div>

<div class="card article">
<h3>9. Créer un CV</h3>
<p>
Présente clairement ta formation,
tes compétences et tes projets.
</p>
</div>

<div class="card article">
<h3>10. Transformer une idée en projet</h3>
<p>
Idée → objectif → prototype → test → amélioration.
</p>
</div>

</div>
</section>

<!-- PROJETS -->

<section id="projets">

<h2>💡 Projets</h2>

<div class="grid">

<div class="card">
<h3>🌐 Créer un site</h3>
<p>Commence avec une page simple puis ajoute progressivement du contenu.</p>
</div>

<div class="card">
<h3>📱 Créer une application</h3>
<p>Pars d'un problème précis et construis une première version simple.</p>
</div>

<div class="card">
<h3>🎮 Créer un jeu</h3>
<p>Commence avec un gameplay simple avant d'ajouter de nouvelles fonctionnalités.</p>
</div>

<div class="card">
<h3>📖 Créer un ebook</h3>
<p>Choisis un sujet, écris tes chapitres puis crée ton document.</p>
</div>

</div>
</section>

<!-- PREMIUM -->

<section id="premium">

<div class="premium">

<h2>⭐ Réussite Jeune Premium</h2>

<p>
Accède à davantage de ressources pour apprendre,
créer et progresser.
</p>

<div class="price">
1 000 FCFA / mois
</div>

<ul>
<li>✅ 50 fiches de révision</li>
<li>✅ 100 quiz</li>
<li>✅ 30 guides IA</li>
<li>✅ 20 tutoriels de programmation</li>
<li>✅ 10 tutoriels pour créer des jeux</li>
<li>✅ 10 tutoriels pour créer des sites</li>
<li>✅ 20 astuces Android</li>
<li>✅ 10 modèles de CV</li>
<li>✅ 50 idées de projets</li>
<li>✅ Mini-ebook exclusif</li>
<li>✅ Nouveaux contenus régulièrement</li>
</ul>

<!-- REMPLACE CE LIEN PAR TON VRAI LIEN DE PAIEMENT -->

<a
class="btn"
href="https://example.com"
target="_blank">
💳 Accéder à Premium
</a>

<div id="message">
Après le paiement, l'accès Premium sera fourni selon les modalités indiquées.
</div>

</div>
</section>

<!-- A PROPOS -->

<section>

<h2>👋 À propos</h2>

<div class="card">

<p>
Réussite Jeune est un projet destiné à partager
des ressources simples autour de l'apprentissage,
de la technologie, de l'IA et de la création.
</p>

<br>

<p>
Notre objectif est d'aider les jeunes à passer
de l'idée à l'action.
</p>

<br>

<strong>
Apprendre aujourd'hui. Créer demain. 🚀
</strong>

</div>

</section>

<footer>

<p>© 2026 Réussite Jeune</p>

<p>
Apprendre • Créer • Progresser
</p>

</footer>

</body>
</html>
