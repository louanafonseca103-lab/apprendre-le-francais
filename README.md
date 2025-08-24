# apprendre-le-francais
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Apprendre le Français</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Bienvenue sur "Apprendre le Français"</h1>
    <p>Un site simple pour progresser en français</p>
  </header>

  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#lecons">Leçons</a>
    <a href="#exercices">Exercices</a>
    <a href="#contact">Contact</a>
  </nav>

  <main>
    <section id="accueil">
      <h2>Accueil</h2>
      <p>Bienvenue ! Ici tu peux apprendre du vocabulaire, des bases de grammaire et t’exercer.</p>
    </section>

    <section id="lecons">
      <h2>Leçons</h2>
      <ul>
        <li>Leçon 1 : Salutations</li>
        <li>Leçon 2 : Les chiffres</li>
        <li>Leçon 3 : Les couleurs</li>
      </ul>
    </section>

    <section id="exercices">
      <h2>Exercices</h2>
      <p>Bientôt disponibles !</p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email : <a href="mailto:exemple@email.com">exemple@email.com</a></p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Apprendre le Français</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  background-color: #f9f9f9;
}

header {
  background: #2c3e50;
  color: white;
  padding: 1rem;
  text-align: center;
}

nav {
  background: #34495e;
  display: flex;
  justify-content: center;
}

nav a {
  color: white;
  padding: 1rem;
  text-decoration: none;
}

nav a:hover {
  background: #2c3e50;
}

main {
  padding: 2rem;
}

section {
  margin-bottom: 2rem;
  background: white;
  padding: 1rem;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

footer {
  background: #2c3e50;
  color: white;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}
console.log("Bienvenue sur le site d'apprentissage du français !");
